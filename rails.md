En cours de rédaction, le problème étant de connaitre le public visé (quelqu'un déjà à l'aise avec le concept de MVC ou quelqu'un qui a découvert Ruby récemment)

- Introduction
    - qu'est ce que rails
    - L'origine de rails
    - pourquoi rails plutôt que le reste
    - ils utilisent rails : Basecamp, Github, Dribble, 500px, Airbnb, Indiegogo...

## La base

- Installation de rails et découverte de la structure
- Les migrations
- Les models, découverte des fonctions en mode interactif `rails c`
- Les routes
- Les controllers
- Les vues

## Approfondissons

- L'asset manager

### Les models

- validations
- scope
- callbacks
- relations

### Les controllers

- params params.require.permit
- before action, after action...

### Les vues

- les helpers (urls helpers)
- Le form helper (découverte de la gem simple_form peut être ?)

## TP : Petsy, le réseaux social pour animaux

- (à voir si on découpe ou on tente d'y aller comme un boeuf)

## Notions avancées

- Debug avec ou sans console interactive
- Cache
- Internationalisation
- Tests ?
- ActionCable
- ActionMailer
- Création API (c'est pas un peu pousser la formation trop loin?)
- Déploiement d'une application rails (peut être placer ça sur la formation serveur, à voir...)
- La création de script de déploiement sur Capistrano ou outil similaire (peut être placer ça sur la formation Capistrano)

## Les gems incontournables

- devise, devise-i18n, omniauth
- simple_form
- carrierwave (upload de media)
- factory_girl_rails (fixtures)
- rspec-rails (tests)
- kaminari (pagination)
- slim-rails
