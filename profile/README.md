## Welcome to the Orbiter GitHub

![cover](https://orbiter.host/og.png)

Orbiter is the easiest way to host static sites, open sourced and built on open web principles and technologies.

If you haven't already, try out Orbiter for free and [launch your first site](https://app.orbiter.host)!

Here is a quick overview of everything that runs Orbiter and the repo for each part:

- [orbiter-backend](https://github.com/orbiterhost/orbiter-backend) - The core server and API that handles Supabase, uploading files, creating new sites, ets.
- [orbiter-frontend](https://github.com/orbiterhost/orbiter-frontend) - The primary way users interact with Orbiter from sign up to deploying and managing sites
- [orbiter-contracts](https://github.com/orbiterhost/orbiter-contracts) - Every site on Orbiter has an [IPCM](https://ipcm.dev) on [Base](https://base.org) smart contract that holds the latest IPFS state of the site. These contracts help facilitate the deployment of those site contracts. 
- [orbiter-website-worker](https://github.com/orbiterhost/orbiter-website-worker) - A Cloudflare worker that takes a request for a website on Orbiter, fetches the IPFS data, and returns it
- [orbiter-analytics](https://github.com/orbiterhost/orbiter-analytics) - Our in-house analytics API and database for sites running on Orbiter
- [orbiter-resolver](https://github.com/orbiterhost/orbiter-resolver) - A special smart contract to help connect Orbiter Sites with ENS names
- [orbiter-nginx](https://github.com/orbiterhost/orbiter-nginx) - Self hosted SSL server and router
- [orbiter-cli](https://github.com/orbiterhost/orbiter-cli) - A developer tool for automating site deployments

If you have any questions feel free to [reach out](mailto:steve@orbiter.host,justin@orbiter.host)!
