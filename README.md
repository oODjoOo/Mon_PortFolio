# 🌐 Mon Portfolio Moderne

Bienvenue sur mon portfolio personnel, réalisé avec **Astro**, **React** et **Tailwind CSS**. Ce site met en avant mes compétences, mes projets, et mon parcours de développeur web.

## ✨ Fonctionnalités

- 🎨 **Design moderne** – Interface élégante avec un effet *glassmorphism*
- 🌀 **Animations fluides** – Transitions dynamiques grâce à Framer Motion
- 🌗 **Thème sombre/clair** – Adaptation automatique au thème système
- 📱 **Responsive** – Optimisé pour mobile, tablette et bureau
- ⚡ **Performance** – Propulsé par Astro pour une rapidité optimale
- 🧩 **Structure modulaire** – Personnalisation facile et évolutive
- 🔍 **Optimisation SEO** – Contenu structuré pour un meilleur référencement

---

## 🚀 Lancer le projet

### ✅ Prérequis

- [Node.js](https://nodejs.org/) (version 18+ recommandée)
- `npm`, `yarn` ou `bun`

### 🔧 Installation

```bash
git clone https://github.com/jordanricca/Mon_Portfolio.git
cd Mon_Portfolio

# Installation des dépendances
npm install
# ou
yarn install
# ou
bun install

# Démarrage du serveur de développement
npm run dev
# ou
yarn dev
# ou
bun dev
```

Visit `http://localhost:4321` in your browser to see it in action.

## 🧩 Customizing the Portfolio

All your content lives inside `src/lib/data.ts`. Update the following to make it yours:

### 1. Personal Info

```ts
export const personalInfo = {
  name: "Jordan Ricca",
  location: "France",
  email: "ton.email@example.com",
  github: "https://github.com/jordanricca",
  linkedin: "https://www.linkedin.com/in/jordanricca/",
};
```

### 2. Work Experience

```ts
export const workExperience = [ /* ... */ ];
export const education = [ /* ... */ ];
export const skills = { /* ... */ };
export const projects = [ /* ... */ ];
export const awards = [ /* ... */ ];

## 📦 Build for Production

```bash
npm run build
# ou
yarn build
# ou
bun run build
```

To preview the production build locally:

```bash
npm run preview
# ou
yarn preview
```

## 📤 Deployment

Tu peux facilement déployer ce site sur :

Vercel

Netlify

GitHub Pages

ou tout autre hébergeur de site statique

## 📝 License

Projet sous licence MIT. Voir le fichier LICENSE pour plus d’informations.

## ©️ Copyright

Développé avec ❤️ par Jordan Ricca – 2025
Tu peux librement utiliser ce template pour ton propre portfolio. Merci de conserver une mention du créateur original.

---

## 🌟 Like it?

Pense à lui laisser une étoile ⭐ sur GitHub pour le soutenir et aider d'autres développeurs à le découvrir !

---

## 🙏 Acknowledgments

- [Astro](https://astro.build/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Lucide Icons](https://lucide.dev/)
#