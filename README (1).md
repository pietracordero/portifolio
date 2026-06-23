# The Pietra Archive — Portfolio

## Estrutura de Arquivos

```
pietra-portfolio/
├── index.html          ← Arquivo principal do site
├── images/
│   ├── pietra1.jpg     ← Foto 1 (selfie perfil)
│   ├── pietra2.jpg     ← Foto 2 (retrato principal)
│   ├── pietra3.jpg     ← Foto 3 (galeria)
│   └── illustration.png ← Imagem gerada pelo Gemini
└── README.md
```

## Como hospedar no GitHub Pages

1. Crie um novo repositório no GitHub (ex: `pietra-portfolio` ou `seuusername.github.io`)
2. Faça upload de **todos** os arquivos mantendo a estrutura de pastas
3. Vá em **Settings → Pages → Source: main branch → / (root)**
4. Aguarde alguns minutos — o site ficará disponível em `https://seuusername.github.io/pietra-portfolio`

## Personalização

- **Adicionar mais fotos na galeria**: adicione imagens em `images/` e edite o HTML na seção `tab-gallery`
- **Alterar texto de boas-vindas**: procure por `Bem-vinda ao meu Arquivo Digital`
- **Cores**: altere as variáveis CSS em `:root` (início do `<style>`)
- **Adicionar links de projetos**: procure por cada `proj-card` e adicione `<a href="...">` nos títulos

## Fontes utilizadas
- Playfair Display (títulos)
- Dancing Script (assinatura/cursiva)
- Space Mono (corpo/monospace)

Todas carregadas via Google Fonts — funciona sem instalação local.
