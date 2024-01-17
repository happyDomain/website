---
title: Dossier de presse happyDomain
toc: yes
---

**happyDomain est une interface libre et open-source qui rend les noms de domaine accessibles en réduisant les points de friction habituels.**\
Notre interface moderne centralise vos domaines et inclut toutes les fonctionnalités que vous attendriez aujourd'hui pour une gestion de domaine sans prise de tête.

Nous avons créé happyDomain parce que nous voulons faire gagner du temps aux équipes opérationnelles, en leur donnant des super-pouvoirs :
avoir un contrôle total sur leurs domaines tant en production qu'en interne, sans avoir à lire et à apprendre tous les nouveaux standards et en restant concentré sur les besoins organisationnels.

Notre mission est d'aider chacun à devenir plus indépendant sur Internet, face aux géants de la technologie, en faisant des noms de domaine l'affaire de tous.
[Consultez notre article de blog à ce sujet.](https://blog.happydomain.org/fr/happydomain-simplifions-l-usage-des-noms-de-domaines/)


## L'origine

En 2018, Pierre-Olivier a donné un cours dans une école d'ingénieurs en informatique sur l'administration système.
Pour une série de travaux pratiques, il a mis en place une console d'hébergeur réduite, incluant notamment la gestion des domaines.

Pendant que les étudiants montrent leur étonnement face à la complexité des domaines, Pierre-Olivier constate que personne à son travail ne veut faire des mises à jour de domaine.
En même temps, [Stéphane Bortzmeyer commente cette complexité](https://www.bortzmeyer.org/hebergement-dns-chaton.html) pour M. et Mme Michu.
Il y avait clairement quelque chose à faire !


## Liste des fonctionnalités

Voici un aperçu des principales fonctionnalités d'happyDomain :

- centraliser la gestion des domaines de plus de 45 fournisseurs de noms de domaine ou serveurs faisant autorité,
- guider les administrateurs avec des formulaires clairs,
- visualiser clairement les changements qui seront propagés,
- conserver l'historique des modifications apportées à la zone,
- revenir à un état antérieur de la zone en un seul clic,
- regrouper les enregistrements par services/besoins : email, délégation, serveur, répartition de charge, etc.
- éliminer toute la complexité technique grâce à une vue logique, plus simple,
- importer/exporter la zone depuis/vers un fichier Bind standard,
- garder une trace des actions pour un audit ultérieur,
- automatiser les tâches via une API REST.


## Détails techniques

happyDomain dispose d'une interface utilisateur ultra-rapide, propulsée par un binaire ou un conteneur léger.

Nous utilisons des technologies de pointe :
- Notre interface est basée sur [SvelteKit](https://kit.svelte.dev/) et s'appuie sur un [Service Worker](https://developer.mozilla.org/docs/Web/API/Service_Worker_API) pour avoir une empreinte réseau réduite : seules les requêtes API sont échangées une fois chargées pour la première fois.
- Le serveur est un programme Golang : même les grandes zones sont traitées en un clin d'œil sur les appareils à faible puissance.
- Pour être déployé dans une infrastructure moderne, nous fournissons une [image Docker basée sur Alpine](https://hub.docker.com/r/happydomain/happydomain/), adaptée à Docker, Podman, Kubernetes, ... et disponible pour les architectures les plus courantes : `amd64`, `arm` et `arm64`.

En ce qui concerne le DNS, nous nous appuyons sur des dépendances robustes, telles que :
- L'incroyable [bibliothèque DNS de miekg](https://github.com/miekg/dns), utilisée, entre autres, par [CoreDNS](https://coredns.io/), au cœur de Kubernetes.
- Les intégrations des fournisseurs sont données par le fantastique [projet dnscontrol](https://dnscontrol.org/) de StackOverflow.

happyDomain est construit pour durer : conçu dès le départ pour tous types de charge, avec la sécurité et l'efficacité à l'esprit.


## Utilisation et applications

Aujourd'hui, nous invitons tous les administrateurs système à rejoindre notre plateforme :
- les employés qui gèrent des domaines internes ou publics,
- les indépendants gérant un large portefeuille de domaines pour leurs clients,
- les agences de communication possédant d'innombrables noms de domaine,
- les geeks à la recherche de nouveaux horizons,
- les personnes soucieuses de la protection de leur vie privée et désireuses de gagner leur indépendance.

Les noms de domaine sont l'affaire de tous.
Nous avons construit une interface simple qui vise à répondre à des besoins concrets, en cachant aux utilisateurs toute la complexité et l'évolution des normes.

Employés et indépendants apprécieront notre sympathique plateforme.
Pensez au temps passé régulièrement sur des questions de DNS, que vous devez traiter avec les interfaces obscures des fournisseurs ou en faisant face à leur manque de fonctionnalités.
De plus, lire et comprendre des documentations ou chercher des tutoriels pour votre configuration exacte peut être fastidieux.

Avec happyDomain, chaque demande organisationnelle ou émanant de client peut être traitée en quelques secondes sans crainte ni doute, même sans avoir à chercher un tutoriel ou une documentation trop technique.


## Comment tester happyDomain ?

Nous sommes un projet libre et open source : vous pouvez utiliser l'interface officielle disponible à [`www.happydomain.org`](https://www.happydomain.org/), ou l'installer chez vous.

Une démonstration est disponible à [`try.happydomain.org`](https://try.happydomain.org/) : vous pouvez évaluer comment happyDomain fonctionne, sans compte ni domaine.

Pour un déploiement facile, nous fournissons [une image Docker](https://hub.docker.com/r/happydomain/happydomain/) : `docker run -e HAPPYDOMAIN_NO_AUTH=1 -p 8081:8081 happydomain/happydomain`

Le code source est disponible sur [Framagit](https://framagit.org/happyDomain/) : vous pouvez le consulter, le copier, donner votre avis, rapporter des bugs ou faire des modifications, comme vous le souhaitez.


## Équipe et communauté

happyDomain est développé par un groupe de personnes basées à Paris, en France.
Parmi elles, [Pierre-Olivier](https://nemunai.re/) dirige les développements et Frédéric fédère l'équipe.

Nous construisons une communauté d'utilisateurs qui veulent reprendre le contrôle de leurs noms de domaine et/ou de leur vie privée.
Vous pouvez nous rejoindre sur [notre canal Matrix](https://matrix.to/#/#happyDNS:matrix.org), ou en savoir plus en suivant [notre blog](https://blog.happydomain.org/) et [notre compte Mastodon](https://floss.social/@happyDomain).


## Ressources médias

Couleur principale : <span style="background: #1cb487; color: #fff; padding: 0.2em 0.5em; font-family: monospace">#1cb487</span>

### Logos

![happyDomain logo black](/img/assets/logo/happyDomain.png)
Logo happyDomain noir

![happyDomain logo white](/img/assets/logo/happyDomain-white.png)
Logo happyDomain blanc

![happyDomain icon](/img/assets/logo/happyDomain-icon.png)
Icône happyDomain

![happyDomain rounded icon](/img/assets/logo/happyDomain-rounded.png)
Icône arrondie happyDomain


### Captures d'écran

![happyDomain home page](/img/screenshots/domains-list.webp)
**Page d'accueil d'happyDomain :**
les domaines sont regroupés, visibles avec leur statut. Les filtres se trouvent à droite.

---

![import a domain in happyDomain](/img/screenshots/domain-import.webp)
**Import d'un domaine depuis un fournisseur :**
il suffit de cliquer sur le bouton pour le synchroniser dans happyDomain.

---

![happyDomain's supported providers](/img/assets/providers.webp)
happyDomain supporte plus de 45 fournisseurs à ce jour, d'autres sont à venir grâce à [dnscontrol](https://dnscontrol.org/).

---

![domain abstraction created by happyDomain](/img/screenshots/domain-abstract.webp)
**Page principale d'un domaine :**
une vue abstraite de la zone, les enregistrements bruts sont regroupés sous les services.

---

![happyDomain expose simple but complete forms](/img/screenshots/service-caa.webp)
**Le formulaire pour éditer les enregistrements CAA :**
chaque service est expliqué en détail, vous êtes guidé à chaque étape.

---

![review the modifications before publishing them](/img/screenshots/zone-diff.webp)
Les modifications ne sont pas directement propagées : vous choisissez quand les appliquer en une seule fois.
**Un diff est présenté avant l'application des modifications, ce qui permet d'éviter les erreurs visibles.**

---

![happyDomain keeps a history](/img/screenshots/domain-history.webp)
**happyDomain garde un historique :** afficher les modifications précédentes, revenir en arrière en un seul clic.

---

![happyDomain logs actions](/img/screenshots/domain-logs.webp)
**happyDomain enregistre les actions effectuées sur le domaine,** permettant des audits futurs.


### Images de présentation

![OpenGraph image](/img/og.webp)


## Nous contacter

N'hésitez pas à nous contacter à l'adresse <presse@happydomain.org> pour toute information ou demande de presse.


## Foire aux questions

##### Vendez-vous des noms de domaine ?

Non, happyDomain ne vend pas encore de domaines.
Pour commencer à utiliser notre interface, vous devez acheter un domaine auprès de l'un de nos [fournisseurs supportés](https://www.happydomain.org/providers/features).


##### Je ne veux plus dépendre de mon hébergeur de nom de domaine. Puis-je héberger mon nom de domaine sur votre infrastructure ?

Nous proposerons une telle fonctionnalité dans un avenir proche, car elle figure dans notre manifeste. Nous avons choisi de nous concentrer d'abord sur la diffusion de l'idée que les noms de domaine sont accessibles à tout le monde grâce à cette interface fonctionnelle, avant de nous concentrer sur la protection de la vie privée, la lutte contre la censure, ...


##### J'ai ma propre infrastructure. Puis-je utiliser happyDomain comme serveur d'autorité secondaire ?

Nous fournirons cette fonctionnalité dans un futur proche, dès que notre infrastructure de serveurs de noms sera prête.
