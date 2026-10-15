BANCO UFPR — APP INSTALÁVEL (PWA) v1.0

O pacote contém o aplicativo web progressivo (PWA) pronto para ser publicado em hospedagem HTTPS.

ARQUIVOS PRINCIPAIS
- index.html: interface e lógica do aplicativo
- questions.js: banco de questões incluído
- Geral.pdf: prova original para consultar páginas
- manifest.webmanifest: nome, ícones e comportamento de instalação
- sw.js: cache dos arquivos principais para acesso offline após a primeira carga
- icon-192.png, icon-512.png, apple-touch-icon.png, icon.svg: ícones do app

PUBLICAÇÃO
Envie TODOS os arquivos desta pasta para a raiz (/) do repositório GitHub Pages, mantendo os nomes. O arquivo index.html deve ficar na raiz, não dentro de uma subpasta. Em Settings > Pages, use Deploy from a branch, branch main e pasta /(root).

INSTALAÇÃO NO IPHONE
1. Abra https://gabrielurio25-prog.github.io/banco-ufpr/ no Safari.
2. Toque em Compartilhar.
3. Escolha Adicionar à Tela de Início.
4. Confirme o nome Banco UFPR e toque em Adicionar.

INSTALAÇÃO NO ANDROID
Abra o site no Chrome e use o menu do navegador para instalar/adicionar à tela inicial, se a opção estiver disponível.

RECURSOS ATUAIS
- filtros por matéria, tema, subtema e texto
- responder e confirmar alternativa antes de ver a correção
- marcar questões para revisar
- importar questões em JSON e exportar backup JSON
- cache dos arquivos principais para uso offline depois que forem carregados

LIMITAÇÕES IMPORTANTES
- Não é um app nativo publicado na App Store/Google Play; é um PWA instalável pela web.
- Importação direta de PDF ou ZIP não está implementada; a importação de banco é via JSON.
- Questões, respostas e marcações ficam no armazenamento local do navegador/dispositivo. Exporte backups; elas não sincronizam automaticamente entre aparelhos.
- O modo offline deve ser validado após a publicação no endereço HTTPS.


Atualização: adicionada a prova UFPR 2024 ao banco como 90 registros individuais, com filtros e Modo Prova. O enunciado integral e as figuras são consultados no PDF oficial incorporado; alternativas e gabarito foram extraídos do PDF fornecido e devem ser conferidos com o gabarito definitivo.


Atualização: questões UFPR 2024 incluídas individualmente no banco, com enunciados no cartão, alternativas, gabarito e link para a página original. A prova 2025 foi preservada.


ATUALIZAÇÃO 2024
- O banco de 2024 mantém as questões de conhecimentos gerais 1–82 e somente a seção de Inglês 83–90.
- As questões 83–90 foram classificadas como Inglês e receberam alternativas correspondentes à seção inglesa.
- A edição de 2025 foi preservada.
