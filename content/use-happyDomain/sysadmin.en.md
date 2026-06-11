+++
title = "happyDomain for System Administrators"
description = "Simplify DNS zone management across multiple providers. happyDomain gives sysadmins a unified interface with history, rollback, and audit trails."
layout = "usage"
+++

{{< usage-lead >}}
A <span class="text-hilight px-1">single interface</span> to view and manage your zones, both internal <span class="text-nowrap">(Bind, ...)</span> and public <span class="text-nowrap">(OVH, Gandi, ...)</span>.
{{< /usage-lead >}}

{{< usage-points title="Does this sound familiar?" >}}
{{< usage-point icon="terminal" title="Two worlds, two workflows" >}}
SSH and a text editor for the internal zones, a different web console for each public provider. Same records, completely different tools.
{{< /usage-point >}}
{{< usage-point icon="arrow-counterclockwise" title="No undo" >}}
A bad record propagates in seconds. Recovering means digging through backups or your memory, while the service is down.
{{< /usage-point >}}
{{< usage-point icon="inboxes" title="Every change lands on you" >}}
You're the only one trusted to touch DNS, so every record request becomes a ticket in your queue.
{{< /usage-point >}}
{{< /usage-points >}}

{{< usage-feature
  title="Edit all your zones in one place, internal and public."
  image="/img/screenshots/domain-abstract.webp"
  alt="A zone displayed the same clear way, whatever the host"
>}}
Whatever the host of your zones, happy<span class="fw-bold">Domain</span> displays them in the same clear way, limiting errors.

Install happy<span class="fw-bold">Domain</span> next to your Bind or PowerDNS and enjoy the interface without changing your configuration. <span class="text-muted">(coming soon)</span>
{{< /usage-feature >}}

{{< usage-feature
  title="View your changes before applying them."
  image="/img/screenshots/zone-diff.webp"
  alt="Review and confirm the changes that will be applied"
  flip="true"
  bg="green"
>}}
Before publishing, happy<span class="fw-bold">Domain</span> shows you exactly what will change. A preview that avoids many mistakes, on zones where mistakes are expensive.

You can even select which changes go out now and which ones should wait.
{{< /usage-feature >}}

{{< usage-feature
  title="Full history, instant rollback."
  image="/img/screenshots/domain-history.webp"
  alt="History of every version of a zone"
>}}
Every version of every zone is kept, with who changed what and when.

When something breaks, you don't reconstruct the previous state from backups: you roll the zone back to it in one click, then investigate calmly.
{{< /usage-feature >}}

{{< usage-feature
  title="Catch problems before they become outages."
  image="/img/screenshots/checks-dashboard.webp"
  alt="Monitoring dashboard showing the status of every check on a domain"
  flip="true"
  bg="plum"
>}}
With built-in checkers, happy<span class="fw-bold">Domain</span> keeps an eye on your domains and zones around the clock: registration expiry, DNSSEC validity, delegation consistency, TLS certificates, response times and more.

Each check is evaluated against clear rules and reported as <span class="fw-bold">OK</span>, <span class="fw-bold">Warning</span> or <span class="fw-bold">Critical</span>, so you spot what needs attention at a glance and get notified the moment a check changes state.
{{< /usage-feature >}}

{{< usage-feature
  title="Share zone management with your teams."
  image="/img/screenshots/domain-abstract-records.webp"
  alt="Zone management shared between teams"
  coming_soon="true"
>}}
Whether it's permanent or in preparation for a particular event, happy<span class="fw-bold">Domain</span> lets several people collaborate on the same zone.

Delegate all or only part of a zone, down to a single record. The routine requests leave your queue; the control stays with you.
{{< /usage-feature >}}

{{< usage-feature
  title="Manage simply, even the special zones."
  image="/img/screenshots/service-caa.webp"
  alt="Editing an advanced DNS service through a guided form"
  flip="true"
  bg="green"
  coming_soon="true"
>}}
Looking for an interface that displays reverse IPv4/IPv6 zones in a human way?
Or a <a href="https://en.wikipedia.org/wiki/DNSBL">Real-time Blackhole List (DNSBL)</a> zone? Or DNS <a href="https://www.dnsrpz.info/">Response Policy Zones</a> (DNS-RPZ)?

happy<span class="fw-bold">Domain</span> understands them and lets you manage them unequivocally.
{{< /usage-feature >}}
