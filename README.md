# Boilerplate para Projetos Simples

Neste boilerplate, utilizamos ferramentas leves e eficientes para desenvolvimento de projetos simples, como:

- **ReactJS**
- **Vite**
- **TailwindCSS**

### Utilizando BiomeJS como Linter

Além disso, estou testando o uso do **BiomeJS** como linter de código. Para configurá-lo corretamente no VSCode, siga os passos abaixo:

1. Instale a extensão "Biome" no VSCode, procurando por "Biome" nas extensões.

2. Você tem duas opções:
   - Formatar manualmente: Clique com o botão direito no arquivo e selecione _"Formatar documento com"_, escolhendo o Biome.
   - Configurar para formatar automaticamente ao salvar. Para isso, adicione o seguinte código ao seu `settings.json`:

   ```json
   "[typescript]": {
       "editor.defaultFormatter": "biomejs.biome",
       "editor.formatOnSave": true,
       "editor.codeActionsOnSave": {
           "quickfix.biome": true
       }
   }

### Ferramentas Necessárias
Para rodar o projeto, certifique-se de ter instaladas as seguintes ferramentas:

- [VSCode](https://code.visualstudio.com/)
- [NodeJS](https://nodejs.org/en)
- NPM(Vem integrado com NodeJS) ou [Yarn](https://yarnpkg.com/getting-started/install)
