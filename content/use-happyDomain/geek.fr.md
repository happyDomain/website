+++
title = "happyDomain pour les passionnés"
description = "Prenez le contrôle de vos noms de domaine avec une interface open source puissante. happyDomain rend la gestion DNS accessible et agréable pour les passionnés de tech."
layout = "usage"
+++

{{< usage-lead >}}
Une <span class="text-hilight px-1">interface open source</span> pour <span class="text-hilight px-1">garder son indépendance</span> sur le web.
{{< /usage-lead >}}

{{< usage-points title="Ça vous parle ?" >}}
{{< usage-point icon="house-gear" title="Auto-hébergé, sauf le DNS" >}}
Votre mail, votre cloud, votre git sont sur vos propres serveurs. Mais votre DNS reste enfermé dans une console de registrar fermée que vous ne contrôlez pas.
{{< /usage-point >}}
{{< usage-point icon="exclamation-triangle" title="Une faute de frappe et c'est la catastrophe" >}}
Les fichiers de zone bruts ne pardonnent rien. Un point oublié, un TTL erroné, et votre mail disparaît silencieusement pendant des heures avant que vous ne le remarquiez.
{{< /usage-point >}}
{{< usage-point icon="lock" title="Prisonnier d'un fournisseur" >}}
L'interface de chaque registrar décide de ce que vous pouvez faire et comment. Déplacer vos zones ailleurs, c'est tout réapprendre.
{{< /usage-point >}}
{{< /usage-points >}}

{{< usage-feature
  title="Une interface simple et claire, quel que soit l'hébergeur."
  image="/img/screenshots/domain-abstract.webp"
  url="app.happydomain.org/domains/example.com"
  alt="Une zone affichée de manière claire et lisible"
>}}
Que vos zones soient chez un registrar ou sur vos propres serveurs, happy<span class="fw-bold">Domain</span> les affiche de la même manière claire, pour limiter les erreurs.

Installez happy<span class="fw-bold">Domain</span> à côté de votre Bind ou PowerDNS et profitez de l'interface sans changer votre configuration.
<span class="text-muted">(bientôt disponible)</span>
{{< /usage-feature >}}

{{< usage-feature
  title="L'auto-hébergement facilité, même pour le DNS."
  image="/img/screenshots/providers-list.webp"
  url="app.happydomain.org/providers"
  alt="Liste des fournisseurs pris en charge, des services cloud aux serveurs auto-hébergés"
  flip="true"
  bg="green"
>}}
Avec la même interface, gérez votre zone chez un fournisseur tiers ou faites tourner vos propres serveurs DNS. Vos domaines, vos règles.

N'ayez plus peur d'éditer un fichier texte de zone : on s'en occupe.

happy<span class="fw-bold">Domain</span> est open source, n'a besoin que de très peu de ressources, tourne sans souci sur un Raspberry Pi, et peut même n'être lancé que lorsque c'est nécessaire.
{{< /usage-feature >}}

{{< usage-feature
  title="Bidouillez sans crainte : aperçu, historique, retour arrière."
  image="/img/screenshots/zone-diff.webp"
  url="app.happydomain.org/domains/example.com/diff"
  alt="Vérifiez et confirmez les modifications qui seront appliquées"
>}}
Avant la publication de toute modification, happy<span class="fw-bold">Domain</span> vous montre exactement ce qui va changer et demande confirmation. Fini les fautes de frappe silencieuses.

Et comme chaque version de votre zone est conservée dans l'historique, vous pouvez expérimenter librement et revenir en arrière en un clic si quelque chose tourne mal.
{{< /usage-feature >}}

{{< usage-feature
  title="Répondez à tous vos besoins en toute simplicité."
  image="/img/screenshots/domain-services.webp"
  url="app.happydomain.org/domains/example.com/services"
  alt="Services rattachés à un domaine, décrits en mots simples"
  flip="true"
  bg="plum"
>}}
Un nouveau service ? Une correction urgente ? happy<span class="fw-bold">Domain</span> utilise une terminologie simple, pour rester focalisé sur le résultat attendu.

Nous avons à cœur de mettre à disposition les dernières nouveautés en terme d'enregistrement DNS et de services, pour que votre configuration ne soit jamais en retard sur les standards.
{{< /usage-feature >}}

{{< usage-feature
  title="Gérez simplement, même les zones spéciales."
  image="/img/screenshots/service-caa.webp"
  url="app.happydomain.org/domains/example.com/services"
  alt="Édition d'un service DNS avancé via un formulaire guidé"
  coming_soon="true"
>}}
Vous recherchez une interface qui affiche d'une manière humaine les zones de <span class="font-italic">reverse</span> IPv4/IPv6 ?
Ou une zone <a href="https://fr.wikipedia.org/wiki/DNSBL"><span class="font-italic">Real-time Blackhole List</span> (DNSBL)</a> ? Ou encore une zone de politique <a href="https://www.dnsrpz.info/">de filtrage des réponses DNS (DNS-RPZ)</a> ?

happy<span class="fw-bold">Domain</span> les comprend et vous permet de les gérer sans équivoque.
{{< /usage-feature >}}
