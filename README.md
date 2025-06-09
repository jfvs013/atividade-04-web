# atividade-04-web

**Nome:** Jacson Francisco Viana Santos

**Descrição:** Esta atividade faz parte da disciplina de Desenvolvimento Web I. O objetivo é aprofundar nos conhecimentos da linguagem HTML.

---

## Resumo do Projeto Yamaha YZF-R15 ABS

Este projeto é um website informativo dedicado à motocicleta Yamaha YZF-R15 ABS, com o objetivo de apresentar suas características, especificações e mídias visuais.

### Estrutura do Projeto:

O website é composto pelas seguintes páginas principais:

* **`index.html` (Página Inicial)**
    * **Propósito:** Apresenta uma visão geral e introdutória da Yamaha YZF-R15 ABS.
    * **Conteúdo:** Inclui descrições sobre a performance da moto (motor, injeção, freios, design, pneus, iluminação LED, custo-benefício), sua tecnologia e inovação (refrigeração líquida, VVA, painel digital, suspensão ajustável, tecnologia DiASil, chassi Deltabox) e sua robustez e esportividade (inspiração em competição, suspensão, chassi, resistência, rodas).
    * **Seções Específicas:** Contém uma seção visual destacando as cores disponíveis da Yamaha YZF-R15 ABS 2025.

* **`fichatecnica.html` (Especificações)**
    * **Propósito:** Detalha as especificações técnicas completas da motocicleta.
    * **Conteúdo:** Organizado em tabelas claras, abrange informações sobre o Motor, Câmbio, Suspensão, Freios e Dimensões da Yamaha YZF-R15 ABS.
    * **Recursos Visuais:** Inclui uma imagem representativa das cores da moto no topo da página.

* **`galeria.html` (Galeria)**
    * **Propósito:** Oferece uma coleção de imagens da Yamaha YZF-R15 ABS.
    * **Conteúdo:** Exibe uma galeria de fotos da motocicleta, permitindo aos usuários visualizarem o design e os detalhes da moto em diferentes ângulos e contextos.

* **`videos.html` (Saiba tudo sobre a R15!)**
    * **Propósito:** Compila vídeos relevantes sobre a Yamaha YZF-R15 ABS.
    * **Conteúdo:** Apresenta vídeos que abordam reviews, testes, dicas de manutenção e modificações da motocicleta, fornecendo uma perspectiva dinâmica e prática.

* **`saibamais.html` (Saiba Mais)**
    * **Propósito:** Serve como um ponto de redirecionamento para informações oficiais.
    * **Conteúdo:** Contém um link direto para a página oficial da Yamaha YZF-R15 ABS no site da Yamaha Brasil, oferecendo uma fonte confiável e atualizada de detalhes e especificações.

### Recursos e Design:

* **Navegação Fixa:** Um menu de navegação fixo (`.faixa2`) no topo da página permite fácil acesso a todas as seções do site.
* **Design Responsivo:** A meta tag `viewport` e o CSS garantem que o site se adapte a diferentes tamanhos de tela (desktop, tablet, celular), proporcionando uma boa experiência de usuário em qualquer dispositivo.
* **CSS Centralizado:** Todos os estilos são gerenciados em um único arquivo `style.css` para consistência visual.

---

## Recursos e Aspectos Técnicos Utilizados na Criação do Site

Este projeto foi desenvolvido utilizando as linguagens de marcação e estilização web fundamentais: HTML5 para a estrutura do conteúdo e CSS3 para o design e apresentação visual.

### 1. Estrutura e Semântica HTML5:

O HTML5 foi utilizado para construir a base do site, focando em uma estrutura semântica e acessível.

#### Tags Estruturais Principais:

* `<!DOCTYPE html>`: Declara o tipo de documento como HTML5.
* `<html>`: Elemento raiz de todas as páginas, com atributo `lang="pt-br"` para indicar o idioma do conteúdo.
* `<head>`: Contém metadados da página.
    * `<meta charset="UTF-8">`: Define a codificação de caracteres para UTF-8, garantindo a exibição correta de caracteres especiais.
    * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: **Essencial para responsividade**, informa ao navegador como controlar as dimensões da viewport, garantindo que o site se adapte a diferentes tamanhos de tela.
    * `<title>`: Define o título da página exibido na aba do navegador.
    * `<link rel="stylesheet" href="style.css">`: Vincula o arquivo CSS externo para estilização.
* `<body>`: Contém todo o conteúdo visível da página.

#### Tags de Conteúdo e Agrupamento:

