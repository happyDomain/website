+++
title = "happyDomain for System Administrators"
description = "Simplify DNS zone management across multiple providers. happyDomain gives sysadmins a unified interface with history, rollback, and audit trails."
layout = "usage"
+++

{{< usage-lead >}}
A <span class="text-hilight">simple interface</span> to view and manage your zones, both internals <span class="text-nowrap">(Bind, ...)</span> and publics <span class="text-nowrap">(OVH, Gandi, ...)</span>.
{{< /usage-lead >}}

{{< usage-feature
  title="Edit your zone files more efficiently."
  image="/img/screenshots/domain-abstract.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
>}}
Whatever the host of your zones, happy<span class="fw-bold">Domain</span> displays them in a clear way to limit errors.

By installing happy<span class="fw-bold">Domain</span> next to your Bind or PowerDNS, enjoy the interface without changing your configuration. <span class="text-muted">(coming soon)</span>
{{< /usage-feature >}}

{{< usage-feature
  title="View your changes before applying them."
  image="/img/screenshots/zone-diff.webp"
  alt="Review and confirm the changes that will be applied"
  flip="true"
  bg="green"
>}}
Before publishing your changes, happy<span class="fw-bold">Domain</span> shows you what changes will be made. A preview that will avoid many mistakes.

You can even select which changes you want to release now and which ones should wait.
{{< /usage-feature >}}

{{< usage-feature
  title="Share the zone management with your teams or collaborators."
  image="/img/screenshots/domain-abstract.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
  coming_soon="true"
>}}
Whether it's permanent or in preparation for a particular event, happy<span class="fw-bold">Domain</span> gives you the ability to collaborate on editing the same area.

Delegate to your teams all or only part of the area, it's up to you.
{{< /usage-feature >}}

{{< usage-feature
  title="Manage simply, even the special zones."
  image="/img/screenshots/domains-list.webp"
  alt="Liste des domaines, regroupés astucieusement par client"
  flip="true"
  bg="plum"
  coming_soon="true"
>}}
Looking for an interface that displays reverse IPv4/IPv6 zones in a human way?
Or a <a href="https://en.wikipedia.org/wiki/DNSBL">Real-time Blockhole List (DNSBL)</a> zone? Or a DNS <a href="https://www.dnsrpz.info/">Response Policy Zones</a> (DNS-RPZ)?

happy<span class="fw-bold">Domain</span> understands them and allows you to manage them unequivocally.
{{< /usage-feature >}}

{{< usage-feature
  title="Catch problems before they become outages."
  image="/img/screenshots/checks-dashboard.webp"
  alt="Monitoring dashboard showing the status of every check on a domain"
>}}
With built-in checkers, happy<span class="fw-bold">Domain</span> keeps an eye on your domains and zones around the clock: registration expiry, DNSSEC validity, delegation consistency, TLS certificates, response times and more.

Each check is evaluated against clear rules and reported as <span class="fw-bold">OK</span>, <span class="fw-bold">Warning</span> or <span class="fw-bold">Critical</span>, so you can spot what needs attention at a glance, and get notified the moment a check changes state.
{{< /usage-feature >}}
