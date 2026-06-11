+++
title = "happyDomain for Enthusiasts"
description = "Take control of your domain names with a powerful, open-source interface. happyDomain makes DNS management fun and accessible for hobbyists and tech enthusiasts."
layout = "usage"
+++

{{< usage-lead >}}
An <span class="text-hilight px-1">open-source interface</span> to keep your <span class="text-hilight px-1">independence</span> on the web.
{{< /usage-lead >}}

{{< usage-points title="Does this sound familiar?" >}}
{{< usage-point icon="house-gear" title="Self-hosted, except DNS" >}}
Your mail, your cloud, your git are on your own servers. But your DNS still lives in a closed registrar console you don't control.
{{< /usage-point >}}
{{< usage-point icon="exclamation-triangle" title="One typo from disaster" >}}
Raw zone files are unforgiving. A missing dot, a wrong TTL, and your mail silently vanishes for hours before you notice.
{{< /usage-point >}}
{{< usage-point icon="lock" title="Locked into a provider" >}}
Each registrar's interface decides what you can do and how. Moving your zones elsewhere means relearning everything.
{{< /usage-point >}}
{{< /usage-points >}}

{{< usage-feature
  title="A simple and clear interface, whatever the host."
  image="/img/screenshots/domain-abstract.webp"
  alt="A zone displayed in a clear, human-readable way"
>}}
Whether your zones live at a registrar or on your own servers, happy<span class="fw-bold">Domain</span> displays them the same clear way, limiting errors.

Install happy<span class="fw-bold">Domain</span> next to your Bind or PowerDNS and enjoy the interface without changing your configuration.
<span class="text-muted">(coming soon)</span>
{{< /usage-feature >}}

{{< usage-feature
  title="Self-hosting made easy, even for DNS."
  image="/img/screenshots/providers-list.webp"
  alt="List of supported providers, from cloud services to self-hosted servers"
  flip="true"
  bg="green"
>}}
With the same interface, manage your zone at a third-party provider or run your own DNS servers. Your domains, your rules.

Don't be afraid of editing a zone text file: we take care of it.

happy<span class="fw-bold">Domain</span> is open source, needs very few resources, runs happily on a Raspberry Pi, and can even be launched only when needed.
{{< /usage-feature >}}

{{< usage-feature
  title="Tinker without fear: preview, history, rollback."
  image="/img/screenshots/zone-diff.webp"
  alt="Review and confirm the changes that will be applied"
>}}
Before any change is published, happy<span class="fw-bold">Domain</span> shows you exactly what will be modified and asks for confirmation. No more silent typos.

And since every version of your zone is kept in history, you can experiment freely and roll back in one click if something goes wrong.
{{< /usage-feature >}}

{{< usage-feature
  title="Set up any service in all simplicity."
  image="/img/screenshots/domain-services.webp"
  alt="Services attached to a domain, described in plain words"
  flip="true"
  bg="plum"
>}}
A new service? An urgent fix? happy<span class="fw-bold">Domain</span> uses simple terminology to stay focused on the expected result.

We are committed to providing the latest in DNS registration and services, so your setup never lags behind the standards.
{{< /usage-feature >}}

{{< usage-feature
  title="Manage easily, even special zones."
  image="/img/screenshots/service-caa.webp"
  alt="Editing an advanced DNS service through a guided form"
  coming_soon="true"
>}}
Looking for an interface that displays reverse IPv4/IPv6 zones in a human way?
Or a <a href="https://en.wikipedia.org/wiki/DNSBL">Real-time Blackhole List (DNSBL)</a> zone? Or DNS <a href="https://www.dnsrpz.info/">Response Policy Zones</a> (DNS-RPZ)?

happy<span class="fw-bold">Domain</span> understands them and lets you manage them unequivocally.
{{< /usage-feature >}}
