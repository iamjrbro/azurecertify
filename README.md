# ☁️ AzurePrep — Plataforma de Simulados Azure

## 🚀 Deploy no Render

### 1. Suba o código no GitHub
```bash
git init
git add .
git commit -m "feat: AzurePrep platform"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/azurecertify.git
git push -u origin main
```

### 2. Crie o serviço no Render
1. Acesse [render.com](https://render.com) → **New → Static Site**
2. Conecte o repositório `azurecertify`
3. O Render lê o `render.yaml` automaticamente
4. Clique em **Create Static Site**

O site ficará em: `https://azurecertify.onrender.com`

Todo `git push` na `main` faz deploy automático.

---

## 💻 Rodar localmente
```bash
npm install
npm run dev
```

## 🛠 Stack
React 18 + Vite 5 + Render Static Site
