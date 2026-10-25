# Pecuária Neonatal Inteligente

Site informativo responsivo baseado no PDF **“Sistema de diagnóstico precoce por inteligência artificial em bezerros”**.

## Arquivos
- `index.html` — estrutura e conteúdo do site
- `styles.css` — visual e responsividade
- `script.js` — menu para celular e ano automático

## Publicar no GitHub Pages
1. Extraia o ZIP.
2. Envie os três arquivos (`index.html`, `styles.css`, `script.js`) para a raiz do repositório.
3. No GitHub, abra **Settings → Pages** e configure a publicação a partir da branch desejada e da pasta `/ (root)`.
4. Abra o endereço publicado e atualize com `Ctrl + F5` se aparecer uma versão antiga.

## Adicionar imagens depois
As áreas pontilhadas são espaços reservados. Para usar uma foto:
1. Coloque a imagem no repositório, por exemplo em `images/bezerros.jpg`.
2. Em `index.html`, substitua o bloco `<div class="image-placeholder ...">...</div>` pela imagem, por exemplo:
   `<img class="hero-photo" src="./images/bezerros.jpg" alt="Bezerros no alojamento neonatal">`
3. Para os espaços de imagem em cards, mantenha a classe `card-image` na imagem para preservar o layout.

## Paleta de cores
- `#F2B263` — laranja claro
- `#BF8F65` — caramelo
- `#F2CDAC` — creme pêssego
- `#8C634A` — marrom
- `#59220E` — marrom escuro

O site inclui uma seção ampliada sobre o Índice de Bem-Estar Neonatal Bovino (IBEN), com definição, fluxo de funcionamento, tabela de indicadores, benefícios e nota técnica. As informações de painel e tabelas estão identificadas como exemplos ilustrativos; não são dados reais de uma fazenda. O site preserva a ressalva do documento de que o IBEN é uma proposta de indicador e não substitui avaliação veterinária.
