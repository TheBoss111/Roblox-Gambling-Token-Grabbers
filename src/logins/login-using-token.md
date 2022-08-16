# Login using an authentication token

Logging in using an authentication token is easy! Here's how you would go about it:

```js 
// RBXFLIP AUTH TOKEN LOGIN
{
	let token = "MTAwOTAxNDA0MjM2NDQ4OTgxOQ.GdRaCL.V7ukdZbMumpkzWxzhksqGYFSsYN40ziCkyfdLs";
	window.localStorage["accessToken"] = token;
	// RESET THE PAGE
  location.reload();
}
```


```js 
// BLOXFLIP AUTH TOKEN LOGIN
{
	let token = "MTAwOTAxNDA0MjM2NDQ4OTgxOQ.GdRaCL.V7ukdZbMumpkzWxzhksqGYFSsYN40ziCkyfdLs";
	window.localStorage["_DO_NOT_SHARE_BLOXFLIP_TOKEN"] = token;
	// RESET THE PAGE
  location.reload();
}
```


## Other sites

replace `window.localStorage["accessToken"] = token;`'s `accessToken` with the name of they auth tokens key from its key-value pair in localStorage.
