# Configuration

DART usually needs configuration in three places:

1) **Server / viewer**
2) **Mobile app**
3) **Controller**

---

## Minimal configuration checklist

- [ ] Server IP address
- [ ] Viewer URL/port
- [ ] Data/session output directory
- [ ] Streaming settings (fps/bitrate)
- [ ] Safety settings (battery threshold, return-to-home)

---

## Suggested config table (fill in)

| Setting | Where | Example |
|---|---|---|
| SERVER_IP | phone/controller | `192.168.0.10` |
| VIEWER_PORT | server | `8080` |
| STREAM_FPS | phone | `30` |
| VIDEO_BITRATE | phone | `4M` |
| SESSION_DIR | server | `./sessions/` |

!!! tip "One source of truth"
    Prefer a single `.env` or `config.yaml` shared by all components.
