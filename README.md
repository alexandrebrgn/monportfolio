# Astro Starter Kit: Portfolio

```sh
npm run dev -- --host
```

![portfolio](https://user-images.githubusercontent.com/357379/210779178-a98f0fb7-6b1a-4068-894c-8e1403e26654.jpg)

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## 📃 Notes perso

public >
    assets >
        images pour ilustrer les pages des projets et image de garde de projet
        backgrounds >
            fond d'écrans


src >
    components >
        composants
        icon >
            composant icône
    content >
        ...
        work >
            la ou se trouvent le code des projets avec le contenu en markdown
            title: titre de la page de garde
            publishDate: date de création du projet servant notemment à trier les projets
            img: chemin de l'image de garde
            img_alt: texte de l'alt de l'image
            link: #
            description: |
            AuthJSReactFirebase est un projet que j'ai réalisé en suivant une formation de 1h30 en ligne afin d'en apprendre plus sur React JS et Firebase
            tags:
            - React JS
            - Firebase
            - Javascript
            - Bootstrap
                layouts >
        ...
    pages >
        la ou se trouvent le code des pages 
        work >
            [...slug].astro -> forme de la page quand on appuie sur un projet
    styles >
