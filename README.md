<div align="center">

# ☁️ Spliit Cloud Companion

### Spliit Cloud, directement sur Android

Application Android légère basée sur une **Trusted Web Activity (TWA)** pour utiliser [Spliit Cloud](https://spliit.cloud) comme une application Android.

[Ouvrir Spliit Cloud](https://spliit.cloud) · [Dépôt de Spliit Cloud](https://github.com/antonio-ivanovski/spliit-cloud/)

</div>

---

## À propos

**Spliit Cloud Companion** est une application Android compagnon permettant d'accéder à l'instance de **Spliit Cloud** hébergée sur **https://spliit.cloud**.

Le projet repose sur une **Trusted Web Activity (TWA)** : l'application Android ne réimplémente pas Spliit Cloud. Elle fournit un conteneur Android dédié qui affiche directement l'application web en plein écran.

```text
Android
   │
   ▼
Spliit Cloud Companion
   │
   │ Trusted Web Activity
   ▼
https://spliit.cloud
   │
   ▼
Spliit Cloud
```

## Pourquoi une TWA ?

Cette approche permet de :

- utiliser Spliit Cloud depuis une application Android dédiée ;
- profiter d'une expérience plein écran proche d'une application native ;
- garder l'application web comme source principale de l'expérience utilisateur ;
- bénéficier des évolutions de Spliit Cloud sans réimplémenter son interface côté Android ;
- conserver une application Android légère.

## Spliit Cloud

Le service utilisé par Spliit Cloud Companion est disponible à l'adresse :

**https://spliit.cloud**

Le code source de l'application web Spliit Cloud est disponible ici :

**https://github.com/antonio-ivanovski/spliit-cloud/**

Ce dépôt concerne uniquement **Spliit Cloud Companion et son intégration Android/TWA**. Pour les fonctionnalités, l'interface ou le fonctionnement de l'application web, consultez le dépôt Spliit Cloud ci-dessus.

## Trusted Web Activity

Une **Trusted Web Activity** permet à une application Android d'afficher une application web/PWA en plein écran à l'aide d'un navigateur compatible installé sur l'appareil.

La relation de confiance entre l'application Android et le domaine web repose notamment sur les **Digital Asset Links**.

## Crédits

**Spliit Cloud Companion** est un projet compagnon indépendant destiné à faciliter l'utilisation de Spliit Cloud sur Android.

L'application web **Spliit Cloud** est un projet distinct. Tous les crédits concernant Spliit Cloud, son code source et son développement reviennent à ses auteurs et contributeurs respectifs.

<div align="center">

**Spliit Cloud dans votre poche.**

[🌐 spliit.cloud](https://spliit.cloud) · [💻 Spliit Cloud sur GitHub](https://github.com/antonio-ivanovski/spliit-cloud/)

</div>
