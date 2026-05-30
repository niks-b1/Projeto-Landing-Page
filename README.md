# Atividade Prática: Desenvolvimento de Landing Page (Clone da Prisma Treinamentos)

**Objetivo:** Recriar a estrutura e o design da landing page da [Prisma Treinamentos](https://www.prismatreinamentos.com/) aplicando boas práticas de HTML5, CSS3 (incluindo responsividade) e JavaScript (caso necessário para interações).

**O que será avaliado:**

* Semântica do HTML.
* Fidelidade do design (cores, tipografia e espaçamentos).
* Responsividade (o site deve funcionar bem em celulares e computadores).
* Organização do código e versionamento (opcional, ex: GitHub).

---

## Guia de Passo a Passo para os Alunos

### Passo 1: Análise e Planejamento (A "Engenharia Reversa")

Antes de digitar qualquer linha de código, você precisa entender a estrutura do site que vai buildar.

1. **Acesse o site de referência** e navegue por ele.
2. **Identifique as seções principais:** Observe como a página é dividida. Geralmente temos:
* Cabeçalho (`<header>`) com a logo e menu de navegação.
* Seção Principal/Hero (`<section>`) com a promessa principal, imagem de fundo e botões de chamada para ação (CTA).
* Seção de Serviços/Cursos apresentando o que a empresa faz.
* Seção "Sobre" ou diferenciais da empresa.
* Depoimentos ou marcas parceiras.
* Rodapé (`<footer>`) com informações de contato, redes sociais e direitos autorais.


3. **Mapeamento de Cores e Fontes:** Use a ferramenta de inspeção do navegador (F12) para descobrir a paleta de cores (hexadecimais) e as fontes utilizadas.

---

### Passo 2: Preparação do Ambiente e Coleta de Assets

1. Crie uma pasta para o seu projeto e configure os arquivos básicos: `index.html`, `style.css` e uma pasta `/assets` (ou `/img`) para as imagens.
2. **Imagens e Logos:** Baixe as imagens necessárias do site de referência. *Dica:* Você pode clicar com o botão direito nas imagens e "Salvar como", ou buscá-las na aba "Sources/Fontes" do inspetor do navegador. Se alguma imagem for difícil de extrair, você pode usar uma imagem similar temporária (placeholders).
3. **Configuração de Fontes:** Se o site usar fontes do Google Fonts, pegue o link de importação e coloque no seu HTML ou CSS.

---

### Passo 3: Estruturação com HTML Semântico

Agora, construa o "esqueleto" do site. Foque apenas no conteúdo e na estrutura, sem se preocupar com a beleza nesta etapa.

1. Monte a estrutura básica do HTML5 (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
2. Crie as tags estruturais com base na análise do Passo 1 (`<header>`, `<main>`, `<section>`, `<footer>`).
3. Adicione os textos, títulos (`<h1>` a `<h6>`), parágrafos (`<p>`), links (`<a>`) e imagens (`<img>`).
4. **Dica de Ouro:** Adicione classes (`class=""`) descritivas em seus elementos (ex: `.header-navigation`, `.hero-button`, `.course-card`) para facilitar a estilização no próximo passo.

---

### Passo 4: Estilização Base e Layout (CSS)

Com a estrutura pronta, é hora de dar vida ao site.

1. **Reset CSS:** Comece aplicando um reset básico (zerar `margin`, `padding` e definir `box-sizing: border-box`) para que o site renderize igual em todos os navegadores.
2. **Estilos Globais:** Defina a cor de fundo padrão da página, a fonte principal (`font-family`) e as cores dos textos.
3. **Layout das Seções:** Use **Flexbox** ou **CSS Grid** para alinhar os elementos.
* *Exemplo:* O menu do cabeçalho geralmente usa Flexbox com `justify-content: space-between`. Os cards de cursos podem usar CSS Grid ou Flexbox com `flex-wrap`.


4. Adicione os espaçamentos internos (`padding`) e externos (`margin`) para que o site respire, baseando-se no site original.

---

### Passo 5: Responsividade (Mobile-First ou Desktop-First)

Um site moderno precisa se adaptar a telas de celulares e tablets.

1. Use **Media Queries** (`@media`) para ajustar o layout quando a tela diminuir.
2. **Pontos de atenção:**
* O menu de navegação horizontal do topo deve sumir ou virar um "menu hambúrguer" em telas menores.
* Seções que tinham 3 ou 4 colunas de conteúdo (lado a lado) no computador devem empilhar verticalmente (1 coluna) no celular.
* Ajuste o tamanho das fontes e imagens para que não quebrem a tela e eliminem a barra de rolagem horizontal.



---

### Passo 6: Interatividade ( JavaScript)

Se o site original tiver elementos dinâmicos, você pode implementá-los aqui:

1. **Menu Hambúrguer:** Adicione um script simples para abrir e fechar o menu no celular ao clicar no ícone.
2. **Animações ao rolar a página (Scroll):** Efeitos suaves quando o usuário desce a página.
3. **Carrossel/Slider:** Caso a seção de depoimentos ou cursos utilize um banner rotativo.

---

### Passo 7: Revisão e Entrega

1. **Diferentes Navegadores:** Teste o seu site no Chrome, Firefox e Edge para garantir que está tudo certo.
2. **Validação:** Verifique se não há links quebrados ou imagens que não carregam.
3. **Publicação (Opcional):** Suba o código para o GitHub e faça o deploy em plataformas gratuitas como GitHub Pages, Vercel ou Netlify para gerar um link visualizável.

---


* **Foco no aprendizado:** Lembre-os de que não precisa ficar 100% idêntico nos mínimos pixels, mas a estrutura, a disposição dos elementos e a experiência do usuário devem ser muito próximas.
