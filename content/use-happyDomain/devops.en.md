+++
title = "happyDomain for DevOps Engineers"
description = "Automate DNS management with happyDomain's REST API. Integrate domain operations into your CI/CD pipelines and infrastructure workflows."
layout = "usage"
+++

{{< usage-lead >}}
A <span class="text-hilight px-1">REST API and web interface</span> to centralize domain management <span class="text-hilight px-1">in the cloud, with suppliers and on premise</span>.
{{< /usage-lead >}}

{{< usage-feature
  title="All your domains' operations accessible via a REST API."
  image="/img/screenshots/features/rest.png"
  alt="Our REST API, commented and exposed with Swagger"
>}}
Everything that's done in the happy<span class="fw-bold">Domain</span> web interface can easily be done with the API, in your language of choice.

Our REST API is fully documented, and thanks to Swagger, you can browse it and easily generate a tool using it in any supported language.

<a href="/swagger/index.html" target="_blank">See the API documentation and try it out now!</a>
{{< /usage-feature >}}

{{< usage-feature
  title="Forget about the complexity of each hosting company. Take advantage of our unified interface."
  image="/img/screenshots/domain-abstract.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
  flip="true"
  bg="green"
>}}
Don't be afraid of discovering a new host. happy<span class="fw-bold">Domain</span> manages over 25 hosts worldwide:

<ul class="text-left">
  <li class="mb-1"><strong>cloud services&nbsp;:</strong> Route53, Azure DNS, Google Cloud DNS, DigitalOcean, Linode, Oracle Cloud, ...</li>
  <li class="mb-1"><strong>CDN&nbsp;:</strong> Akamai Edge DNS, Cloudflare, ...</li>
  <li class="mb-1"><strong>registrar&nbsp;:</strong> OVH, Gandi, Namecheap, Vultr, ...</li>
  <li class="mb-1"><strong>your local setup&nbsp;:</strong> BIND, PowerDNS, knot, ...</li>
</ul>

<a href="https://docs.dnscontrol.org/service-providers/providers" target="_blank">See the list of supported DNS hosts.</a>
{{< /usage-feature >}}

{{< usage-feature
  title="Respond to all requests with ease."
  image="/img/screenshots/domain-services.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
>}}
A new service? An urgent fix? happy<span class="fw-bold">Domain</span> uses simple terminology to stay focused.
{{< /usage-feature >}}

{{< usage-feature
  title="Many tools are already available for you, DevOps."
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
    or deploy happy<span class="fw-bold">Domain</span> using the official Ansible collection.
  </li>
  <li class="mb-2">
    <a href="https://pypi.org/project/happydomain/" target="_blank"><strong>Python SDK:</strong></a>
    easily automate all aspects of your domains, with the simplicity of Python.
  </li>
  <li class="mb-2">and counting&hellip;</li>
</ul>
{{< /usage-feature >}}
