# Minha Meta — GitHub Pages V3

Versão organizada para publicação direta no GitHub Pages.

## Estrutura

- `index.html` — aplicativo completo (React compilado) + tema Premium V3.
- `theme-overrides.css` — camada de tema preto/grafite/dourado usada pelo aplicativo.
- `manifest.json` — configuração básica do PWA.
- `icon.svg` — ícone do aplicativo.

## Como publicar

1. Crie ou abra o repositório no GitHub.
2. Envie estes quatro arquivos para a raiz do repositório.
3. Se já existir um `index.html`, substitua-o por este.
4. Vá em **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch que contém os arquivos (normalmente `main`) e a pasta `/ (root)`.
7. Salve e aguarde o GitHub Pages publicar.

## Observação

O `index.html` é um bundle React já compilado. Esta versão não exige Node.js, npm ou build local para funcionar no GitHub Pages.

O aplicativo continua dependendo dos recursos externos já presentes no bundle, como Google Fonts, quando disponíveis.
