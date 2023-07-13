# Steam Errors

Below you'll find explanations and troubleshooting steps for the most common
Steam errors.

The number in square brackets is the
[Steam error code](https://steamerrors.com/) returned by Steam when account
creation fails.

==- [17] Steam has banned the domain!

Steam permanently banned the Domain you chose!

- If you are using one of our [Free](domains/free.md) or
  [Premium](domains/premium.md) pools, please contact us so we can rotate the
  domain.
- If you are using a [Custom Domain](domains/customdomain.md), you will need to
  use buy and setup a different one.

===

==- [84] Steam is temporarily limiting account creations.

Steam ratelimited your account creation. This can either be due to your IP
hitting the limit, or your E-Mail domain hitting the limit.

The limits appear to be the following:

- 15 per day per IP
  - Use a proxy, or wait a day
- 100 per day per Domain
  - Use a different domain, or wait a day

If you are using the [Free](domains/free.md) domain pool, it's very likely that
others have already exhausted the quota of the domain. You should consider using
a [Custom Domain](domains/customdomain.md) or
[Premium Domain](domains/premium.md).

===

==- [101] Steam refused account generation.

Steam refused to generate the account. This is most often related to your IP not
being trusted by Steam.

However, Steam seems to also randomly give this error sometimes, so you should
try multiple times before declaring the IP as dead.
([Mass Generator](features/mass-generator.md) will retry up to 5 times before
aborting)

===

==- [105] Steam has banned your IP

You are IP banned! Steam bans VPNs, proxies etc. Try a different one.

If you aren't using a VPN, :skull:.

===
