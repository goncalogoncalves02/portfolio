# Portefólio Pessoal

![Demonstração Desktop](./website-demo-image/desktop.png "Demonstração Desktop")
![Demonstração Mobile](./website-demo-image/mobile.png "Demonstração Mobile")

## Sobre o projeto

Portefólio pessoal estático criado a partir do template "vCard" e personalizado para destacar as competências, experiências e projetos de Gonçalo Gonçalves. O site é totalmente responsivo, funciona apenas com HTML, CSS e JavaScript puros e pode ser servido como uma Single Page Application (SPA) simples.

## Funcionalidades principais

- Barra lateral com informação pessoal e toggle de contactos optimizado para dispositivos móveis.
- Navegação entre secções (About, Resume, Portfolio, Contact) com gestão do estado via JavaScript para manter a experiência de SPA.
- Carrossel horizontal de testemunhos com modal dinâmico que replica conteúdo e imagem do cartão selecionado.
- Filtro de projetos com botões e select personalizado (desktop/mobile) que activa/desactiva itens por categoria.
- Formulário de contacto com validação nativa do browser e bloqueio do botão Submit até todos os campos estarem válidos.
- Layout responsivo com CSS custom properties, breakpoints e optimização para teclado/scroll.

## Estrutura de pastas

```
.
├── index.html              # Página principal com todo o conteúdo da SPA
├── assets
│   ├── css
│   │   └── style.css       # Tema visual, variáveis e media queries
│   ├── js
│   │   └── script.js       # Lógica de navegação, filtros, modal e formulário
│   └── images              # Fotografias, logótipos e imagens de suporte
├── website-demo-image      # Capturas para README e divulgação
├── LICENSE                 # Licença MIT do template original
└── README.md               # Este documento
```

## Tecnologias e recursos

- HTML5 sem dependências de frameworks.
- CSS3 com variáveis, flexbox e animações leves.
- JavaScript ES6+ para interações e controlo de estado.
- Google Fonts (Poppins) para tipografia.
- Ionicons (via CDN) para ícones escaláveis.

## Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/goncalogoncalves02/portfolio.git
   cd portfolio
   ```
2. Opção rápida: abra o ficheiro `index.html` directamente no browser.
3. Opção recomendada para desenvolvimento: sirva a pasta raiz com um servidor estático (qualquer ferramenta funciona). Exemplo com Node.js instalado:
   ```bash
   npx serve .
   ```
4. Abra `http://localhost:3000` (ou a porta indicada) e valide a navegação entre secções e o formulário.

## Personalização

- Substitua textos, contactos e links directamente em `index.html`. As secções estão comentadas para facilitar a edição.
- Actualize imagens em `assets/images/` (respeite nomes ou ajuste os `src` no HTML).
- Ajuste cores, tipografia e espaçamentos em `assets/css/style.css`, onde as variáveis `:root` ajudam a manter consistência.
- Para alterar interações (ex.: categorias de projectos, labels de botões), edite `assets/js/script.js`.
- Revise metadados (`<head>`) para SEO básico: título, descrição, favicon e redes sociais caso necessário.

## Boas práticas sugeridas

- Execute testes de acessibilidade (Lighthouse ou Wave) após alterações para garantir contraste e navegação por teclado.
- Comprima novas imagens antes de adicioná-las para manter o carregamento rápido.
- Use comentários do código apenas quando necessário e mantenha a estrutura semântica (headings em ordem, listas estruturadas).

## Créditos

- Template base: [vCard Personal Portfolio by codewithsadee](https://github.com/codewithsadee/vcard-personal-portfolio).
- Ícones: [Ionicons](https://ionic.io/ionicons).
- Fonte: [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins).

## Licença

Distribuído sob a licença MIT. Consulte `LICENSE` para mais detalhes.

## Contacto

- Email: [goncalo.goncalves.t0113779@edu.atec.pt](mailto:goncalo.goncalves.t0113779@edu.atec.pt)
- Localização: Setúbal, Portugal
