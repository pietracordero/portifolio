# Pietra Cordero — Portfolio

Site pessoal de portfólio com estética scrapbook digital, animações scroll-triggered e identidade visual vintage-contemporânea.

---

## 🚀 Como hospedar no GitHub Pages (passo a passo)

### 1. Crie o repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique no **+** no canto superior direito → **New repository**
3. Nomeie o repositório como: `pietra-cordero-portfolio` (ou qualquer nome que preferir)
4. Deixe como **Public** (obrigatório para GitHub Pages gratuito)
5. **NÃO** marque "Add a README file" (vamos fazer o upload dos arquivos)
6. Clique em **Create repository**

---

### 2. Prepare os arquivos localmente

Sua pasta do projeto deve conter:
```
pietra-portfolio/
├── index.html        ← arquivo principal
├── pietra1.jpeg      ← suas fotos
├── pietra2.jpeg
├── pietra3.jpeg
└── README.md
```

> ⚠️ **Importante:** As fotos devem estar na mesma pasta que o `index.html` e com exatamente esses nomes: `pietra1.jpeg`, `pietra2.jpeg`, `pietra3.jpeg`

---

### 3. Faça o upload dos arquivos

**Opção A — Pelo site do GitHub (mais fácil):**

1. Após criar o repositório, clique em **"uploading an existing file"** no centro da página
2. Arraste TODOS os arquivos da pasta `pietra-portfolio/` para a área de upload
3. No campo "Commit changes", escreva: `🎨 Portfolio inicial`
4. Clique em **Commit changes**

**Opção B — Via terminal (para quem usa Git):**

```bash
# Na pasta do projeto:
git init
git add .
git commit -m "🎨 Portfolio inicial"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/pietra-cordero-portfolio.git
git push -u origin main
```

---

### 4. Ative o GitHub Pages

1. No repositório, clique em **Settings** (engrenagem no topo)
2. No menu lateral esquerdo, clique em **Pages**
3. Em **Source**, selecione:
   - Branch: **main**
   - Folder: **/ (root)**
4. Clique em **Save**
5. Aguarde 1–2 minutos

✅ Seu site estará disponível em:
```
https://SEU_USUARIO.github.io/pietra-cordero-portfolio/
```

---

### 5. (Opcional) Domínio personalizado

Se quiser usar um domínio próprio como `pietracordero.com`:

1. Compre o domínio em Namecheap, GoDaddy, Registro.br, etc.
2. Em **Settings → Pages → Custom domain**, adicione seu domínio
3. Configure os DNS do seu domínio apontando para o GitHub (eles mostram as instruções)

---

## 🔄 Como atualizar o site no futuro

**Pelo site do GitHub:**
1. Vá até o arquivo que quer editar no repositório
2. Clique no ícone de lápis ✏️ (Edit this file)
3. Faça as alterações e clique em **Commit changes**
4. O site atualiza automaticamente em ~1 minuto

**Via terminal:**
```bash
git add .
git commit -m "📝 Atualização: descreva o que mudou"
git push
```

---

## 📁 Estrutura do projeto

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Site completo — HTML, CSS e JS em um único arquivo |
| `pietra1.jpeg` | Foto para o Photo Booth (cena 4) |
| `pietra2.jpeg` | Foto para o Photo Booth (cena 4) |
| `pietra3.jpeg` | Foto para o Photo Booth (cena 4) |

---

## 🎨 Identidade Visual

| Token | Valor | Uso |
|-------|-------|-----|
| Vanilla Cream | `#F5EFE3` | Fundo principal |
| Midnight Indigo | `#1C2340` | Envelope, headers, DVD cases |
| Bordeaux Velvet | `#7B1C2E` | Acento primário, botões, assinatura |
| Aged Paper | `#EDE3CF` | Fundos secundários |
| Silver Accent | `#C0B8A8` | Detalhes, renda |

| Fonte | Uso |
|-------|-----|
| Cormorant Garamond | Body text, texto da carta |
| Playfair Display | Títulos de seção |
| Dancing Script | Títulos principais, assinatura |
| Courier Prime | Labels, monospace, typewriter |

---

## 📞 Contato

- **Email:** pietracordero10@gmail.com
- **LinkedIn:** [pietra-cordero-b88337253](https://linkedin.com/in/pietra-cordero-b88337253)
- **Instagram:** [@pietra.cordero](https://instagram.com/pietra.cordero)
