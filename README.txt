BANCO UFPR — VERSÃO 0.3 (PWA LOCAL)

Conteúdo
- index.html: interface do app
- questions.js: banco inicial da UFPR 2025
- Geral.pdf: prova original para consulta de páginas
- manifest.webmanifest, icon.svg, sw.js: instalação PWA e cache offline

O que funciona nesta versão
- filtros por matéria, tema, subtema e texto
- selecionar alternativa e confirmar antes de revelar a correção
- marcar questões para revisar
- importar banco de questões em formato JSON
- exportar backup JSON do banco atual
- tentativa de cache offline via service worker quando hospedado em HTTPS

Importação JSON
Aceita um arquivo JSON que seja diretamente uma lista de questões, ou um objeto com uma propriedade "questions" ou "UFPR_QUESTIONS" que contenha a lista. Cada questão precisa ter id e options_extracted. Campos esperados seguem o formato do arquivo questions.js.

Duplicatas
O campo id é usado como chave. IDs novos são adicionados. IDs existentes são atualizados pelo conteúdo importado. Portanto, use IDs estáveis e únicos para cada questão.

Limitações conhecidas
- Esta versão importa JSON, não PDF nem ZIP diretamente.
- Questões importadas com PDFs próprios precisam incluir o PDF no pacote publicado e o campo source_pdf precisa apontar para o arquivo correto; o botão de página original desta versão está orientado ao PDF Geral.pdf da UFPR 2025.
- Dados e marcações são armazenados no navegador do dispositivo. Use Exportar backup regularmente. Limpar dados do navegador pode apagar o banco importado.
- Para instalar como app no iPad, publique todos os arquivos em uma hospedagem HTTPS. Abra o endereço no Safari e use Compartilhar > Adicionar à Tela de Início.
- O Service Worker e o modo instalável precisam ser testados no endereço final HTTPS.

Esta é uma primeira versão funcional para validação, não uma versão publicada.
