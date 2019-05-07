
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const cancel = {
  Comment: "Cancelling for this week due to all hands"
};

let res = await client.api('/me/events/{id}/cancel')
	.version('beta')
	.post(cancel);

```