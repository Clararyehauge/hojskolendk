## GitHub Copilot Chat

- Extension Version: 0.22.4 (prod)
- VS Code: vscode/1.95.2
- OS: Mac

## Network

User Settings:

```json
  "github.copilot.advanced": {
    "debug.useElectronFetcher": true,
    "debug.useNodeFetcher": false
  }
```

Connecting to https://api.github.com:

- DNS ipv4 Lookup: 140.82.121.5 (11 ms)
- DNS ipv6 Lookup: ::ffff:140.82.121.5 (3 ms)
- Electron Fetcher (configured): HTTP 200 (86 ms)
- Node Fetcher: HTTP 200 (166 ms)
- Helix Fetcher: HTTP 200 (303 ms)

Connecting to https://api.githubcopilot.com/_ping:

- DNS ipv4 Lookup: 140.82.114.21 (49 ms)
- DNS ipv6 Lookup: ::ffff:140.82.114.21 (2 ms)
- Electron Fetcher (configured): HTTP 200 (466 ms)
- Node Fetcher: HTTP 200 (425 ms)
- Helix Fetcher: HTTP 200 (417 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).
