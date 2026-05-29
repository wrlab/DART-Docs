# Mobile App

This page covers phone-side setup and how to verify streaming.

---

## Goals

You should be able to confirm:

- tracking is started
- the QR-code marker initializes the coordinate frame
- the server receives pose/frames
- the viewer updates

---

## Connect to the server

1. Set the server IP/port in the app
2. Start streaming
3. Confirm the viewer receives updates

---

## Common failure points

- phone and server are not on the same SSID
- wrong IP/port (use the server’s LAN IP)
- firewall blocks ports
- low light / low texture causing tracking instability
