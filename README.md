# Ahmet Boz

I build and run hosting infrastructure. Founder of [VPSPioneer](https://vpspioneer.com), a UK company that sells web hosting on DirectAdmin and KVM VPS on its own Proxmox servers in France/UK/Türkiye.

Most of what I write is the glue that makes a small hosting company run without a night shift: WHMCS modules, Proxmox automation, cloud-init images, Laravel sites and the monitoring around them.

## What I work with

- **Hosting stack:** Proxmox VE, ZFS, cloud-init, DirectAdmin, CloudLinux, nginx, Debian
- **Billing and provisioning:** WHMCS modules and hooks, provisioning APIs, console gateways
- **Web:** PHP, Laravel, WordPress
- **Networking:** IPv4, IPv6, firewalling, mail deliverability (SPF, DKIM, DMARC)

## Open source

Small, finished tools taken from production and cleaned up for anyone running the same stack.

- [whmcs-ga4-consent-mode](https://github.com/ahmetboz/whmcs-ga4-consent-mode): GA4 and Google Ads for the WHMCS client area under Consent Mode v2, denied by default, one banner, purchase and conversion events.
- - [whmcs-hooks](https://github.com/ahmetboz/whmcs-hooks): single-file WHMCS hooks for the things a small host needs: Telegram alerts for orders and tickets, a safeguard against accidental terminations, a promo-code banner in the store cart, a ticket label fix.


More to come: a collection of small WHMCS hooks (Telegram alerts, admin safeguards) and the scripts that build our Proxmox cloud-init templates.

## Elsewhere

- Website: [vpspioneer.com](https://vpspioneer.com)
- Website: [hostingartisan.com](https://hostingartisan.com)
- Guides on hosting, Proxmox, WHMCS and DirectAdmin: [vpspioneer.com/blog](https://vpspioneer.com/blog)
- [LinkedIn](https://www.linkedin.com/in/ahmet-boz-8945ab152/)
- Email: [hello@vpspioneer.com](mailto:hello@vpspioneer.com)

I answer issues and pull requests on the repos above; for hosting questions, the site's ticket system is faster than GitHub.
