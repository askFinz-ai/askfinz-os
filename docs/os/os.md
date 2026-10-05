# askFinz OS: Linux for AI workstations, servers and IoT

A purpose-built Linux distribution that turns any workstation, server or IoT device into a managed askFinz kiosk and a cloud-scheduled compute node.

**Canonical page:** [https://askfinz.com/os](https://askfinz.com/os)

## Key points

### Three jobs

01 Thin client into the workshop. Boot from USB or installed disk, pair the device to your askFinz account, and the Chromium kiosk opens fullscreen on the askFinz workshop.

### What it isn't

askFinz OS is not a general-purpose desktop distro. It does not ship a custom shell or window manager — the Workstation profile is a Chromium kiosk pointed at the askFinz cloud, not GNOME or KDE with our wallpaper.

### One OS. Three shapes

The Workstation profile turns a desktop or laptop into a kiosk + compute node: fullscreen Chromium pointed at the cloud, hardware bridge exposing your GPU and NPU, k3s scheduling your own workloads alongside the kiosk session.

### Images

Every image ships SHA-256 + GPG-signed by askFinz Release Engineering. Disks are LUKS-encrypted with TPM2 auto-unlock; AES-NI keeps the overhead under five per cent.

---

Summary of [https://askfinz.com/os](https://askfinz.com/os), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
