# Saffron Walden Detailing — Requirements

## Domain
saffronwaldendetailing.co.uk

## Hosting
- Server: 192.168.1.108
- Container: swd-site (nginx:alpine)
- Port: 8035
- Files: /home/sebastian/saffronwaldendetailing.co.uk
- Auto-deploy: cron git pull every 5 minutes

## DNS
- Cloudflare DNS A records → 146.70.181.37 (proxied)
- SSL: Full (Strict) via NPM + Let's Encrypt

## TODO
- [ ] Add real before/after photos
- [ ] Set up Calendly and embed in booking section
- [ ] Google Business Profile link
