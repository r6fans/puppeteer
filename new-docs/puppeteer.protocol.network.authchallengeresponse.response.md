<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [AuthChallengeResponse](./puppeteer.protocol.network.authchallengeresponse.md) &gt; [response](./puppeteer.protocol.network.authchallengeresponse.response.md)

## Protocol.Network.AuthChallengeResponse.response property

The decision on what to do in response to the authorization challenge. Default means deferring to the default behavior of the net stack, which will likely either the Cancel authentication or display a popup dialog box.

<b>Signature:</b>

```typescript
response: ('Default' | 'CancelAuth' | 'ProvideCredentials');
```