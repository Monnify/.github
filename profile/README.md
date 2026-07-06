<div align="center">
  <img src="https://developers.monnify.com/svg/monnifyLogo.svg" alt="Monnify" width="260" />

  <h3>Payments infrastructure for African businesses</h3>

  <p>
    Accept payments, disburse funds, verify identities, and manage wallets &mdash;
    all through one API.
  </p>

  <p>
    <a href="https://monnify.com"><strong>Website</strong></a> ·
    <a href="https://developers.monnify.com"><strong>API Docs</strong></a> ·
    <a href="https://app.monnify.com/create-account"><strong>Create an Account</strong></a> ·
    <a href="https://slack.monnify.com/"><strong>Developer Slack</strong></a>
  </p>

  <p>
    <a href="https://twitter.com/monnify"><img src="https://img.shields.io/badge/Twitter-%40monnify-1DA1F2?logo=twitter&logoColor=white" alt="Twitter"></a>
    <a href="https://www.instagram.com/monnifyhq/"><img src="https://img.shields.io/badge/Instagram-%40monnifyhq-E4405F?logo=instagram&logoColor=white" alt="Instagram"></a>
    <a href="https://www.facebook.com/Monnify-102435331122100/"><img src="https://img.shields.io/badge/Facebook-Monnify-1877F2?logo=facebook&logoColor=white" alt="Facebook"></a>
    <a href="https://monnify.statuspage.io/"><img src="https://img.shields.io/badge/Status-Live-brightgreen" alt="Status"></a>
  </p>
</div>

---

## What Monnify does

Monnify is a payment gateway that lets businesses **collect** payments (card, bank transfer, USSD, reserved accounts),
**disburse** funds (single and bulk transfers), **verify** customers (BVN/NIN/account lookups), and manage **wallets** &mdash;
via REST APIs and native SDKs.

Start here: [developers.monnify.com](https://developers.monnify.com) for the full API reference and integration guides.

## Official SDKs & wrappers

<table>
<tr>
<td align="center" width="140">
<a href="https://github.com/Monnify/AndroidSDK"><img src="https://developers.monnify.com/svg/androidicon.svg" width="40" height="40" alt="Android"/><br/><b>Android</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/IOS-SDk"><img src="https://developers.monnify.com/svg/appleicon.svg" width="40" height="40" alt="iOS"/><br/><b>iOS</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/FlutterSDK"><img src="https://developers.monnify.com/svg/fluttericon.svg" width="40" height="40" alt="Flutter"/><br/><b>Flutter</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/WebSDK"><img src="https://developers.monnify.com/svg/worldicon.svg" width="40" height="40" alt="Web"/><br/><b>Web SDK</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/Monnify-Nodejs-lib"><img src="https://developers.monnify.com/logos/nodejs.svg" width="40" height="40" alt="Node.js"/><br/><b>Node.js</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/Monnify-ts"><img src="https://developers.monnify.com/logos/typescript.svg" width="40" height="40" alt="TypeScript"/><br/><b>TypeScript</b></a>
</td>
</tr>
<tr>
<td align="center" width="140">
<a href="https://github.com/Monnify/Monnify-PHP-SDK"><img src="https://cdn.simpleicons.org/php" width="40" height="40" alt="PHP"/><br/><b>PHP</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/monnify-laravel"><img src="https://developers.monnify.com/logos/laravel.png" width="40" height="40" alt="Laravel"/><br/><b>Laravel</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/monnify-python"><img src="https://developers.monnify.com/logos/python.png" width="40" height="40" alt="Python"/><br/><b>Python</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/Monnify-java-sdk"><img src="https://developers.monnify.com/logos/java.svg" width="40" height="40" alt="Java"/><br/><b>Java</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/Monnify-Go-Wrapper"><img src="https://developers.monnify.com/logos/golang.png" width="40" height="40" alt="Go"/><br/><b>Go</b></a>
</td>
<td align="center" width="140">
<a href="https://github.com/Monnify/monnify-dotnet-lib"><img src="https://developers.monnify.com/logos/dotnet.png" width="40" height="40" alt=".NET"/><br/><b>.NET</b></a>
</td>
</tr>
</table>

## AI integration (MCP)

<table>
<tr>
<td align="center" width="140">
<a href="https://www.npmjs.com/package/@monnify/mcp-server"><img src="https://cdn.simpleicons.org/modelcontextprotocol" width="40" height="40" alt="MCP"/><br/><b>MCP Server</b></a>
</td>
</tr>
</table>

[`@monnify/mcp-server`](https://www.npmjs.com/package/@monnify/mcp-server) is a [Model Context Protocol](https://modelcontextprotocol.io) server that lets AI clients (Claude Desktop, Cursor, VS Code, and others) accept payments, verify identities, manage virtual accounts, and query transactions using natural language instead of direct API calls. See the [integration guide](https://developers.monnify.com/docs/integration/mcp-server) for setup and the full tool list.

## Samples & integration guides

Reference implementations showing common integration patterns &mdash; not maintained SDKs.

- [monnify-sample-webhook-nodejs](https://github.com/Monnify/monnify-sample-webhook-nodejs) &mdash; verifying and handling webhook events in Node.js
- [Webhook-ASP-NET](https://github.com/Monnify/Webhook-ASP-NET) &mdash; webhook handling in ASP.NET
- [monnify-django-webhook](https://github.com/Monnify/monnify-django-webhook) &mdash; webhook verification in Django
- [ReservedAccount-Sample](https://github.com/Monnify/ReservedAccount-Sample) &mdash; Reserved (virtual) Account API usage
- [monnify-wallet-impl-java](https://github.com/Monnify/monnify-wallet-impl-java) &mdash; wallet feature using Reserved Accounts + disbursements
- [Monnify-Sample-Store](https://github.com/Monnify/Monnify-Sample-Store) / [samplestore-using-websdk-monnify](https://github.com/Monnify/samplestore-using-websdk-monnify) &mdash; ecommerce checkout demos
- [monnify-wordpress-plugin](https://github.com/Monnify/monnify-wordpress-plugin) &mdash; WordPress/WooCommerce plugin
- [monnify-php-sample-codes](https://github.com/Monnify/monnify-php-sample-codes) &mdash; PHP integration snippets

## Getting help

- 📖 Docs: [developers.monnify.com](https://developers.monnify.com)
- 💬 Developer community: [slack.monnify.com](https://slack.monnify.com/)
- 📊 Service status: [monnify.statuspage.io](https://monnify.statuspage.io/)
- ✉️ Support: integration-support@monnify.com
