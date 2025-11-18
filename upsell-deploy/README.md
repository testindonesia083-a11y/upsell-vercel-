# 🚀 Como Fazer Deploy no Vercel

## 📦 O que está incluído

Esta pasta contém tudo que você precisa:
- ✅ **index.html** - Página completa com design correto
- ✅ **images/** - Pasta com todas as imagens (Super Kit + testemunhos)

## 🎯 Instruções de Deploy

### Método 1: Via GitHub (Recomendado)

1. **Crie um repositório no GitHub**
   - Acesse [github.com](https://github.com) e faça login
   - Clique em "New repository"
   - Dê um nome (ex: `upsell-pagina`)
   - Clique em "Create repository"

2. **Faça upload dos arquivos**
   - Arraste a pasta `upsell-deploy` inteira para o GitHub
   - OU use o GitHub Desktop
   - OU use linha de comando:
   ```bash
   cd upsell-deploy
   git init
   git add .
   git commit -m "Primeira versão"
   git branch -M main
   git remote add origin SEU-REPOSITORIO-AQUI
   git push -u origin main
   ```

3. **Deploy no Vercel**
   - Acesse [vercel.com](https://vercel.com)
   - Faça login com sua conta GitHub
   - Clique em "Add New..." → "Project"
   - Selecione o repositório que você criou
   - Configure:
     - **Framework Preset**: Other
     - **Root Directory**: Deixe em branco (ou `./` se pedir)
     - **Build Command**: Deixe VAZIO
     - **Output Directory**: Deixe VAZIO
   - Clique em "Deploy"
   - ✅ Pronto! Em poucos segundos seu site estará no ar

---

### Método 2: Upload Direto no Vercel

1. **Acesse** [vercel.com](https://vercel.com)
2. **Faça login**
3. **Clique** em "Add New..." → "Project"
4. **Arraste** toda a pasta `upsell-deploy` para a área de upload
5. **Aguarde** o deploy finalizar
6. ✅ **Pronto!** Você receberá uma URL como `seu-projeto.vercel.app`

---

## ✅ Checklist Antes do Deploy

- [x] Arquivo `index.html` está na raiz da pasta
- [x] Pasta `images/` com todas as 4 imagens está incluída
- [x] Cor de fundo está correta (azul claro)
- [x] Botões Cakto estão configurados
- [x] Todas as imagens estão referenciadas corretamente

---

## 🎨 Cores Utilizadas

- **Fundo da página**: Azul claro suave (hsl(51, 100%, 86%))
- **Cor primária**: Verde/Teal (#0f7865)
- **Banner urgência**: Vermelho (#E30300)
- **Seção testemunhos**: Verde escuro (#0F7865)

---

## 📸 Imagens Incluídas

✅ **super-kit.png** - Imagem principal do produto  
✅ **testemunho1.jpg** - Ana Paula  
✅ **testemunho2.jpg** - Carlos Silva  
✅ **testemunho3.jpg** - Maria Santos  

---

## 🔧 Problemas Comuns

### As imagens não aparecem
**Solução**: Certifique-se de que a pasta `images/` foi enviada junto com o `index.html`

### Erro 404
**Solução**: O arquivo DEVE se chamar `index.html` (não outro nome)

### Cores diferentes
**Solução**: Use o arquivo exatamente como está - as cores já estão corretas

---

## 📞 Suporte

- **Documentação Vercel**: https://vercel.com/docs
- **GitHub**: https://docs.github.com

---

**Boa sorte com o deploy! 🎉**
