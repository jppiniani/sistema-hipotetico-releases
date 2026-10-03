# Changelog

Todas as mudanças relevantes do projeto estão registradas neste arquivo.
O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/) e o versionamento segue o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [v1.0] - 02/10/2026

### Adicionado
- Página inicial do operador (`pg002.html`) com menu HOME, ATUALIZAÇÕES, RELATÓRIOS e SAIR.
- Página de mensagem de erro (`msg.html`) exibindo "Preencher usuário" e botão VOLTAR.
- Consistência no login (`index.html`):
  - usuário em branco abre a página de erro;
  - usuário `admin` abre a página do administrador;
  - qualquer outro usuário abre a página do operador.

### Corrigido
- Campo SENHA exibia a senha digitada; agora é do tipo `password` e mostra apenas pontos (branch `correcoes`).

## [v0.2] - 02/10/2026

### Adicionado
- Página inicial do administrador (`pg001.html`) com menu HOME, ATUALIZAÇÕES, RELATÓRIOS, CONFIGURAÇÃO, ADMINISTRAÇÃO e SAIR.

### Alterado
- Botão ENTRAR do login passa a abrir a página do administrador, ainda sem validar usuário e senha.

## [v0.1] - 02/10/2026

### Adicionado
- Página de login (`index.html`) com campos USUÁRIO e SENHA e botão ENTRAR.
- Página de aviso "Sistema em construção" (`working.html`), exibida ao clicar em ENTRAR.
- Logotipo do IFSP (`logobra.png`).

### Corrigido
- Acentos apareciam quebrados no navegador (ex.: "HipotÃ©tico"); as páginas agora declaram a codificação UTF-8 (branch `ajustev1`).
