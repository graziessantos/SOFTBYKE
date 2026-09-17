<h1><a href="https://ana-juliaps.github.io/SOFTBYKE/">🚴 SOFTBYKE </a></h1>
https://ana-juliaps.github.io/SOFTBYKE/
<br><br>
Site fictício de e-commerce especializado em bicicletas, peças e acessórios para ciclismo, desenvolvido como <b>projeto acadêmico</b> para a disciplina de <b>Desenvolvimento Web</b> do curso de <b>Ciência da Computação</b>.

O projeto simula uma loja virtual completa, com página inicial, catálogo de produtos, páginas de produto dinâmicas, institucional, galeria e uma área de documentação técnica.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estruturação das páginas (`homepage.html`, `catalogo.html`, `empresa.html`, `galeria.html`, `documento.html` e o template `paginas-produtos/produto.html`).
- **CSS3** — estilização visual, com um arquivo de estilos dedicado por página/seção (`style.css`, `homepage.css`, `catalogo.css`, `produto.css`, `estilo_empresa.css`, `documentos.css`).
- **JavaScript (Vanilla JS)** — interatividade da interface e montagem dinâmica das páginas de produto (`js/script.js`, `js/produto.js`).
- **JSON** — `produtos.json` funciona como uma base de dados local com as informações de todos os produtos (nome, categoria, preço, imagem, descrição, especificações etc.), consumida via `fetch()`.
- **Figma** — utilizado na etapa de prototipação (wireframes), incorporado na página de Documentos via iframe.

Nenhum framework ou biblioteca externa foi utilizado — todo o front-end é escrito em HTML, CSS e JavaScript puros.

## 📁 Estrutura do projeto

```
SOFTBYKE-main/
├── homepage.html            # Página inicial (destaques, parceiros, mais vendidos)
├── catalogo.html            # Catálogo completo de produtos
├── empresa.html             # Página institucional (sobre a empresa)
├── galeria.html             # Galeria de imagens
├── documento.html           # Documentação técnica do projeto (wireframes, links)
├── produtos.json            # Base de dados dos produtos
├── css/                     # Folhas de estilo
├── js/                      # Scripts JavaScript
├── img/                     # Imagens do site (produtos, banners, logos, parceiros)
├── documentos/              # Arquivos de apoio (ex: briefing do projeto)
└── paginas-produtos/
    └── produto.html         # Template único de página de produto (dados carregados via ?id=)
```

## ▶️ Como executar

Como o site utiliza `fetch()` para carregar o `produtos.json`, ele precisa ser servido por um servidor local (abrir os arquivos `.html` direto no navegador, via `file://`, bloqueia essa requisição). Algumas opções simples:

- Usar a extensão **Live Server** do VS Code; ou
- Rodar `python3 -m http.server` na pasta do projeto e acessar `http://localhost:8000/homepage.html`.

## 👥 Integrantes

- Grazielle
- Beatriz
- Lara
- Ana Júlia

**Curso:** Ciência da Computação
**Disciplina:** Desenvolvimento Web
**Turma:** A