* `<div>`: Amplamente utilizado para agrupar e organizar seções do conteúdo, como `faixa`, `faixa2`, `container-pagina-inicial`, `container-ficha-tecnica`, `container-videos`, `container-galeria`, `secao-especificacao`, `secao-videos`, `galeria-flex`, `videos-grid`, `video-item`, `video-embed`, `galeria-item`.
* `<h1>`, `<h2>`, `<h3>`: Usadas para títulos e subtítulos, seguindo uma hierarquia de importância para o conteúdo. Embora alguns `h2` e `h3` pudessem ser `h1` em páginas específicas para melhor semântica (conforme discutido), a hierarquia interna das seções está presente.
* `<p>`: Para parágrafos de texto.
* `<ul>`, `<li>`: Utilizadas para listas não ordenadas, notavelmente para o menu de navegação (`.faixa2`) e para listar características da moto em `index.html`.
* `<a>`: Para links de navegação entre páginas e para redirecionamento externo (como para o site da Yamaha), com atributos `href` para o destino, `target="_blank"` para abrir em nova aba e `rel="noopener noreferrer"` para segurança em links externos.
* `<img>`: Para incorporar imagens no layout, com o atributo `src` para o caminho da imagem e `alt` para texto alternativo (importante para acessibilidade).
* `<table>`, `<tr>`, `<td>`: Utilizadas para estruturar dados tabulares na página `fichatecnica.html` (Especificações).
* `<iframe>`: Para incorporar vídeos externos (do YouTube, por exemplo) na página `videos.html`, com atributos como `src` para o link do vídeo, `frameborder`, `allow` e `allowfullscreen`.

### 2. Estilização CSS3:

O CSS3 é o pilar do design visual do site, garantindo uma apresentação coesa e responsiva.

#### Arquivo Único:

Todo o estilo é gerenciado a partir do arquivo `style.css`.

#### Seletores Utilizados:

* **Seletores de Tipo:** `html`, `body`, `p`, `h3`, `img`, `ul`, `li`, `a`, `table`, `tr`, `td`, `iframe`.
* **Seletores de Classe:** Amplamente utilizados para aplicar estilos específicos a elementos com classes como `faixa`, `faixa2`, `centralizar`, `container-ficha-tecnica`, `container-pagina-inicial`, `secao-com-imagens`, `secao-especificacao`, `specs-table`, `ficha-tecnica-img`, `galeria-flex`, `container-galeria`, `intro-galeria`, `galeria-fotos`, `galeria-item`, `galeria-autor`, `container-videos`, `intro-videos`, `secao-videos`, `videos-grid`, `video-item`, `video-embed`, `video-titulo`, `video-autor`, `botao-saiba-mais`.
* **Seletores de Pseudoclasse:** `:hover` para efeitos interativos ao passar o mouse sobre links e itens de galeria.
* **Seletores Combinadores:** `faixa2 ul`, `faixa2 ul li`, `faixa2 ul li a`, `specs-table tr`, `specs-table td`, `specs-table tr:last-child`, `specs-table td:first-child`, `specs-table td:last-child`.

#### Propriedades CSS Principais:

* **Layout e Posicionamento:** `display` (com `block`, `flex`, `inline-block`), `margin`, `padding`, `width`, `height`, `max-width`, `min-width`, `position` (`fixed`, `relative`), `top`, `left`, `z-index` (para camadas de elementos como as barras de navegação), `overflow` (`hidden`).
* **Tipografia:** `font-size`, `color`, `font-weight`, `text-align`, `text-decoration`, `line-height`.
* **Caixas e Bordas:** `background-color`, `border`, `border-bottom`, `border-radius`, `box-shadow`.
* **Modelos de Caixa:** `box-sizing` (implícito como `content-box`, mas importante para responsividade).
* **Flexbox:** Utilizado extensivamente para criar layouts responsivos e alinhamento de itens, como em `.faixa`, `.faixa2`, `.faixa2 ul`, `.galeria-flex`, `.videos-grid`. Propriedades como `justify-content`, `align-items`, `gap`, `flex` foram cruciais.
* **Transições:** `transition` para animações suaves ao interagir com elementos (`:hover`).
* **Transformações:** `transform` (`translateY`) para efeitos de movimento em hover.
* **Responsividade Específica para Vídeos:** `padding-bottom: 56.25%;` dentro de `.video-embed` para manter a proporção 16:9 dos vídeos incorporados.
* **Outros:** `list-style` (para remover marcadores de lista), `scroll-padding-top` (para rolagem suave abaixo do cabeçalho fixo).
