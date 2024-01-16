---
title: happyDomain Press Kit
toc: yes
---

**happyDomain is a free and open-source interface that makes domain names accessibles and reduces the usual friction points.**\
Our modern interface centralizes your domains and includes all the features you'd expect these days for painless domain management.

We built happyDomain because we want to save operational teams time, by giving them superpowers:
to be in full control over their production's or internal domains, without having to read and learn all the regularly new standards, by staying focused on organizational needs.

Our mission is to help people become more independent on the Internet, in the face of the tech giants, by making domain names everyone's business. [See our blog post](https://blog.happydomain.org/fr/happydomain-simplifions-l-usage-des-noms-de-domaines/)


## The Origin

Back in 2018, Pierre-Olivier gave a lecture at a computer engineering school about system administration.
For a practical exercice, he implements a reduced hosting provider console, including domain management.

Students were astonished by the complexity, remembering Pierre-Olivier that no one at his job want to make domain updates.
At the same time [Stéphane Bortzmeyer commented on that complexity](https://www.bortzmeyer.org/hebergement-dns-chaton.html) for everyone else.
Clearly there was something to be done!


## Feature List

Here's an overview of happyDomain's main features:

- consolidate domain names from over 45 domain name providers or authoritative servers,
- guide administrators with clear forms,
- clearly visualize the changes that will be propagated,
- keep a history of changes made to the zone,
- return to a previous zone status with a single click,
- group records by services/needs: email, delegation, server, load balancing, etc.
- abstract all technical complexity into a logical view,
- import/export the zone as a standard file,
- keep track of actions for later auditing,
- automate tasks via a REST API.


## Technical Details

happyDomain has an ultra-fast user interface, backed with a small footprint binary or container.

We use state of the art tech:
- Our interface is based on [SvelteKit](https://kit.svelte.dev/), and relies on a [Service Worker](https://developer.mozilla.org/docs/Web/API/Service_Worker_API) to have a reduced network footprint: only API requests are exchanged once first loaded.
- The server is a Golang binary: even large zones are processed in a flash on low power devices.
- To be deployed in modern stack, we provide a [Alpine-based Docker image](https://hub.docker.com/r/happydomain/happydomain/), suitable for Docker, Podman, Kubernetes, ... and available for most common architectures: `amd64`, `arm` and `arm64`.

For the DNS part, we rely on battle tested dependencies, such as:
- The great [miekg's DNS library](https://github.com/miekg/dns), used by [CoreDNS](https://coredns.io/), at the heart of Kubernetes.
- Providers' integrations are given by the fantastic [dnscontrol project](https://dnscontrol.org/) of StackOverflow.


happyDomain is built to last: designed from the ground-up for all kind of load, with security and efficiency in mind.


## Usage and Applications

Today, we welcome all system administrators to join our platform:
- employes managing internal or publicly available domains,
- freelances handling large portfolio of customers,
- communication agencies with countless domain names,
- geeks looking for new horizons,
- privacy aware individuals wanting to gain their independence.

Domain names are everybody's business.
We built a simple interface that aims to respond to concretes needs, hidding all the complexity, changing standards from users.

Employes and freelances will enjoy our effortless platform.
Think of the time spent regularly on DNS issues, dealing with sometimes insane providers interface or their lack for X or Y features.
Moreover, reading and understanding documentations or searching tutorial for your exact setup can be tedious.
Each organizational or client request can be treated in seconds without fear or doubt, even without looking for some nasty tutorial or insanely-technical documentation.


## How to Test happyDomain

We are a free and open source project: you can use the official interface available at [`www.happydomain.org`](https://www.happydomain.org/), or install it at home.

A demonstration is available at [`try.happydomain.org`](https://try.happydomain.org/): you can evaluate how happyDomain work, no account or domain required.

For an easy deployment, we provide [a Docker image](https://hub.docker.com/r/happydomain/happydomain/): `docker run -e HAPPYDOMAIN_NO_AUTH=1 -p 8081:8081 happydomain/happydomain`

The source code is available on [framagit](https://framagit.org/happyDomain/): you can consult it, copy it, give your opinion, report bugs or make modifications, as you wish.


## Team and Community

happyDomain is built by a group of people based in Paris, in France.
Among others, [Pierre-Olivier](https://nemunai.re/) leads the developments and Frédéric federates the team.

We're building a community of users who want to regain control of their domain names.
You can join us on [our Matrix channel](https://matrix.to/#/#happyDNS:matrix.org), or find out more by following [our blog](https://blog.happydomain.org/) and [our Mastodon account](https://floss.social/@happyDomain).


## Media Assets

Main color: <span style="background: #1cb487; color: #fff; padding: 0.2em 0.5em; font-family: monospace">#1cb487</span>

### Logos

![happyDomain logo black](/img/assets/logo/happyDomain.png)
happyDomain logo black

![happyDomain logo white](/img/assets/logo/happyDomain-white.png)
happyDomain logo black

![happyDomain icon](/img/assets/logo/happyDomain-icon.png)
happyDomain icon

![happyDomain rounded icon](/img/assets/logo/happyDomain-rounded.png)
happyDomain rounded icon


### Screenshots

![happyDomain home page](/img/screenshots/domains-list.webp)
**happyDomain's home page:**
domains are listed by group, with their status. Filters are on the right.

---

![import a domain in happyDomain](/img/screenshots/domain-import.webp)
**Import a domain from a provider:**
when supported, just hit the button to synchronize it in happyDomain.

---

![happyDomain's supported providers](/img/assets/providers.webp)
happyDomain supports more than 45 providers to date, more to come thanks to [dnscontrol](https://dnscontrol.org/).

---

![domain abstraction created by happyDomain](/img/screenshots/domain-abstract.webp)
**Main domain page**:
an abstract view of the zone, the raw records are grouped under services.

---

![happyDomain expose simple but complete forms](/img/screenshots/service-caa.webp)
**The form to edit CAA records**:
each service is deeply explained, you are guided at each step.

---

![review the modifications before publishing them](/img/screenshots/zone-diff.webp)
Modifications are not directly propagated: you choose when to apply them in one go.
**A diff is presented before applying changes, a good way to avoid visible mistakes.**

---

![happyDomain keeps a history](/img/screenshots/domain-history.webp)
**happyDomain keeps an history:** view previous modifications, rollback in one click.

---

![happyDomain logs actions](/img/screenshots/domain-logs.webp)
**happyDomain logs actions made on the domain:** allowing future audits.


### Feature Graphics

![OpenGraph image](/img/og.webp)


## Contact Information

Don't hesitate to contact us at <press@happydomain.org> for any details or press inquiries.


## Frequently Asked Questions

##### Do you sell domain names?

No, happyDomain does not sell domains yet.
To start using our interface, you need to buy a domain from one of our [supported providers](https://www.happydomain.org/providers/features).


##### I don't want to rely on my domain name hosting provider anymore. Can I host my domain name on your infrastructure?

We'll provide such a feature in the near future, as it's on our manifest. We choose to focus first on spreading the word that domain names are accessibles to everyone through this sweet interface, before targeting privacy, censorship, …


##### I have my own infrastructure. Can I use happyDomain as a secondary authoritative server?

We'll provide such feature in a near future, as soon as our name server infrastructure is ready.
