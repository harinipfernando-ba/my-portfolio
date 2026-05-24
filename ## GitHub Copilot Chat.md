## GitHub Copilot Chat

- Extension: 0.47.0 (prod)
- VS Code: 1.119.0 (8b640eef5a6c6089c029249d48efa5c99adf7d51)
- OS: win32 10.0.26200 x64
- GitHub Account: Harini-Fernando

## Network

User Settings:
```json
  "http.systemCertificatesNode": true,
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 4.237.22.34 (6 ms)
- DNS ipv6 Lookup: Error (113 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (1 ms)
- Electron fetch (configured): HTTP 200 (74 ms)
- Node.js https: HTTP 200 (168 ms)
- Node.js fetch: HTTP 200 (58 ms)

Connecting to https://api.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.112.21 (26 ms)
- DNS ipv6 Lookup: Error (27 ms): getaddrinfo ENOTFOUND api.githubcopilot.com
- Proxy URL: None (3 ms)
- Electron fetch (configured): HTTP 200 (877 ms)
- Node.js https: HTTP 200 (757 ms)
- Node.js fetch: HTTP 200 (927 ms)

Connecting to https://copilot-proxy.githubusercontent.com/_ping:
- DNS ipv4 Lookup: 4.237.22.41 (28 ms)
- DNS ipv6 Lookup: Error (30 ms): getaddrinfo ENOTFOUND copilot-proxy.githubusercontent.com
- Proxy URL: None (5 ms)
- Electron fetch (configured): HTTP 200 (176 ms)
- Node.js https: HTTP 200 (181 ms)
- Node.js fetch: HTTP 200 (192 ms)

Connecting to https://mobile.events.data.microsoft.com: HTTP 404 (360 ms)
Connecting to https://dc.services.visualstudio.com: HTTP 404 (351 ms)
Connecting to https://copilot-telemetry.githubusercontent.com/_ping: HTTP 200 (875 ms)
Connecting to https://copilot-telemetry.githubusercontent.com/_ping: HTTP 200 (780 ms)
Connecting to https://default.exp-tas.com: HTTP 400 (240 ms)

Number of system certificates: 76

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).