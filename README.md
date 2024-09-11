
# Kinghost Landing Page

Este projeto é uma landing page criada como parte do curso **Codeboost**. O foco principal foi o uso de **Sass** para estruturar e organizar o CSS, sem a utilização de **JavaScript**. A página possui um design moderno e responsivo, utilizando boas práticas de estilização e modularidade.

## ✨  Visualize o projeto online:

* Acesse a página publicada pelo Github Pages: [https://allndouglas.github.io/kinghost-landing-page/]

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura da página.
- **Sass**: Pré-processador CSS utilizado para modularidade e otimização dos estilos.
- **CSS3**: Estilização visual da página, com arquivos minificados para melhor performance.

## 📂 Estrutura do Projeto

```
kinghost-landing-page/
│
├── css/
│   ├── main.min.css
│   └── main.min.css.map
│
├── img/
│   └── (imagens utilizadas no projeto)
│
├── scss/
│   ├── _grid.scss
│   ├── _header.scss
│   ├── _home.scss
│   ├── _mixins.scss
│   ├── _reset.scss
│   ├── _variables.scss
│   └── main.scss
│
├── index.html
└── README.md
```

- **css/**: Contém os arquivos CSS minificados gerados pelo compilador Sass.
- **img/**: Diretório onde estão armazenadas as imagens utilizadas no projeto.
- **scss/**: Contém os arquivos Sass organizados em componentes e módulos para facilitar a manutenção e escalabilidade do código.
- **index.html**: Arquivo principal da landing page.
- **README.md**: Documentação do projeto.

## 🔥 Funcionalidades

- Layout totalmente responsivo, adaptado para diferentes resoluções de tela.
- Estrutura de estilos organizada em arquivos Sass modulares:
  - `_grid.scss`: Responsável pelo layout de grids.
  - `_header.scss`: Estilos para a seção de cabeçalho.
  - `_home.scss`: Estilos do corpo da pagina.
  - `_mixins.scss`: Conjunto de mixins reutilizáveis.
  - `_reset.scss`: Reset padrão de estilos.
  - `_variables.scss`: Variáveis globais usadas no projeto (cores, tamanhos, etc).
  - `main.scss`: Arquivo Sass principal que importa todos os arquivos parciais.

## 🛠️ Ferramentas Utilizadas

- **Sass Compiler (VSCode)**: Foi utilizado a extensão **Sass Compiler** no VSCode para compilar os arquivos `.scss` em `.css`, gerando o arquivo minificado (`main.min.css`) para otimizar o desempenho.

## 📚 Pré-requisitos

- Instalar o **Sass Compiler** no **VSCode** ou utilizar outra ferramenta para compilar os arquivos **Sass**.

## 🚀 Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/AllnDouglas/kinghost-landing-page.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd kinghost-landing-page
   ```
3. Compile os arquivos `.scss` para `.css` (se necessário):
   ```bash
   sass scss/main.scss css/main.min.css --style compressed
   ```
4. Abra o arquivo `index.html` no navegador para visualizar a página.

## 📷 Preview Desktop e Mobile

### Desktop
![Landing Page](https://github.com/AllnDouglas/kinghost-landing-page/blob/main/Kinghost-desktop.png)

### Mobile
![Landing Page](https://github.com/AllnDouglas/kinghost-landing-page/blob/main/kinghost%20-%20responsivo.png)


## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usar e modificar conforme necessário.
