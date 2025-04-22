# HeemannLang – Premium Multilingual Language System 🌍

Sistema multilíngue premium com suporte a `BroadcastChannel`, fallback visual e modularização por namespace.

## Instalação

```bash
npm install .
npm run build

## Uso

import { LanguageProvider, useLanguageContext } from 'heemlang';

<LanguageProvider>
  <App />
</LanguageProvider>
const { currentLanguage, changeLanguage } = useLanguageContext();

