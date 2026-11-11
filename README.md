# Aleph Void QEMU Manager

[![Sponsor Aleph Void](https://img.shields.io/badge/Sponsor-Aleph%20Void-EA4AAA?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/aleph-void)

**QEMU, without the command line — a desktop manager for QEMU virtual machines on macOS, Linux and Windows.**

QEMU Manager creates, configures and runs QEMU virtual machines from a Proxmox-style hardware list. It supports 18 guest architectures, UEFI and TPM 2.0, snapshots that include memory, full and linked clones, OVA/OVF import and export, PCI and USB passthrough, shared folders and an embedded noVNC console, and it always shows the exact QEMU command line it runs.

This repository hosts the source for the QEMU Manager marketing site at [qemu-manager.alephvoid.com](https://qemu-manager.alephvoid.com), and its issue tracker is the place to get support for the app.

## Links

- Website: <https://qemu-manager.alephvoid.com>
- Features: <https://qemu-manager.alephvoid.com/#features>
- How it works: <https://qemu-manager.alephvoid.com/#how-it-works>
- Requirements: <https://qemu-manager.alephvoid.com/#requirements>
- Download: <https://qemu-manager.alephvoid.com/#install>
- FAQ: <https://qemu-manager.alephvoid.com/#faq>
- Support: <https://qemu-manager.alephvoid.com/support.html>
- Privacy policy: <https://qemu-manager.alephvoid.com/privacy.html>

## Reporting Bugs

Found a bug or have a feature request? File it on our [GitHub issue tracker](https://github.com/aleph-void/qemu-manager.alephvoid.com/issues). Include your host OS and CPU, QEMU version, app version, the guest architecture, the VM's QEMU command line and the QEMU log, plus steps to reproduce.

Don't post license keys in issues. For purchase or license problems, email <support@alephvoid.com>.

## Development

The site is static HTML and CSS with no build step; `styles.css` follows the shared Aleph Void palette used by the other product sites. Preview it locally with any static server:

```sh
python3 -m http.server 8000
```

Pushing to `main` deploys to the `gh-pages` branch via `.github/workflows/deploy.yml`.

---

QEMU is a trademark of Fabrice Bellard. QEMU Manager is an independent project by [Aleph Void LLC](https://alephvoid.com), not affiliated with the QEMU project.
