# Metropolitan by Lindenberg

Site institucional do empreendimento Metropolitan by Lindenberg — alto padrão ao lado do Parque da Cidade (São Paulo).

## Estrutura do projeto

```
lindenberg/
├── index.html              # Página principal
├── css/
│   ├── main.css            # Estilos principais (Tailwind/theme)
│   └── sonner.css          # Estilos do componente de notificações (toast)
├── js/
│   ├── main.js             # Bundle da aplicação
│   ├── analytics.js        # Script de analytics (Tinybird/Flock)
│   └── ...                 # Outros scripts (player, embed etc.)
├── images/                 # Imagens do site
│   ├── hero-building-*.jpg
│   ├── fachada-book-*.jpg
│   └── ...
└── embed/
    └── video.html          # Player de vídeo embutido (iframe)
```

## Como usar

Abra o `index.html` no navegador ou sirva a pasta com um servidor estático (ex.: `python -m http.server 8000` ou `npx serve .`).

## Paleta e identidade

- **Cores:** navy, copper, cream (definidas em `css/main.css` como variáveis CSS)
- **Fontes:** Playfair Display (títulos), Raleway (corpo)
