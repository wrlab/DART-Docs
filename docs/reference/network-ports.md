# Network Ports

Document your actual ports here.

| Component | Protocol | Port | Notes |
|---|---|---:|---|
| Viewer | HTTP/WS | 8080 | UI + control |
| Streaming | WebRTC | TBD | pose + RGB-D |
| Telemetry | WS | TBD | status/health |

!!! tip "Avoid magic numbers"
    Keep ports in a single config file and reference it here.
