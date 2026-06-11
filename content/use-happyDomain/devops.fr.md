+++
title = "happyDomain pour les DevOps"
description = "Automatisez la gestion DNS avec l'API REST de happyDomain. Intégrez les opérations de domaines dans vos pipelines CI/CD et workflows d'infrastructure."
layout = "usage"
+++

{{< usage-lead >}}
Une <span class="text-hilight px-1">API REST et une interface web</span> pour automatiser la gestion des domaines <span class="text-hilight px-1">dans le cloud, chez des fournisseurs et sur site</span>.
{{< /usage-lead >}}

{{< usage-points title="Ça vous parle ?" >}}
{{< usage-point icon="mouse" title="Le ClickOps ne passe pas à l'échelle" >}}
Tout dans votre stack est du code, sauf le DNS. Les enregistrements sont encore modifiés à la main dans la console d'un fournisseur : impossible à scripter, à relire ou à reproduire.
{{< /usage-point >}}
{{< usage-point icon="plug" title="Une API par hébergeur" >}}
Chaque hébergeur a sa propre API, sa propre authentification, ses propres particularités. Votre automatisation devient un amas de scripts fragiles qui casse à chaque fois qu'un client change de fournisseur.
{{< /usage-point >}}
{{< usage-point icon="git" title="Le DNS contourne votre pipeline" >}}
Les déploiements sont relus, testés et réversibles. Les changements DNS partent directement en production, sans rien de tout cela.
{{< /usage-point >}}
{{< /usage-points >}}

{{< usage-feature
  title="Une seule API REST pour toutes les opérations sur vos domaines."
  image="/img/screenshots/features/rest.png"
  alt="Notre API REST, commentée et exposée avec Swagger"
>}}
Tout ce qui se fait dans l'interface web d'happy<span class="fw-bold">Domain</span> peut se faire avec l'API, dans votre langage de prédilection. Scriptez-le une fois, exécutez-le partout.

Notre API REST est entièrement documentée et grâce à Swagger, vous pouvez la parcourir et générer un client dans tous les langages supportés.

<a href="/swagger/index.html" target="_blank">Voir la documentation de l'API et l'essayer maintenant !</a>
{{< /usage-feature >}}

{{< usage-feature
  title="Oubliez les particularités de chaque hébergeur. Une seule abstraction pour plus de 25 hébergeurs."
  image="/img/screenshots/domain-abstract.webp"
  alt="Une zone affichée de la même façon, quel que soit le fournisseur derrière"
  flip="true"
  bg="green"
>}}
Écrivez votre automatisation pour happy<span class="fw-bold">Domain</span> une seule fois ; il dialogue avec chaque fournisseur à votre place :

<ul class="text-left">
  <li class="mb-1"><strong>services de cloud :</strong> Route53, Azure DNS, Google Cloud DNS, DigitalOcean, Linode, Oracle Cloud, ...</li>
  <li class="mb-1"><strong>CDN :</strong> Akamai Edge DNS, Cloudflare, ...</li>
  <li class="mb-1"><strong>bureaux d'enregistrement :</strong> OVH, Gandi, Namecheap, Vultr, ...</li>
  <li class="mb-1"><strong>vos serveurs locaux :</strong> BIND, PowerDNS, knot, ...</li>
</ul>

<a href="https://docs.dnscontrol.org/service-providers/providers" target="_blank">Voir la liste des hébergeurs DNS supportés.</a>
{{< /usage-feature >}}

{{< usage-feature
  title="Intégrez le DNS dans votre workflow de relecture."
  image="/img/screenshots/zone-diff.webp"
  alt="Relisez et confirmez les changements qui seront appliqués"
>}}
Avant toute publication, happy<span class="fw-bold">Domain</span> affiche le diff exact entre la zone actuelle et la nouvelle, et attend votre confirmation.

Vous pouvez même choisir quels changements partent maintenant et lesquels attendent. Ça fonctionne comme une pull request, pour votre DNS.
{{< /usage-feature >}}

{{< usage-feature
  title="Des outils qui s'intègrent à ce que vous utilisez déjà."
  image="/img/screenshots/sdk-python.webp"
  alt="Utilisation du SDK Python"
  flip="true"
  bg="plum"
>}}
<ul class="text-left">
  <li class="mb-2">
    <a href="https://galaxy.ansible.com/happydns/happydomain" target="_blank"><strong>Collection Ansible :</strong></a>
    <span class="text-hilight px-1 text-dark">ajouter ou modifier les enregistrements d'une zone,</span>
    gérer de nouveaux domaines via leur bureau d'enregistrement,
    gérer les utilisateurs d'happy<span class="fw-bold">Domain</span>,
    ou encore déployer happy<span class="fw-bold">Domain</span> lui-même grâce à la collection officielle.
  </li>
  <li class="mb-2">
    <a href="https://pypi.org/project/happydomain/" target="_blank"><strong>SDK Python :</strong></a>
    automatiser tous les aspects liés à vos domaines, avec la simplicité de Python.
  </li>
  <li class="mb-2">et d'autres encore&hellip;</li>
</ul>
{{< /usage-feature >}}

{{< usage-feature
  title="Supervision incluse, aucune stack supplémentaire à déployer."
  image="/img/screenshots/checks-dashboard.webp"
  alt="Tableau de bord de supervision affichant l'état de chaque vérification d'un domaine"
>}}
Les vérificateurs d'happy<span class="fw-bold">Domain</span> contrôlent en continu les expirations, le DNSSEC, la délégation, les certificats et la disponibilité des services pour chaque domaine que vous gérez.

Chaque vérification rapporte un état clair et vous notifie dès qu'il change, pour qu'une délégation cassée n'attende jamais un déploiement raté pour être remarquée.
{{< /usage-feature >}}
