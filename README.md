# 📰 TechNews Today - Portal de Tecnologia

## 📌 Sobre o Projeto

O **TechNews Today** é um portal de notícias sobre tecnologia desenvolvido como atividade prática do curso Técnico em Desenvolvimento de Sistemas.

O projeto apresenta uma página moderna e responsiva, utilizando recursos de **HTML5 e CSS3**, com destaque para efeitos de transparência, gradientes, organização em colunas e interações com os elementos da página.

## 🎯 Objetivo

O objetivo da atividade é aplicar conceitos de **CSS externo**, organização de layouts, responsividade e efeitos visuais em uma página HTML já estruturada.

Durante o desenvolvimento foram utilizados recursos como **CSS Grid**, **Glassmorphism**, **gradientes**, **transições**, **efeitos de hover**, **position sticky** e **Media Queries**.

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- CSS Grid
- Glassmorphism
- Backdrop Filter
- Gradientes
- Media Queries
- GitHub
- Visual Studio Code

## 📂 Estrutura do Projeto

```text
tech_news/
│
├── desafio10a.html
├── 10a_desafio.css
└── README.md
```

## 💻 Funcionamento

O portal possui um cabeçalho com o nome **TechNews Today** e uma frase de apresentação.

A página também apresenta uma notícia em destaque sobre Inteligência Artificial, contendo título, data, texto e a opção **"Leia mais"**.

Na parte principal do portal, o conteúdo é organizado utilizando **CSS Grid**, deixando a seção de vídeo e a seção de newsletter lado a lado.

A seção de vídeo apresenta um conteúdo incorporado por meio de um `iframe`.

A newsletter possui campos para preenchimento do e-mail, seleção da área de interesse, aceite dos termos e botão de inscrição.

Por fim, o rodapé apresenta os direitos autorais e o endereço de contato.

## 🎨 Design e Estilização

O projeto utiliza um visual moderno inspirado no conceito de **Glassmorphism**, utilizando transparências, bordas suaves e efeito de desfoque.

As caixas de conteúdo possuem transparência e `backdrop-filter`, criando o efeito de vidro.

Também foram utilizados gradientes em diferentes elementos da página para destacar o título e o botão de inscrição.

## 🌫️ Glassmorphism

O efeito de **Glassmorphism** foi criado utilizando propriedades como:

```css
background: rgba(255, 255, 255, .1);
backdrop-filter: blur(10px);
border: 1px solid rgba(255, 255, 255, .1);
```

Essas propriedades permitem criar caixas semitransparentes com efeito de desfoque.

## 📐 CSS Grid

O **CSS Grid** foi utilizado para organizar o conteúdo principal da página.

```css
.conteudo {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 30px;
}
```

Dessa forma, o conteúdo consegue ser distribuído em colunas, deixando o vídeo e a newsletter organizados no layout.

## 🖱️ Interações

Foram utilizadas propriedades como `transition`, `transform` e `:hover` para criar interações nos elementos.

Quando o usuário passa o mouse sobre a notícia em destaque, ela apresenta um pequeno movimento para cima.

O botão de inscrição também possui um efeito de aumento quando o cursor passa sobre ele.

## 📱 Responsividade

O projeto possui uma **Media Query** para adaptar o layout em dispositivos menores.

```css
@media (max-width: 767px) {
    .conteudo {
        grid-template-columns: 1fr;
    }
}
```

Em telas menores, as colunas são reorganizadas verticalmente, facilitando a navegação pelo portal em celulares e tablets.

## 📌 Recursos Utilizados

- Header com `position: sticky`
- Efeito Glassmorphism
- `backdrop-filter`
- Gradiente no título
- CSS Grid
- Efeitos `hover`
- Transições
- Formulário de newsletter
- Vídeo incorporado
- Media Query
- Layout responsivo

## 📋 Checklist da Atividade

- [x] Glassmorphism com `backdrop-filter`
- [x] Gradiente no texto
- [x] CSS Grid no layout
- [x] Header com `position: sticky`
- [x] Media Query para celular
- [x] CSS externo
- [x] Interação com `hover`
- [x] Sem frameworks
- [x] Sem JavaScript
- [x] HTML mantido conforme a estrutura fornecida

## 🚀 Como Executar

Para executar o projeto, é necessário ter o **Visual Studio Code** instalado.

Primeiramente, abra a pasta do projeto no Visual Studio Code.

Depois, verifique se os arquivos `desafio10a.html` e `10a_desafio.css` estão na mesma pasta.

Em seguida, abra o arquivo `desafio10a.html` utilizando o **Live Server**.

O portal será aberto automaticamente no navegador.

## 🌐 GitHub

O projeto foi desenvolvido para ser publicado em um repositório público no **GitHub**, conforme solicitado na atividade.

Os arquivos principais do projeto são:

- `desafio10a.html`
- `10a_desafio.css`

## 👩‍💻 Autora
**Lívia Guedes**

Curso Técnico em Desenvolvimento de Sistemas
