
# 🚀 Nuxt Minimal Starter

Este é um projeto minimalista utilizando **Nuxt.js**, um poderoso framework para Vue.js.  

📖 Consulte a [documentação oficial do Nuxt](https://nuxt.com/docs/getting-started/introduction) para mais detalhes.

---

## 📌 Requisitos  

Antes de começar, certifique-se de ter instalado:  
- **Node.js** (versão recomendada: LTS)  
- **npm** ou **yarn** (para gerenciamento de pacotes)  

---
### Descrição dos Arquivos e Pastas:

- **`assets/`**: Contém arquivos estáticos que são processados pelo Nuxt durante a compilação. Aqui você pode adicionar seus arquivos de estilo (CSS/SCSS), imagens, fontes, etc.
- **`components/`**: Pasta onde você coloca os componentes Vue.js reutilizáveis que são usados dentro de suas páginas.
- **`pages/`**: Contém as páginas principais da aplicação. O Nuxt cria automaticamente rotas com base nos arquivos dentro dessa pasta.
- **`public/`**: Qualquer arquivo que você deseja que seja acessível diretamente via URL, como imagens ou fontes estáticas.
- **`server/`**: Caso você esteja utilizando funcionalidades do servidor no Nuxt (como API endpoints), o código relacionado fica aqui.
- **`.gitignore`**: Arquivo que informa ao Git quais arquivos ou pastas ele deve ignorar (geralmente arquivos de build ou de configuração local).
- **`nuxt.config.ts`**: O arquivo de configuração principal do Nuxt.js, onde você define configurações globais, plugins, middlewares, etc.
- **`package.json`**: Contém as dependências e scripts principais do npm. Esse arquivo é criado automaticamente pelo npm quando você inicializa o projeto.
- **`tsconfig.json`**: Configurações do TypeScript para compilar os arquivos `.ts`.

## 🔧 Instalação  

Clone o repositório e instale as dependências:  

```bash
# Clone o repositório
git clone https://github.com/SamuelEngMek/nuxt-my-website.git

# Acesse a pasta do projeto
cd nuxt-my-website

# Instale as dependências
npm install
```

---

## 💻 Ambiente de Desenvolvimento  

Após a instalação das dependências, você pode iniciar o servidor de desenvolvimento local. O servidor ficará escutando mudanças no código e as refletirá automaticamente no navegador. Para iniciar o servidor, execute o comando:

```bash
npm run dev
```

O servidor será iniciado em **http://localhost:3000/**.

---

## 🚀 Construção e Produção  

Para construir a aplicação para produção e gerar uma versão otimizada do seu projeto, siga os passos abaixo:  

Antes de fazer o deploy da aplicação para um ambiente de produção, é necessário gerar uma versão otimizada do projeto. Isso remove arquivos e dependências não essenciais, além de realizar outras otimizações para melhorar a performance.

Execute o comando abaixo para construir a aplicação para produção:

```bash
npm run build
```

Após gerar o build de produção, você pode visualizá-lo localmente antes de fazer o deploy para o servidor de produção. Para isso, execute o comando abaixo: 

```bash
npm run preview
```

Depois de construir a aplicação e visualizá-la localmente, você pode prosseguir para o deploy no ambiente de produção. Existem diversas opções para isso, dependendo do seu provedor de hospedagem. Por exemplo:

Vercel: Utilize o fluxo de integração contínua (CI) para fazer o deploy diretamente do repositório GitHub, GitLab ou Bitbucket.
Netlify: Similar ao Vercel, você pode conectar seu repositório ao Netlify para automação de deploy.
DigitalOcean, AWS, ou outras nuvens: Você pode configurar o deploy manualmente utilizando serviços de hospedagem de sua escolha.
A vantagem de fazer o deploy em plataformas como Vercel ou Netlify é que elas gerenciam automaticamente o processo de CI/CD para você, permitindo deploys rápidos com mínima configuração.

---

## 📦 Deploy  

Confira a documentação oficial sobre [implantação do Nuxt](https://nuxt.com/docs/getting-started/deployment) para saber como hospedar seu projeto em diversas plataformas.

---

## 📄 Licença  

Este projeto é distribuído sob a licença MIT. Sinta-se à vontade para modificá-lo e utilizá-lo.  

---

✉ **Contato:** Caso tenha dúvidas ou sugestões, entre em contato pelo [LinkedIn](https://www.linkedin.com/in/samuel-miranda-71b545192/) ou contribua diretamente no repositório! 🚀
