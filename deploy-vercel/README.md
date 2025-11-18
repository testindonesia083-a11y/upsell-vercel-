# Como fazer deploy no Vercel

## 📋 Passo a passo

### Método 1: Deploy via Interface do Vercel (Mais Fácil)

1. **Acesse o Vercel**
   - Vá para [vercel.com](https://vercel.com)
   - Faça login ou crie uma conta gratuita

2. **Prepare os arquivos**
   - Você precisa apenas do arquivo `index.html` que está nesta pasta
   - Opcionalmente, inclua o `vercel.json` também

3. **Faça o upload**
   - Clique em "Add New..." → "Project"
   - Arraste a pasta `deploy-vercel` para a área de upload
   - OU suba os arquivos para o GitHub e importe o repositório

4. **Configure (se necessário)**
   - Framework Preset: Deixe como "Other"
   - Root Directory: Deixe como está
   - Build Command: Deixe VAZIO
   - Output Directory: Deixe VAZIO

5. **Deploy!**
   - Clique em "Deploy"
   - Aguarde alguns segundos
   - Pronto! Você receberá uma URL como `seu-projeto.vercel.app`

---

### Método 2: Deploy via CLI (Linha de Comando)

```bash
# 1. Instale o Vercel CLI (apenas uma vez)
npm i -g vercel

# 2. Entre na pasta
cd deploy-vercel

# 3. Faça login no Vercel
vercel login

# 4. Faça o deploy
vercel
```

Siga as instruções na tela e pronto!

---

## ✅ Checklist

- [ ] O arquivo se chama `index.html` (não outro nome)
- [ ] O arquivo está completo (tem `<!DOCTYPE html>`, `<head>`, `<body>`)
- [ ] O script do Cakto está incluído
- [ ] Testou localmente abrindo o arquivo no navegador

---

## 🚨 Problemas comuns

### Erro 404
- **Causa**: Arquivo não se chama `index.html`
- **Solução**: Renomeie para `index.html`

### Botões não funcionam
- **Causa**: Script do Cakto não carregou
- **Solução**: Verifique sua conexão e se o script está no HTML

### Página aparece sem estilo
- **Causa**: CSS não foi carregado
- **Solução**: Use o arquivo `index.html` completo que forneci

---

## 📱 O que está incluído

O arquivo `index.html` contém:
- ✅ Estrutura HTML completa
- ✅ Estilização CSS moderna e responsiva
- ✅ Botões Cakto configurados
- ✅ Design bonito com gradiente
- ✅ Totalmente funcional no mobile

---

## 🎨 Personalizações

Se quiser mudar as cores ou textos:

1. **Mudar o título**: Edite a linha com `<h1>`
2. **Mudar a descrição**: Edite o parágrafo com classe `subtitle`
3. **Mudar cores**: Procure por `#0f7865` e substitua pela cor desejada
4. **Mudar o ícone**: Substitua o emoji `🎁` por outro

---

## 📞 Suporte

Se tiver problemas:
- Documentação Vercel: https://vercel.com/docs
- Comunidade Vercel: https://community.vercel.com

Bom deploy! 🚀
