# curso-react-webpack

Projeto de estudos do **módulo gratuito do curso [React Ninja](https://www.udemy.com/course/curso-reactjs-ninja/)**, focado na configuração manual do Webpack para desenvolvimento de aplicações com React.js.

> ⚠️ Este módulo utiliza o **Webpack na versão 1**. O curso completo aborda a migração para versões mais recentes e configurações avançadas.

## 🎯 O que é abordado neste módulo

- Configuração do Webpack do zero para projetos React
- Webpack Dev Server — servidor local para servir os arquivos
- Hot Reload — atualização automática no browser durante o desenvolvimento
- Boas práticas de configuração de ambiente para React.js

## 🛠️ Tecnologias utilizadas

- [Node.js](https://nodejs.org/)
- [React.js](https://react.dev/)
- [Webpack 1.x](https://webpack.github.io/)
- [Webpack Dev Server 1.x](https://github.com/webpack/webpack-dev-server)

## 📋 Pré-requisitos

- Conhecimento básico de JavaScript
- Node.js instalado (versão LTS recomendada)
- npm

## 🚀 Instalação e execução

```bash
# Clone o repositório
git clone https://github.com/danielfalcaodf/curso-react-webpack.git
cd curso-react-webpack

# Instale as dependências
npm install

# Gere o bundle
npx webpack

# Ou inicie o servidor de desenvolvimento
npx webpack-dev-server
```

Com o `webpack-dev-server`, a aplicação fica disponível em `http://localhost:8080` e o bundle é servido em `http://localhost:8080/static/bundle.js`.

## 📁 Estrutura do projeto

```
curso-react-webpack/
├── src/
│   ├── index.js        # Ponto de entrada da aplicação
│   └── app.js          # Módulo com lógica separada (ex: função sum)
├── dist/               # Saída do bundle (gerado pelo Webpack, ignorado no git)
├── index.html          # Página HTML que carrega o bundle
├── webpack.config.js   # Configuração do Webpack
└── package.json
```

## 📚 O que foi aprendido

- Como configurar o Webpack manualmente para projetos React
- Conceitos de `entry`, `output` e geração de bundle
- **Configuração do `publicPath`** para servir o bundle em um caminho virtual (`static/`)
- **Uso do Webpack Dev Server** para servir a aplicação localmente sem gerar arquivos em disco
- **Modularização de aplicação** — separar responsabilidades em módulos com `module.exports` e `require`
- Diferença entre configuração manual e ferramentas prontas (CRA, Vite)

## 🔗 Referências

- [React Ninja — Curso completo](https://www.udemy.com/course/curso-reactjs-ninja/)
- [Documentação do Webpack](https://webpack.js.org/)

## 📝 Licença

Este projeto é apenas para fins de estudo e não possui licença formal.
