---
hide:
  - toc
---

<style>
  .hero-container {
    position: relative;
    width: 100%;
    height: 62vh;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    background-color: #000;
    box-shadow: 0 15px 35px rgba(0,0,0,0.4);
    margin-bottom: 30px;
  }
  .bg-video {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    transform: translateX(-50%) translateY(-50%);
    object-fit: cover;
    opacity: 0.35;
    z-index: 0;
  }
  .hero-content {
    position: relative;
    z-index: 1;
    text-align: center;
    color: white;
    padding: 20px;
  }
  .hero-content img {
    width: 120px;
    margin-bottom: 14px;
    filter: drop-shadow(0px 4px 6px rgba(0,0,0,0.5));
  }
  .hero-content h1 {
    font-size: 3.2rem;
    font-weight: 900;
    margin: 0;
    color: white !important;
    text-shadow: 2px 2px 10px rgba(0,0,0,0.85);
  }
  .hero-content p {
    font-size: 1.05rem;
    max-width: 900px;
    margin: 14px auto 26px auto;
    color: #e6e6e6;
    text-shadow: 1px 1px 6px rgba(0,0,0,0.85);
  }
</style>

<div class="hero-container">
  <video class="bg-video" autoplay loop muted playsinline preload="metadata"
         poster="assets/1024.png">
    <source src="assets/Scan_MeetingRoom2_WXR.mp4" type="video/mp4">
  </video>

  <div class="hero-content">
    <img src="assets/1024.png" alt="DART Logo">
    <h1>DART</h1>
    <p><b>Open-source indoor 3D scanning drone</b><br/>
    Build with off-the-shelf UAV + smartphone payload, and monitor/replay scans in a web viewer.</p>

    <div>
      <a href="getting-started/" class="md-button md-button--primary" style="font-size: 1.05rem; padding: 10px 18px;">🚀 Start Here</a>
      <a href="hardware/" class="md-button" style="font-size: 1.05rem; padding: 10px 18px;">🧩 Build Hardware</a>
      <a href="software/" class="md-button" style="font-size: 1.05rem; padding: 10px 18px;">💻 Setup Software</a>
      <a href="https://github.com/wrlab/DART" target="_blank" class="md-button". style="font-size: 1.05rem; padding: 10px 18px;">🌐 GitHub</a>
    </div>
  </div>
</div>

!!! warning "Safety first"
    DART involves operating drones indoors. Always follow local laws and safety rules.
    Keep a safety perimeter and never fly near people.

---

## What you will build

<div class="grid cards" markdown="1">
-   **Phone-on-drone payload**  
    Print & assemble a lightweight mount
    ![Mount](assets/mount.png){ style="display:block; margin: 10px auto 0 auto; width: 100%; max-width: 520px; height: 240px; object-fit: contain; border-radius: 10px;" }

-   **QR marker**  
    Print and place the marker before the first scan  
    ![QR Marker](assets/qr_marker.png){ style="width: 100%; max-height: 260px; object-fit: contain; border-radius: 10px;" }

-   **Tablet controller UI**  
    Monitor scan status and switch modes safely  
    ![Controller UI](assets/controller_ui.png){ style="display:block; margin: 10px auto 0 auto; width: 100%; max-width: 520px; height: 240px; object-fit: contain; border-radius: 10px;" }

-   **Web monitoring & replay**  
    Live view + replay with synchronized video
    ![WXR](assets/reconstruction_wxr.png){ style="display:block; margin: 10px auto 0 auto; width: 100%; max-width: 520px; height: 240px; object-fit: cover; border-radius: 10px;" }
</div>

---

## Recommended build path

1. **Read the “Start Here” page** (requirements + first run) → **Getting Started**
2. **Build the mount** and complete pre-flight checks → **Hardware**
3. **Run the server/viewer**, connect phone + controller, and perform your first scan → **Software → Operation**

---

## Project status

- **Docs-first**: This site prioritizes reproducible build steps and “first success”.
- **Known-good baseline**: DJI Phantom 4 Pro V2.0 + iPhone 15 Pro (from our reference build).
- **Help wanted**: more tested configurations, mount variants, and troubleshooting cases.

---

## Quick links

<div class="grid cards" markdown="1">
- **Getting Started**  
  Requirements, demo replay, quickstart, first scan checklist.  
  [Open →](getting-started/index.md)

- **Hardware**  
  BOM, printing, mount assembly, integration, safety.  
  [Open →](hardware/)

- **Software**  
  Installation, configuration, viewer, sessions & logs.  
  [Open →](software/)
</div>
