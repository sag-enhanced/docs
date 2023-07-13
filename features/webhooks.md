# Webhooks

SAGE allows you to send Webhook notifications everytime an account is generated
successfully.

[!ref Webhooks](https://sage.party/dash#webhooks)

!!!danger Untrusted webhooks

Webhooks receive all information about your Steam account. This includes the
username, password, email address, email password and cookie.

They also get your IP because webhooks are sent directly from your browser.

Only add webhooks you truly trust.

!!!

## Discord Webhooks

SAGE has special logic for Discord webhooks, so they work directly out of the
box. The request payload will be automatically be converted to be Discord
compatible and show a beautiful embed.

## Any Webhook

Any webhook URL (that is not Discord) will get a payload like the following
`POST`ed to it:

```json
{
	"id": "<steam64-id>",
	"profile": {
		"username": "<your-steam-username>",
		"password": "<your-steam-password>"
	},
	"email": {
		"username": "<your-email-username>",
		"password": "<your-email-password>"
	},
	"cookieJar": [
		{
			"name": "steamLoginSecure",
			"url": "https://store.steampowered.com",
			"value": "<your-steam-auth-cookie>"
		},
		{
			"name": "sessionid",
			"url": "https://store.steampowered.com",
			"value": "<your-steam-session-cookie>"
		}
	]
}
```

!!!info Ignore undocumented fields

There are some more fields that are undocumented. You should ignore undocumented
fields.

Also don't complain if they disappear one day.

!!!
