# Travail individuel: Création d'une page web

L'objectif est de créér et de déployer une **landing page** pour votre entreprise créée au cours _stratégie marketing_.

- Compte comme **Note individuelle du cours**
- Intègre le **projet transversal de création d'entreprise**

## Votre mission

Vous êtes développeur/euse web pour l'entreprise que vous avez créé dans le cours précédent. Vous devez créer une **landing page** de votre produit / service.

Heureusement vous pouvez compter sur vos compétences en HTML / CSS et votre compréhension des frameworks CSS. De plus, votre web designer vous a transmis [un zonning pour votre landing page](https://github.com/brunobuddy/iae-landing-page-project/blob/master/landing.pdf), vous n'avez plus qu'à le développer.

> Ces travaux sont focalisés sur la partie développement web. Le contenu (images et texte) peut être factice.

## Les règles

- Durée: 2h
- Livrable: 1 fichier **index.html** avec la page web et le style intégré
- Livraison sur Github (voir point dédié). Comptez quelques minutes dans votre temps pour déployer.

## Resources

- [Le zonning de la landing page](https://github.com/brunobuddy/iae-landing-page-project/blob/master/landing.pdf)
- [Code Sandbox - Editeur de code en ligne](https://codesandbox.io/)
- [Framework CSS Bulma](https://bulma.io/documentation/overview/start/) ou [autres alternatives pour les plus courageux/euses](https://github.com/troxler/awesome-css-frameworks)
- [Générateur de faux text en latin - Lorem Ipsum](https://www.faux-texte.com/)
- [Pexels - Banque d'images libres de droit](https://www.pexels.com/)
- [Github - Hébergement de code source](https://github.com/)
- [Documentation HTML de MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [Documentation CSS de MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

## Livraison sur Gihub Pages

[Github](https://github.com/) est une plateforme d'hébergement du code source. Leur outil **Github Pages** permet de déployer des sites web sans avoir besoin de configurer des serveurs.

Voici les étapes pour déployer votre projet achevé:

- Créer un compte [Github](https://github.com/) si vous n'en avez pas déjà un
- Créer un nouveau _repository_ et appellez le **landing-page-COMPANY** en remplaçant "COMPANY" par le nom de votre projet de création d'entreprise. L'option **public** doit être cochée
- Cliquez sur le petit lien "create a new file" (il est vraiment petit)
- Dans l'éditeur, nommez votre fichier index.html et collez votre code dedans puis cliquez sur **commit new file**
- Ensuite allez dans **settings** puis **pages**. Dans **branch** selectionnez "master" puis cliquez sur **save**
- Dans quelques secondes vous devriez voir un encart qui dit "your site is live at". Envoyez moi l'adresse de votre site à bruno@buddyweb.fr

![image](https://user-images.githubusercontent.com/6626184/194229789-a98577cd-549b-41b2-bd9b-f4e0043d24f5.png)


## Petits rappels intéressants

Pratiques et toujours bon à savoir.

### Intégrer une librarie dans le HTML

```html
<head>
  <link rel="stylesheet" href="https://y-fake-library.css" />
</head>
```

### Styliser des éléments en CSS

```css
p {
  color: red;
}
```

### Intégrer une balise style dans le HTML

```html
<head>
  <style>
    body {
      background-color: black;
      color: white;
      height: 1000px;
    }
    h1,
    h2 {
      color: white !important;
    }
    #login-button {
      float: right;
    }
  </style>
</head>
```

### Que faire si ça ne marche pas ??? :fearful::fearful:

- Keep calm
- Est-ce que certaines parties de mon code sont soulignées en rouge sur l'éditeur ? Il a peut-être detécté quelque chose à cet endroit si c'est le cas.
- Les balises HTML sont elles bien ouvertes et fermées correctement ? Voir la documentation HTML
- La syntaxe des déclarations CSS est-elle correcte ? Accolades, deux-points, point-virgule
- Google est votre ami, cherchez des exemples similaires
- Si jamais le problème persiste, fonctionnez par élimination: créez un novueau projet et ajoutez les éléments 1 par 1 pour voir où ça coince.
