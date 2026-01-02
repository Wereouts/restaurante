# Restaurante

Este é um projeto de cardápio digital moderno e responsivo, desenvolvido para proporcionar uma experiência de usuário fluida na visualização e escolha de pratos. A aplicação permite que os usuários explorem diversas opções gastronômicas, utilizem filtros por categorias, realizem buscas em tempo real e ordenem os itens conforme suas preferências.

![GitHub top language](https://img.shields.io/github/languages/top/Wereouts/restaurante?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/Wereouts/restaurante?style=for-the-badge)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Wereouts/restaurante?style=for-the-badge)

## 💻 Sobre o Projeto

O projeto foi construído utilizando **React** com **TypeScript**, focando em boas práticas de componentização e tipagem estática. Para a estilização, foram utilizados **CSS Modules** com **SASS**, garantindo um escopo isolado para os estilos e facilidade de manutenção através de variáveis e mixins.

Um detalhe interessante é que toda a identidade visual (logotipo) e as descrições dos pratos foram geradas por Inteligência Artificial (ChatGPT e Looka), demonstrando a integração de tecnologias modernas no processo criativo.

![layout restaurante](https://github.com/Wereouts/restaurante/assets/112819754/97eac1ed-e341-41ad-92eb-3b81fef5b039)

## ✅ Status do Projeto

Status: 🏁 Finalizado

## ✨ Funcionalidades Principais

-   **🔍 Busca em Tempo Real:** Localize pratos instantaneamente digitando o nome no buscador.
-   **📂 Filtragem por Categorias:** Navegue entre Massas, Carnes, Combos e opções Veganas.
-   **↕️ Ordenação Inteligente:** Organize o cardápio por porção (peso), quantidade de pessoas ou preço.
-   **📱 Design Responsivo:** Interface totalmente adaptável para dispositivos móveis, tablets e desktops.
-   **🖼️ Galeria Dinâmica:** Exibição de pratos com fotos, descrições detalhadas, etiquetas de categoria e valores.

## 🛠️ Tecnologias Utilizadas

-   **React** (v17)
-   **TypeScript**
-   **SASS (SCSS)**
-   **CSS Modules**
-   **React Icons** (CgSearch, MdKeyboardArrowUp/Down)
-   **Classnames** (Manipulação condicional de classes CSS)
-   **Normalize.css** (Consistência entre navegadores)

## 📂 Estrutura do Projeto

Abaixo, os destaques da organização do código:

-   `src/pages/Cardapio`: Contém o componente principal e seus subcomponentes (Buscador, Filtros, Itens, Ordenador).
-   `src/styles`: Centraliza variáveis de cores e configurações de breakpoints para responsividade.
-   `src/assets`: Armazena recursos estáticos como o logotipo e imagens do cabeçalho.
-   `public/assets/pratos`: Repositório das imagens dos pratos renderizados dinamicamente.

## 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
-   [Node.js](https://nodejs.org/en/) (Recomendado versão LTS)
-   [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## 🚀 Guia de Início Rápido

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Wereouts/restaurante
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd restaurante
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    ```

4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm start
    ```
    A aplicação abrirá automaticamente no seu navegador no endereço `http://localhost:3000`.

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas!

1.  Faça um **Fork** do projeto.
2.  Crie uma **Branch** para sua feature (`git checkout -b feature/NovaFeature`).
3.  Faça o **Commit** de suas alterações (`git commit -m 'Adicionando uma nova funcionalidade'`).
4.  Faça o **Push** para a Branch (`git push origin feature/NovaFeature`).
5.  Abra um **Pull Request**.

Você também pode reportar bugs ou sugerir melhorias na seção de [Issues](https://github.com/Wereouts/restaurante/issues).

## 👥 Autor

Desenvolvido por **Guilherme Costa Alves**. Se você gostou deste projeto, sinta-se à vontade para entrar em contato ou deixar uma estrela no repositório!
