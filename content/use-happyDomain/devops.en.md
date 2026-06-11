+++
title = "happyDomain for DevOps Engineers"
description = "Automate DNS management with happyDomain's REST API. Integrate domain operations into your CI/CD pipelines and infrastructure workflows."
layout = "usage"
+++

{{< usage-lead >}}
A <span class="text-hilight px-1">REST API and web interface</span> to automate domain management <span class="text-hilight px-1">in the cloud, with suppliers and on premise</span>.
{{< /usage-lead >}}

{{< usage-points title="Does this sound familiar?" >}}
{{< usage-point icon="mouse" title="ClickOps doesn't scale" >}}
Everything in your stack is code, except DNS. Records are still changed by hand in a provider's console: unscriptable, unreviewable, unrepeatable.
{{< /usage-point >}}
{{< usage-point icon="plug" title="One API per provider" >}}
Each host has its own API, its own auth, its own quirks. Your automation is a pile of fragile glue scripts that breaks every time a client changes provider.
{{< /usage-point >}}
{{< usage-point icon="git" title="DNS bypasses your pipeline" >}}
Deployments are reviewed, tested and rolled back. DNS changes go straight to production with none of that.
{{< /usage-point >}}
{{< /usage-points >}}

{{< usage-feature
  title="One REST API for all your domains' operations."
  image="/img/screenshots/features/rest.png"
  alt="Our REST API, commented and exposed with Swagger"
>}}
Everything that's done in the happy<span class="fw-bold">Domain</span> web interface can be done with the API, in your language of choice. Script it once, run it everywhere.

Our REST API is fully documented, and thanks to Swagger, you can browse it and generate a client in any supported language.

<a href="/swagger/index.html" target="_blank">See the API documentation and try it out now!</a>
{{< /usage-feature >}}

{{< usage-feature
  title="Forget the quirks of each provider. One abstraction for over 25 hosts."
  image="/img/screenshots/domain-abstract.webp"
  alt="A zone displayed the same way, whatever the provider behind it"
  flip="true"
  bg="green"
>}}
Write your automation against happy<span class="fw-bold">Domain</span> once; it speaks to every provider for you:

<ul class="text-left">
  <li class="mb-1"><strong>cloud services&nbsp;:</strong> Route53, Azure DNS, Google Cloud DNS, DigitalOcean, Linode, Oracle Cloud, ...</li>
  <li class="mb-1"><strong>CDN&nbsp;:</strong> Akamai Edge DNS, Cloudflare, ...</li>
  <li class="mb-1"><strong>registrar&nbsp;:</strong> OVH, Gandi, Namecheap, Vultr, ...</li>
  <li class="mb-1"><strong>your local setup&nbsp;:</strong> BIND, PowerDNS, knot, ...</li>
</ul>

<a href="https://docs.dnscontrol.org/service-providers/providers" target="_blank">See the list of supported DNS hosts.</a>
{{< /usage-feature >}}

{{< usage-feature
  title="Bring DNS into your review workflow."
  image="/img/screenshots/zone-diff.webp"
  alt="Review and confirm the changes that will be applied"
>}}
Before anything is published, happy<span class="fw-bold">Domain</span> shows the exact diff between the current zone and the new one, and waits for confirmation.

You can even cherry-pick which changes ship now and which ones wait. It works like a pull request, for your DNS.
{{< /usage-feature >}}

{{< usage-feature
  title="Tooling that plugs into what you already use."
  image="/img/screenshots/sdk-python.webp"
  alt="Python SDK usage"
  flip="true"
  bg="plum"
>}}
<ul class="text-left">
  <li class="mb-2">
    <a href="https://galaxy.ansible.com/happydns/happydomain" target="_blank"><strong>Ansible collection:</strong></a>
    <span class="text-hilight px-1 text-dark">add or modify zone records,</span>
    manage new domains through their registrar,
    manage happy<span class="fw-bold">Domain</span>'s users,
    or deploy happy<span class="fw-bold">Domain</span> itself with the official collection.
  </li>
  <li class="mb-2">
    <a href="https://pypi.org/project/happydomain/" target="_blank"><strong>Python SDK:</strong></a>
    automate all aspects of your domains, with the simplicity of Python.
  </li>
  <li class="mb-2">and counting&hellip;</li>
</ul>
{{< /usage-feature >}}

{{< usage-feature
  title="Monitoring included, no extra stack to deploy."
  image="/img/screenshots/checks-dashboard.webp"
  alt="Monitoring dashboard showing the status of every check on a domain"
>}}
happy<span class="fw-bold">Domain</span>'s checkers continuously verify expirations, DNSSEC, delegation, certificates and service availability for every domain you manage.

Each check reports a clear status and notifies you the moment it changes state, so a broken delegation never waits for a failed deployment to be noticed.
{{< /usage-feature >}}
