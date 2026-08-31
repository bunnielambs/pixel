# PIXEL — Landing Page

Site estático de página única (`index.html`, sem build). Pronto para GitHub Pages.

## Antes de publicar: preencher contato

Procure os marcadores no `index.html` e substitua todos:

| Marcador       | O que colocar                                              |
| -------------- | --------------------------------------------------------- |
| `[WHATSAPP]`   | número internacional só com dígitos, ex.: `5511999999999` |
| `[EMAIL]`      | e-mail de contato                                          |
| `[TELEFONE]`   | telefone (usado em `tel:` e como texto)                    |
| `[INSTAGRAM]`  | URL completa do perfil (ou remover a linha)                |
| `[LINKEDIN]`   | URL completa (ou remover a linha)                          |

Aparecem na seção `#contato` e no rodapé. Enquanto houver `[` `]` no arquivo, ainda falta preencher.

## Publicar no GitHub Pages

1. Criar o repositório no GitHub (ex.: `site-pixel`).
2. No diretório do projeto:
   ```bash
   git remote add origin https://github.com/<usuario>/<repo>.git
   git push -u origin main
   ```
3. GitHub → repositório → **Settings › Pages** → *Source*: **Deploy from a branch** → branch `main`, pasta `/ (root)` → **Save**.
4. Em ~1 min o site fica em `https://<usuario>.github.io/<repo>/`.

### Domínio próprio (opcional)

Criar arquivo `CNAME` na raiz com o domínio (ex.: `pixel.studio`), commitar, e apontar o DNS
(registro `A`/`ALIAS`) conforme a doc do GitHub Pages.
