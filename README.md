# thiagoantonelli.com.br

Página estática pronta para publicação no GitHub Pages.

## Publicar

1. Crie um repositório público no GitHub chamado `thiagoantonelli-site`.
2. Na pasta deste projeto, execute:

```bash
git init
git add .
git commit -m "Criar pagina Hello World"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/thiagoantonelli-site.git
git push -u origin main
```

3. No repositório, abra **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, `main` e `/ (root)`. O arquivo `CNAME` define `thiagoantonelli.com.br` como domínio personalizado; confirme que ele aparece em **Custom domain**.
4. No DNS do Registro.br, crie registros A para o domínio raiz (`@`) com os quatro IPs informados pela documentação atual do GitHub Pages. Para `www`, crie um CNAME apontando para `SEU_USUARIO.github.io`.
5. Aguarde a verificação do DNS e habilite **Enforce HTTPS** em Settings → Pages.

Antes de trocar o DNS, verifique se já existem registros de site ou e-mail no domínio. Preserve os registros de e-mail (MX, SPF, DKIM e DMARC).
