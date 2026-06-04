+++
title = "Join the beta"
description = "Public registrations on app.happydomain.org are closed. Join the beta program or self-host happyDomain to get started."
+++

## Online version closed

Public registrations on `app.happydomain.org` are paused while we
polish the next release.

### happyDomain is evolving

happyDomain will soon let you **continuously test the security of
your domains** and **monitor every service exposed through DNS**
(web, mail, VPN, etc.) — all of this **with zero configuration**,
working straight from your existing records.

We are rolling out this new version **progressively**, to gather
feedback from our users and refine the service before reopening it
to everyone. Your input at this stage is invaluable in helping us
deliver the best possible product.

Two ways to use happyDomain right now:

### 1. Join the beta program

Subscribe below and we will send you an invitation once a spot opens up.

<form
  class="card card-body bg-light my-4"
  method="post"
  action="https://lists.happydomain.org/subscription/form"
>
  <input type="hidden" name="nonce" />
  <input type="hidden" name="l" value="ef8b61ad-fa7d-4f1a-a20f-bb34ac37a3bf" />
  <input type="hidden" name="lang" value="en" />
  <div class="mb-3">
    <label for="beta-email" class="form-label">Your email</label>
    <input type="email" id="beta-email" name="email" required placeholder="j.postel@isi.edu" class="form-control" />
  </div>
  <altcha-widget floating class="mb-3 mx-auto" challengeurl="https://lists.happydomain.org/api/public/captcha/altcha"></altcha-widget>
  <button type="submit" class="btn btn-primary" data-umami-event="beta-page-join">
    Request beta access
  </button>
</form>

### 2. Self-host happyDomain

happyDomain is open source. You can run it on your own machine in minutes:

- **Binary:** download a [release for your platform](/#downloads).
- **Docker:** `docker run -p 8081:8081 happydomain/happydomain`.

Source code and documentation live on [git.happydomain.org](https://git.happydomain.org/).
