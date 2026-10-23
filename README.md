# Auxílio-Doença — Maragonesa Silveira Advocacia

Landing page institucional focada em auxílio-doença (auxílio por incapacidade temporária — benefício do INSS), desenvolvida para captação de leads via Google Ads e WhatsApp para o escritório Maragonesa Silveira Advocacia & Consultoria.

Baseada na landing page de auxílio-acidente do mesmo escritório, reaproveitando a estrutura, o design e a integração com WhatsApp — com conteúdo, FAQ e dados estruturados adaptados para o tema de auxílio-doença.

## Sobre a página

Página única (one-page), dividida em seções pensadas para conversão:

- **Hero** — proposta de valor direta, com vídeo explicativo e CTA para WhatsApp.
- **Sobre / Como funciona** — quais situações geram direito (doença comum, ocupacional, acidente, pós-cirúrgico), quem pode solicitar e a conexão com o Direito do Trabalho (estabilidade em casos acidentários, FGTS).
- **Perguntas Frequentes** — dúvidas comuns sobre o benefício, em formato de acordeão.
- **CTA final** — reforço de confiança e botão de contato direto pelo WhatsApp.

Inclui também um botão flutuante de WhatsApp (aparece a partir da segunda seção) e rastreamento de conversão para campanhas de Google Ads.

## Tecnologias

- HTML5 semântico
- CSS3 puro (sem framework), com variáveis CSS para cores, espaçamentos e tipografia — mesmo `style.css` base da LP de auxílio-acidente
- JavaScript vanilla (sem dependências) para:
  - incorporação do vídeo do YouTube sob demanda (clique para carregar)
  - acordeão da seção de FAQ
  - exibição do botão flutuante de WhatsApp via IntersectionObserver
- Google Fonts — Montserrat (títulos) e Roboto (texto)
- Schema.org (JSON-LD) — dados estruturados de LegalService e FAQPage para SEO e rich snippets
- Google Tag Manager / GA4 — rastreamento de conversão nos cliques de WhatsApp

## Estrutura do projeto

```
.
├── index.html
├── style.css
└── images/
    ├── favicon.ico
    ├── logo_azul.png
    ├── logo_branco.png
    ├── logo-valtergoes.svg
    └── video-capa-auxilio-doenca.jpg
```

## Como rodar localmente

Não há build nem dependências — é só abrir o `index.html` no navegador, ou servir a pasta com qualquer servidor estático:

```bash
npx serve .
```

## Configuração antes de publicar

- Adicionar as imagens na pasta `images/` (os arquivos de logo podem ser copiados direto da LP de auxílio-acidente; falta apenas a imagem de capa do vídeo)
- Definir e inserir o **ID do vídeo explicativo** sobre auxílio-doença no atributo `data-youtube-id` (está vazio no momento)
- URL final do domínio (usada no canonical, Open Graph e dados estruturados) — atualmente `auxiliodoenca.maragonesa.adv.br` como placeholder
- Endereço completo do escritório (nos dados estruturados), se for incluído
- Imagem de compartilhamento (og:image, 1200×630px)
- Conferir o ID de conversão do Google Ads/GTM, caso seja necessário um container separado para esta campanha

## Créditos

Desenvolvido por Valter Goes.
>>>>>>> 414b730 (docs: documentar estrutura e configuração da landing page)
