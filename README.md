# HeemannLang – Premium Multilingual Language System 🌍

Sistema multilíngue premium com suporte a `BroadcastChannel`, fallback visual e modularização por namespace.

---

## 📦 Instalação

```bash
npm install .
npm run build
```

---

## 🚀 Uso

```tsx
import { LanguageProvider, useLanguageContext } from 'heemlang';

<LanguageProvider>
  <App />
</LanguageProvider>
```

```tsx
const { currentLanguage, changeLanguage } = useLanguageContext();
```

---

## 🔍 Descrição 

HeemannLang é uma solução pensada para aplicações modernas que precisam de suporte multilíngue dinâmico, com fallback seguro, persistência e sincronização entre múltiplas janelas.

Ele se integra facilmente com React + TypeScript, é modular, possui estrutura por namespace e suporta ambientes SSR ou SPA.

Ideal para sistemas globais, enterprise apps ou produtos SaaS com múltiplos idiomas.

---

## 🧠 Autor

**Dr. Heemann Stefanelli**  
🔗 [github.com/DrHeemannStefanelli](https://github.com/DrHeemannStefanelli)

---

## 📄 Licença

MIT © 2025 HeemannLang System
