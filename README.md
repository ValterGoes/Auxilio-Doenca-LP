# Auxílio-Doença — Maragonesa Silveira Advocacia

Landing page institucional focada em auxílio-doença, desenvolvida para captação de leads via WhatsApp e campanhas de tráfego pago.

## Sobre a página

A LP é uma página única com foco em conversão, com seções para:

- Hero com proposta de valor e CTA
- Explicação sobre quem pode ter direito
- Destaque para casos de doença, acidente, pós-cirúrgico e afastamento
- FAQ com dúvidas comuns
- CTA final para WhatsApp e contato direto

## Tecnologias

- HTML5 semântico
- CSS3 puro com variáveis
- JavaScript vanilla para vídeo do YouTube, FAQ e botão flutuante do WhatsApp
- Google Fonts
- Schema.org para SEO
- Google Tag Manager / GA4

## Estrutura do projeto

```bash
.
├── index.html
├── style.css
├── README.md
├── images/
│   ├── favicon.svg
│   ├── favicon.webp
│   ├── logo_azul.webp
│   ├── logo_branco.webp
│   ├── logo-valtergoes.svg
│   └── social-share-.webp
├── fonts/
│   ├── TrajanPro-Bold.otf
│   └── TrajanPro-Regular.otf
└── .gitignore
```

## Como rodar localmente

Abra o arquivo `index.html` diretamente no navegador ou rode um servidor estático:

```bash
cd "/Volumes/Macintosh HD - Dados/MARAGONESA-SILVEIRA-ADV/Auxilio-Doenca-LP"
python3 -m http.server 8000
```

Depois acesse:

```bash
http://localhost:8000/
```

## Checklist antes de subir no Hostinger

- Confirmar o domínio final
- Ajustar o canonical e Open Graph para o domínio definitivo
- Validar se o Google Tag Manager está correto
- Substituir a imagem de compartilhamento caso tenha uma versão final mais adequada
- Fazer upload da pasta inteira para a raiz do site do Hostinger

## Observações

O projeto já está estruturado como site estático e pode ser publicado diretamente no Hostinger sem build ou dependências extras.

## Créditos

Desenvolvido por Valter Goes.
