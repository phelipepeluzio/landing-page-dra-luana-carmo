# Site — Dra. Luana Costa do Carmo

Site institucional pronto para publicar. Estático (HTML/CSS/JS puro), sem necessidade de build, servidor ou banco de dados.

## O que tem nesta pasta

- `index.html` — a página inteira (todas as seções).
- `assets/` — fotos, logo e o vídeo de depoimento, já otimizados para carregar rápido (pasta original tinha ~28 MB de imagens, aqui ficou com ~3 MB).
- `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` — ícones do site (aba do navegador, atalho no celular).
- `robots.txt` — libera a indexação do site pelo Google.

## Como publicar de graça (passo a passo)

### Opção recomendada: Cloudflare Pages
1. Acesse https://dash.cloudflare.com/ e crie uma conta gratuita (ou entre na existente).
2. Vá em **Workers & Pages** → **Create** → aba **Pages** → **Upload assets**.
3. Arraste esta pasta inteira (ou um .zip dela) na área de upload.
4. Dê um nome ao projeto (ex: `dra-luana-carmo`) e clique em **Deploy**.
5. Em minutos o site estará no ar em um endereço tipo `dra-luana-carmo.pages.dev`.
6. Para usar um domínio próprio (ex: `dracarmo.com.br`), vá em **Custom domains** dentro do projeto e siga as instruções — o certificado SSL é grátis e automático.

### Alternativa: Netlify
1. Acesse https://app.netlify.com/ e crie uma conta gratuita.
2. Na tela inicial, arraste esta pasta para a área "Deploy manually" (drag and drop).
3. O Netlify publica o site na hora, com um link tipo `nome-aleatorio.netlify.app` (dá para renomear depois em **Site settings**).
4. Domínio próprio: **Domain settings** → **Add a domain**.

### Alternativa: GitHub Pages
1. Crie um repositório novo no GitHub e suba o conteúdo desta pasta para ele.
2. Em **Settings** → **Pages**, escolha a branch `main` e a pasta raiz (`/`).
3. O site fica disponível em `seu-usuario.github.io/nome-do-repositorio`.

## Antes de publicar, vale revisar

- O telefone do WhatsApp está fixo em `5521990919434` — se mudar, procure por `PHONE` dentro do `index.html` (perto do fim do arquivo) e troque nesse único lugar.
- O endereço do consultório e o mapa (seção "Local") estão com o texto "Em breve, fotos do nosso consultório" — quando tiver fotos do local, é só substituir esse trecho e trocar a imagem.
- O formulário de contato abre o WhatsApp com os dados preenchidos (não envia e-mail nem salva em banco de dados) — é a forma mais simples e sem custo de operar.

## Domínio próprio

O domínio (ex: `www.dracarmo.com.br`) é registrado separadamente, em um site como Registro.br (domínios .com.br) por cerca de R$ 40/ano. A hospedagem (Cloudflare Pages, Netlify etc.) continua grátis — você só paga pelo nome do domínio.
