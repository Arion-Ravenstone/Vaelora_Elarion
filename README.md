# 🌍 Vaelora-Elarion Master RPG & Author Platform

Welcome to the complete codebase and AI-driven RPG system for **Vaelora-Elarion**, the mythic world of Arion Ravenstone.

## ✨ Features

- 🌌 Arion AI: Mood-aware Dungeon Master, lore engine, trauma tracker
- 📚 Dynamic Lore Packs 01–10 (markdown + Firestore JSON)
- 🧝 Character Creator + Stat System + Inventory + Leveling
- 🎲 Dice Roller + Real-time Rolls + Initiative Tracker
- 🛠️ Admin Console (campaigns, items, skills, GM tools)
- 🧠 Pantheon with divine domains and Firestore injection
- ☕ Midnight Brew (Real + Fantasy Recipes + AI Commentary)
- 🗺️ Interactive World Map + Glossary + Timeline + Lore Wiki
- 📜 Author Hub: Books, Blog, About, Newsletter, Events, Media Kit
- 🔐 Firebase Auth + Firestore + Security Rules

## 🧪 Tech Stack

- React + Tailwind CSS + Firebase Hosting, Auth, Firestore
- Arion AI (LLM/LLM-ready + memory system)
- Markdown-based lore formatting system
- GitHub CI/CD deployable
- Modular AI enhancement folders in `/ai/`

## 🚀 Getting Started

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`

## 🔐 Firebase Setup

1. Create a Firebase project at https://console.firebase.google.com
2. Enable Firestore + Authentication (Email/Password)
3. Paste your config into `/src/firebaseConfig.ts`
4. Deploy using:

```bash
firebase login
firebase init
firebase deploy
```

## 📁 Key Folders

- `/ai/phase01–10`: Expandable AI logic (memory, mood, quest, trauma, etc.)
- `/docs/`: Developer guides + roadmap + world building
- `/rpg/`: Core character sheet, skills, classes, and bestiary
- `/midnight-brew/`: Midnight Brew core files
- `/admin/`: Admin panel interfaces and CMS logic

## 👥 Admin + Test Accounts

See `config/test_accounts_vaelora.json`

## 📜 Licensing

All creative works © Jonathan C. Murphy, 2025. This system may not be redistributed without permission.
