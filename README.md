# 🏗️ Base React - CSS-in-JS Boilerplate

![Status](https://img.shields.io/badge/Status-Template-blue)
![React](https://img.shields.io/badge/Framework-React-61DAFB?logo=react&logoColor=black)
![Styled Components](https://img.shields.io/badge/Lib-Styled_Components-DB7093?logo=styled-components&logoColor=white)
![Vite](https://img.shields.io/badge/Build_Tool-Vite-646CFF?logo=vite&logoColor=white)

> Uma estrutura de projeto limpa e pré-configurada, desenhada para iniciar rapidamente o desenvolvimento de interfaces utilizando a metodologia CSS-in-JS.

## 🎯 Motivação e Propósito

Configurar um ambiente React do zero repetidamente consome tempo valioso. O propósito deste repositório é servir como um **Scaffold (Andaime)** para exercícios e projetos futuros.

Ele resolve o problema da "fadiga de configuração" (setup fatigue), entregando um ambiente onde o **Styled Components** já está instalado e integrado, e os arquivos desnecessários de um *create-react-app* padrão já foram removidos, permitindo que o desenvolvedor foque puramente na arquitetura de estilos e lógica de componentes.

## 🛠️ Tecnologias Utilizadas

A stack é minimalista, contendo apenas o essencial para a estilização moderna:

* **[ReactJS](https://react.dev/):** Biblioteca base para a construção da UI.
* **[Styled Components](https://styled-components.com/):** Biblioteca instalada e configurada para permitir escrita de CSS dentro de arquivos JS/TS.
* **[Vite](https://vitejs.dev/):** Ferramenta de build utilizada para garantir um servidor de desenvolvimento ultra-rápido (HMR).
* **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Linguagem padrão do projeto.

## ✨ Funcionalidades

Como um projeto base, suas funcionalidades são estruturais:

1.  **Dependências Pré-instaladas:** O `package.json` já inclui `styled-components`, eliminando a necessidade de instalação manual.
2.  **Limpeza de Código:** Remoção de arquivos de CSS globais desnecessários e logos padrão que vêm na instalação default do React.
3.  **Estrutura Pronta:** Pastas organizadas para receber novos componentes e estilos.

## 📂 Estrutura de Arquivos

A organização é simplificada para facilitar a expansão:

```text
base_exercicio_css_in_js/
├── src/
│   ├── components/      # Diretório reservado para componentes isolados
│   ├── App.jsx          # Componente Raiz limpo
│   ├── main.jsx         # Ponto de entrada da aplicação
│   └── index.css        # (Opcional) Reset básico ou CSS global mínimo
├── public/              # Assets estáticos
├── index.html           # HTML base
├── package.json         # Lista de dependências e scripts
└── vite.config.js       # Configuração do bundler
```
