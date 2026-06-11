+++
title = "happyDomain pour les administrateurs systèmes"
description = "Simplifiez la gestion des zones DNS chez plusieurs hébergeurs. happyDomain offre aux sysadmins une interface unifiée avec historique, rollback et journal d'audit."
layout = "usage"
+++

{{< usage-lead >}}
Une <span class="text-hilight">interface simple</span> pour voir et gérer vos zones, tant internes <span class="text-nowrap">(Bind, ...)</span> que publiques <span class="text-nowrap">(OVH, Gandi, ...)</span>.
{{< /usage-lead >}}

{{< usage-feature
  title="Éditez plus efficacement vos fichiers de zone."
  image="/img/screenshots/domain-abstract.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
>}}
Quel que soit l'hébergeur de vos zones, happy<span class="fw-bold">Domain</span> les affiche de manière claire pour limiter les erreurs.

En installant happy<span class="fw-bold">Domain</span> à côté de votre Bind ou PowerDNS, profitez de l'interface sans changer votre configuration. <span class="text-muted">(bientôt disponible)</span>
{{< /usage-feature >}}

{{< usage-feature
  title="Visualisez les modifications apportées avant de les appliquer."
  image="/img/screenshots/zone-diff.webp"
  alt="Relisiez puis confirmer les modifications qui seront appliquées"
  flip="true"
  bg="green"
>}}
Avant de publier vos changements, happy<span class="fw-bold">Domain</span> vous montre quelles modifications seront faites. Une prévisualisation qui évitera bien des erreurs.

Vous pouvez même sélectionner les changements que vous souhaitez diffuser maintenant et ceux qui doivent attendre.
{{< /usage-feature >}}

{{< usage-feature
  title="Partagez la gestion de la zone avec vos équipes ou vos collaborateurs."
  image="/img/screenshots/domain-abstract.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
  coming_soon="true"
>}}
Que ce soit permanent ou en préparation d'un événement particulier, happy<span class="fw-bold">Domain</span> vous offre la possibilité de collaborer à l'édition d'un même domaine.

Déléguez à vos équipes tout ou partie de la zone, c'est vous qui choisissez.
{{< /usage-feature >}}

{{< usage-feature
  title="Gérez simplement, même les zones spéciales."
  image="/img/screenshots/domains-list.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
  flip="true"
  bg="plum"
  coming_soon="true"
>}}
Vous recherchez une interface qui affiche d'une manière humaine les zones de <span class="font-italic">reverse</span> IPv4/IPv6&nbsp;? ou une zone <a href="https://fr.wikipedia.org/wiki/DNSBL"><span class="font-italic">Real-time Blockhole List</span> (DNSBL)</a>&nbsp;? Ou encore une zone de politique <a href="https://www.dnsrpz.info/">de filtrage des réponses DNS (DNS-RPZ)</a>&nbsp;?

happy<span class="fw-bold">Domain</span> les comprend et vous permet de les gérer sans équivoque.
{{< /usage-feature >}}

{{< usage-feature
  title="Détectez les problèmes avant qu'ils ne deviennent des pannes."
  image="/img/screenshots/checks-dashboard.webp"
  alt="Tableau de bord de supervision affichant l'état de chaque vérification d'un domaine"
>}}
Grâce aux vérificateurs intégrés, happy<span class="fw-bold">Domain</span> surveille vos domaines et vos zones en permanence&nbsp;: expiration de la réservation, validité DNSSEC, cohérence de la délégation, certificats TLS, temps de réponse et bien plus.

Chaque vérification est évaluée selon des règles claires et reportée en <span class="fw-bold">OK</span>, <span class="fw-bold">Avertissement</span> ou <span class="fw-bold">Critique</span>, pour repérer d'un coup d'œil ce qui demande votre attention, et soyez notifié dès qu'une vérification change d'état.
{{< /usage-feature >}}
