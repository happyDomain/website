+++
title = "happyDomain pour les administrateurs systèmes"
description = "Simplifiez la gestion des zones DNS chez plusieurs hébergeurs. happyDomain offre aux sysadmins une interface unifiée avec historique, rollback et journal d'audit."
layout = "usage"
+++

{{< usage-lead >}}
Une <span class="text-hilight px-1">interface unique</span> pour voir et gérer vos zones, tant internes <span class="text-nowrap">(Bind, ...)</span> que publiques <span class="text-nowrap">(OVH, Gandi, ...)</span>.
{{< /usage-lead >}}

{{< usage-points title="Ça vous parle ?" >}}
{{< usage-point icon="terminal" title="Deux mondes, deux méthodes" >}}
SSH et un éditeur de texte pour les zones internes, une console web différente pour chaque hébergeur public. Les mêmes enregistrements, des outils complètement différents.
{{< /usage-point >}}
{{< usage-point icon="arrow-counterclockwise" title="Aucun retour arrière" >}}
Un mauvais enregistrement se propage en quelques secondes. Pour le récupérer, il faut fouiller dans les sauvegardes ou dans votre mémoire, pendant que le service est en panne.
{{< /usage-point >}}
{{< usage-point icon="inboxes" title="Tout retombe sur vous" >}}
Vous êtes la seule personne de confiance pour toucher au DNS, alors chaque demande d'enregistrement devient un ticket dans votre file.
{{< /usage-point >}}
{{< /usage-points >}}

{{< usage-feature
  title="Éditez toutes vos zones au même endroit, internes et publiques."
  image="/img/screenshots/domain-abstract.webp"
  alt="Une zone affichée de la même manière claire, quel que soit l'hébergeur"
>}}
Quel que soit l'hébergeur de vos zones, happy<span class="fw-bold">Domain</span> les affiche de la même manière claire, pour limiter les erreurs.

Installez happy<span class="fw-bold">Domain</span> à côté de votre Bind ou PowerDNS et profitez de l'interface sans changer votre configuration. <span class="text-muted">(bientôt disponible)</span>
{{< /usage-feature >}}

{{< usage-feature
  title="Visualisez vos modifications avant de les appliquer."
  image="/img/screenshots/zone-diff.webp"
  alt="Relisez puis confirmez les modifications qui seront appliquées"
  flip="true"
  bg="green"
>}}
Avant de publier, happy<span class="fw-bold">Domain</span> vous montre exactement ce qui va changer. Une prévisualisation qui évite bien des erreurs, sur des zones où les erreurs coûtent cher.

Vous pouvez même sélectionner les changements qui partent maintenant et ceux qui doivent attendre.
{{< /usage-feature >}}

{{< usage-feature
  title="Historique complet, retour arrière instantané."
  image="/img/screenshots/domain-history.webp"
  alt="Historique de chaque version d'une zone"
>}}
Chaque version de chaque zone est conservée, avec qui a changé quoi et quand.

Quand quelque chose casse, vous ne reconstruisez pas l'état précédent à partir des sauvegardes : vous y ramenez la zone en un clic, puis vous enquêtez calmement.
{{< /usage-feature >}}

{{< usage-feature
  title="Détectez les problèmes avant qu'ils ne deviennent des pannes."
  image="/img/screenshots/checks-dashboard.webp"
  alt="Tableau de bord de supervision affichant l'état de chaque vérification d'un domaine"
  flip="true"
  bg="plum"
>}}
Grâce aux vérificateurs intégrés, happy<span class="fw-bold">Domain</span> surveille vos domaines et vos zones en permanence : expiration de la réservation, validité DNSSEC, cohérence de la délégation, certificats TLS, temps de réponse et bien plus.

Chaque vérification est évaluée selon des règles claires et reportée en <span class="fw-bold">OK</span>, <span class="fw-bold">Avertissement</span> ou <span class="fw-bold">Critique</span>, pour repérer d'un coup d'œil ce qui demande votre attention, et soyez notifié dès qu'une vérification change d'état.
{{< /usage-feature >}}

{{< usage-feature
  title="Partagez la gestion de la zone avec vos équipes."
  image="/img/screenshots/domain-abstract-records.webp"
  alt="Gestion de zone partagée entre les équipes"
  coming_soon="true"
>}}
Que ce soit permanent ou en préparation d'un événement particulier, happy<span class="fw-bold">Domain</span> permet à plusieurs personnes de collaborer sur une même zone.

Déléguez tout ou seulement une partie d'une zone, jusqu'à un seul enregistrement. Les demandes de routine quittent votre file ; le contrôle reste chez vous.
{{< /usage-feature >}}

{{< usage-feature
  title="Gérez simplement, même les zones spéciales."
  image="/img/screenshots/service-caa.webp"
  alt="Édition d'un service DNS avancé via un formulaire guidé"
  flip="true"
  bg="green"
  coming_soon="true"
>}}
Vous recherchez une interface qui affiche d'une manière humaine les zones de <span class="font-italic">reverse</span> IPv4/IPv6 ?
Ou une zone <a href="https://fr.wikipedia.org/wiki/DNSBL"><span class="font-italic">Real-time Blackhole List</span> (DNSBL)</a> ? Ou encore une zone de politique <a href="https://www.dnsrpz.info/">de filtrage des réponses DNS (DNS-RPZ)</a> ?

happy<span class="fw-bold">Domain</span> les comprend et vous permet de les gérer sans équivoque.
{{< /usage-feature >}}
