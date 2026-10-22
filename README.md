# 🤖 B.E.N.
homelab est. 2025

**B.E.N.** is the name of my server. I named it after the robot in the movie _Treasure Planet_. In the movie B.E.N. (Bio Electronic Navigator) is a navigator robot who has had his memory module damaged/corrupted. As a result, he gets confused at times. That's how I feel when working on my server. At times, like B.E.N., I'm having a great time, but suddenly I'm confused and unsure what's going on. What is this issue? How did I get here? To quote Ben in the movie: "I've lost my mind. Ha ha! I've lost my mind! You haven't found it, have you?"

## 💻 Hardware

| Part | Model |
|---|---|
| Case | Fractal Design Node 804 |
| CPU | Intel i7-9700 |
| Motherboard | MSI |
| RAM | 16GB DDR4 |
| GPU | EVGA GTX 1070 FTW |
| PSU | EVGA 750W Gold |
| UPS | APC Back-UPS RS 1500G (refurb) |

The UPS talks to Unraid over USB and shuts BEN down safely after 2 minutes on battery.

## 💾 Storage (~44TB usable)

| Role | Drive |
|---|---|
| Parity | 26TB Seagate Exos (refurb) |
| Array | 20TB Seagate Exos X20 (refurb) |
| Array | 20TB Seagate Exos X20 (refurb) |
| Array | 4TB WD Red |
| Cache | 2TB WD Black NVMe |

## 📎 Software

**OS:** Unraid

| Category | Apps |
|---|---|
| Media | Jellyfin (main), Plex (backup) |
| Web access | Nginx Proxy Manager, Tailscale |

## 🤝 Sibling Project
[MiniBot](https://github.com/g-i-n-g-y/MiniBot): (**Planned**) a Proxmox + K3s cluster on Lenovo ThinkCentre Tiny PCs. Small, power efficient, and home to Immich and other services.
