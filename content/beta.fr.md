+++
title = "Rejoindre la bêta"
description = "Les inscriptions publiques sur app.happydomain.org sont fermées. Rejoignez le programme bêta ou auto-hébergez happyDomain pour commencer."
+++

## Version en ligne fermée

Les inscriptions publiques sur `app.happydomain.org` sont suspendues
le temps de finaliser la prochaine version.

### happyDomain se transforme

happyDomain va bientôt vous permettre de **tester en continu la
sécurité de vos domaines** et de **superviser l'ensemble des services
exposés via le DNS** (web, mail, VPN, etc.) — le tout **sans
configuration**, en s'appuyant directement sur vos enregistrements.

Nous déployons cette nouvelle version **progressivement**, afin de
recueillir les avis de nos utilisateurs et d'ajuster le service avant
sa réouverture publique. Votre retour à ce stade est précieux pour
nous aider à offrir le meilleur produit possible.

Deux manières d'utiliser happyDomain dès maintenant :

### 1. Rejoindre le programme bêta

Inscrivez-vous ci-dessous, nous vous enverrons une invitation
dès qu'une place se libère.

<form
  class="card card-body bg-light my-4"
  method="post"
  action="https://lists.happydomain.org/subscription/form"
>
  <input type="hidden" name="nonce" />
  <input type="hidden" name="l" value="ef8b61ad-fa7d-4f1a-a20f-bb34ac37a3bf" />
  <input type="hidden" name="lang" value="fr" />
  <div class="mb-3">
    <label for="beta-email" class="form-label">Votre email</label>
    <input type="email" id="beta-email" name="email" required placeholder="j.postel@isi.edu" class="form-control" />
  </div>
  <altcha-widget floating class="mb-3 mx-auto" challengeurl="https://lists.happydomain.org/api/public/captcha/altcha"></altcha-widget>
  <button type="submit" class="btn btn-primary" data-umami-event="beta-page-join">
    Demander un accès bêta
  </button>
</form>

### 2. Auto-héberger happyDomain

happyDomain est libre. Vous pouvez le faire tourner sur votre propre machine en quelques minutes :

- **Binaire :** téléchargez une [version pour votre plateforme](/fr/#downloads).
- **Docker :** `docker run -p 8081:8081 happydomain/happydomain`.

Le code source et la documentation sont sur [git.happydomain.org](https://git.happydomain.org/).
