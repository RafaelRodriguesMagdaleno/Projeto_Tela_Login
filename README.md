# Projeto Tela de Login

Página web responsiva que apresenta uma **tela de login**, com um cartão centralizado que reúne uma imagem ilustrativa e um formulário de acesso com campos de e-mail e senha.

O site foi desenvolvido como atividade prática das aulas do professor **Gustavo Guanabara no Estudonauta**, com foco na criação de formulários em HTML5 e na adaptação do layout a diferentes tamanhos de tela por meio de media queries.

## Acesse o projeto

A página está disponível no GitHub Pages:

[Visualizar o Projeto Tela de Login](https://rafaelrodriguesmagdaleno.github.io/Projeto_Tela_Login/)

## Sobre o projeto

A página exibe um cartão de login com título, mensagem de boas-vindas, campos de e-mail e senha, o botão "Entrar" e o link "Esqueci a Senha". Os campos utilizam a validação nativa do navegador e o preenchimento automático.

O projeto é apenas front-end: o formulário aponta para `login.php` e o link para `esqueci.html`, mas esses arquivos não fazem parte do repositório, portanto não há autenticação real.

## Tecnologias utilizadas

- **HTML5** para a estrutura semântica da página e do formulário;
- **CSS3** para cores, espaçamentos, posicionamento e responsividade;
- **Google Material Symbols** para os ícones dos campos de login e senha;
- **GitHub Pages** para hospedagem do site.

## Estrutura do projeto

```text
Projeto_Tela_Login/
├── index.html
├── estilos/
│   ├── style.css
│   └── media_query.css
├── imagens/
│   └── imagem_tela_login.jpg
└── LICENSE
```

### Principais arquivos

- `index.html`: contém a estrutura da página e o formulário de login;
- `estilos/style.css`: define o layout base, pensado para telas pequenas, além das cores e dos espaçamentos;
- `estilos/media_query.css`: ajusta o layout para tablets e desktops;
- `imagens/`: armazena a imagem exibida no cartão de login;
- `LICENSE`: define os termos de licença do projeto.

## Responsividade

O layout segue a abordagem *mobile first*: o `style.css` define a versão para celular e o `media_query.css` sobrescreve apenas o necessário para telas maiores.

- **Celular (até 767px):** cartão estreito, com a imagem no topo e o formulário logo abaixo, sobre um fundo lilás;
- **Tablet (768px a 992px):** cartão ocupando 80% da largura da tela, com a imagem à esquerda e o formulário à direita;
- **Desktop (a partir de 992px):** cartão com 950px de largura, dividido ao meio, com o formulário à esquerda e a imagem à direita.

No tablet e no desktop, o fundo da página passa a utilizar um gradiente entre lilás (`#5f2c82`) e verde (`#49a09d`), as duas cores principais do projeto.

## Como executar localmente

O projeto não possui dependências ou etapa de compilação. Para visualizar a página localmente, clone o repositório ou baixe os arquivos e abra o `index.html` em um navegador.

### Clonando o repositório

```bash
git clone https://github.com/RafaelRodriguesMagdaleno/Projeto_Tela_Login.git
cd Projeto_Tela_Login
```

Em seguida, abra o arquivo `index.html` no navegador.

Durante o desenvolvimento, também é possível utilizar a extensão **Live Server** no Visual Studio Code para atualizar a página automaticamente.

## Conceitos praticados

Este projeto exercita conceitos importantes de desenvolvimento web, entre eles:

- Criação de formulários com `form`, `input` e `label`;
- Uso dos tipos de campo `email` e `password`;
- Validação nativa com o atributo `required`;
- Preenchimento automático com o atributo `autocomplete`;
- Criação de media queries com `min-width` e `max-width`;
- Desenvolvimento *mobile first*;
- Centralização de elementos com `position` e `transform`;
- Uso de `background-size: cover` para adaptar a imagem ao espaço disponível;
- Aplicação de gradientes com `linear-gradient`;
- Publicação de páginas estáticas usando GitHub Pages.

## Créditos

Projeto criado por [Rafael Rodrigues](https://github.com/RafaelRodriguesMagdaleno) como parte das aulas do professor Gustavo Guanabara no [Estudonauta](https://www.estudonauta.com/).

O projeto foi desenvolvido para fins educacionais.
