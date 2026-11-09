# 🌱 AgroSmart - Agricultura Inteligente (Mobile First PWA)

Aplicativo PWA desenvolvido com arquitetura **Mobile First**, compatível com **Android**, **iOS (iPhone/iPad)** e navegadores Desktop.

---

## 📱 Recursos Mobile & PWA Implementados
- **Mobile First & Ergonomia para Polegar**:
  - Barra de navegação inferior estilo aplicativo nativo com 5 abas (`Campos`, `Clima`, `Inspecionar`, `Solo/Ar`, `Manejo`).
  - Botão de ação rápida flutuante centralizado para registro imediato de inspeções fitossanitárias.
  - Carrossel horizontal de filtros rápidos deslizáveis no topo.
  - Alvos de toque otimizados (mínimo de 44px) com feedback tátil de clique (`press-feedback`).
- **Suporte Total a Android & iOS**:
  - **Notch & Dynamic Island**: Suporte completo a áreas seguras do iPhone (`env(safe-area-inset-top)` e `env(safe-area-inset-bottom)`).
  - **Instalação no Android**: Captura do evento `beforeinstallprompt` com banner flutuante para adicionar à tela inicial.
  - **Instalação no iOS**: Detecção inteligente com modal explicativo do Safari (*"Compartilhar > Adicionar à Tela de Início"*).
  - **Ícones Multi-Plataforma**: Gerados ícones `icon-192.png`, `icon-512.png` (com suporte a maskable) e `apple-touch-icon.png` (180x180 para iOS).
  - **Resposta Háptica**: Vibração tátil nativa (`navigator.vibrate`) ao trocar de aba e concluir tarefas.
  - **Suporte Offline**: Service Worker (`sw.js`) configurado com cache local e banner de aviso quando sem sinal na lavoura.

---

## 🚀 Como subir as atualizações para o GitHub Pages

No terminal ou PowerShell dentro da pasta `C:\Users\Ivis Rocha\OneDrive\Desktop\app-agricultura-inteligente`:

```powershell
git add .
git commit -m "feat: mobile first pwa com suporte ios e android"
git push origin main
```
