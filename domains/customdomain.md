---
order: 1
---

# Custom Domain

A Custom Domain is a domain owned and operated by **you**! You have full control
over it, but must also buy it from somewhere.

## Banned TLDs

Steam outright bans a few top-level-domains from creating any accounts, so make
sure you don't buy one of them!

==- Banned TLD list

The following TLDs are banned:

- `.xyz`
- `.ru.com`
- `.za.com`
- `.sa.com`
- `.tk`
- `.cf`
- `.ga`
- `.ml`
- `.gq`

**This list is provided on a best-effort basis with no warranty whatsoever.**

===

## Recommendations

If you are planing to use your custom domain for multiple years, we recommend
buying domains through [Cloudflare Registrar][1], because they have the lowest
_Renewal_ costs.

==- Recommended TLDs for Cloudflare

We recommend the following TLDs for Cloudflare: (3.98$ renewal)

- `.win`
- `.trade`
- `.stream`
- `.party`
- `.men`
- `.loan`
- `.download`
- `.date`
- `.bid`

===

If you don't care about long-lived E-Mail access, we recommend using
[NameCheap][2] and [their first-year discounts (99ct domains)][3].

If you've already used the 99ct promo code, we recommend TLDs like `.click`.

[1]: https://developers.cloudflare.com/registrar/
[2]: https://namecheap.com/
[3]: https://www.namecheap.com/promos/99-cent-domain-names/

## E-Mail forwarding

For E-Mails to your custom domain to actually arrive at our servers, you need to
forward them to `forward@sage.party`.

Below you'll find guides for using NameCheap and Cloudflare to do this, but
there probably are other ways too.

!!!info Legacy forwarding address

The legacy forwarding address `sage@leodev.xyz` will continue to work.

Going forward we are not going to approve any Verification E-Mails for it, so
please use `forward@sage.party` for new setups.

!!!

### Forwarding using NameCheap

Your domain must be registered with NameCheap for this.

1. Go to the [Domain dashboard](https://ap.www.namecheap.com/)
2. Click _MANAGE_ next to your domain
3. Scroll down to _REDIRECT EMAIL_
4. Click _ADD CATCH-All_
5. Set `forward@sage.party` as forward to
6. Click √ to save your changes

### Forwarding using Cloudflare

Your domain must be
[added to a Cloudflare Account](https://developers.cloudflare.com/fundamentals/get-started/setup/add-site/)
for this.

1. Enable
   [Email Routing](https://developers.cloudflare.com/email-routing/get-started/enable-email-routing/)
2. Go to _Routes_
3. Scroll to _Catch-all address_
4. Click on _Edit_ and change the action to `Send to an email`
5. Enter `forward@sage.party` as destination.
6. Click _Save_
7. Enable the checkbox on the right to finalize the Email Routing setup

!!!warning Verification E-Mail

If this is your first-time setup, Cloudflare will sent a Verification E-Mail to
us. We will approve this when we have time, you don't need to do anything but
wait.

!!!

## DNS Verification

When you add your custom domain to SAGE, we require you to prove that you
control the domain by adding a TXT record.

After the process is completed, you can remove the TXT record again.

If you set a password, we will remember it and you'll only need to provide the
password the next time you **add the domain**. If you didn't set a password, or
forgot it, you will need to redo the DNS verification.
