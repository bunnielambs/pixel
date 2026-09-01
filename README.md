# PIXEL — Landing Page

Site estático de página única (`index.html`, sem build), hospedado no GitHub Pages.

## Contato (no `index.html`)

- WhatsApp: +55 (64) 98139-0813 → `https://wa.me/5564981390813`
- E-mail: contatopixelagency@gmail.com
- Instagram: [@pixelagency.jpg](https://instagram.com/pixelagency.jpg)

## Publicar / atualizar no GitHub Pages

Deploy automático: qualquer `git push` para a branch `main` atualiza o site.

```bash
git add -A
git commit -m "..."
git push
```

Configuração inicial do Pages (uma vez): repositório → **Settings › Pages** →
*Source*: **Deploy from a branch** → branch `main`, pasta `/ (root)` → **Save**.

### Domínio próprio (opcional)

Criar arquivo `CNAME` na raiz com o domínio, commitar, e apontar o DNS conforme a
documentação do GitHub Pages.
