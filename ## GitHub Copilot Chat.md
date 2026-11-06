## GitHub Copilot Chat

- Extension: 0.67.0 (prod)
- VS Code: 1.139.0 (2242ebbb54efeeb0129e08e919e7e8d43033cd83)
- OS: linux 6.8.0-1064-azure x64
- Remote Name: codespaces
- Extension Kind: Workspace
- GitHub Account: jsknowl

## Network

User Settings:
```json
  "http.systemCertificatesNode": true,
  "telemetry.telemetryLevel": "all",
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 140.82.114.6 (2 ms)
- DNS ipv6 Lookup: Error (12 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (111 ms)
- Electron fetch: Unavailable
- Node.js https: HTTP 200 (85 ms)
- Node.js fetch (configured): HTTP 200 (55 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.112.21 (2 ms)
- DNS ipv6 Lookup: Error (4 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (25 ms)
- Electron fetch: Unavailable
- Node.js https: HTTP 200 (187 ms)
- Node.js fetch (configured): HTTP 200 (91 ms)

Connecting to https://proxy.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 20.85.130.105 (4 ms)
- DNS ipv6 Lookup: Error (2 ms): getaddrinfo ENOTFOUND proxy.individual.githubcopilot.com
- Proxy URL: None (22 ms)
- Electron fetch: Unavailable
- Node.js https: HTTP 200 (100 ms)
- Node.js fetch (configured): HTTP 200 (98 ms)

Connecting to https://mobile.events.data.microsoft.com/OneCollector/1.0?cors=true&content-type=application/x-json-stream (Node.js fetch): HTTP 200 (58 ms)
Connecting to https://telemetry.individual.githubcopilot.com/telemetry (Node.js https): HTTP 200 (90 ms)
Connecting to https://default.exp-tas.com/vscode/ab (Node.js fetch): HTTP 200 (108 ms)

Number of system certificates: 363

## Notes

- Active fetcher: Node.js fetch.
- For corporate networks also see: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).