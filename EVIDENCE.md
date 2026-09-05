# Phishing Evidence

## 1. Cloudflare Challenge Page
The site returns HTTP 403 with Cloudflare's "Suspected Phishing" challenge page.

## 2. robots.txt Reveals WooCommerce
```
Disallow: /wp-content/uploads/wc-logs/
Disallow: /wp-content/uploads/woocommerce_transient_files/
Disallow: /wp-content/uploads/woocommerce_uploads/
Disallow: /*?add-to-cart=
```

## 3. SSL Certificate
- Issuer: Google Trust Services (WE1)
- Valid: Jul 22, 2026 → Oct 20, 2026 (90 days)
- Auto-generated for phishing site

## 4. DNS Records
- A: 104.21.76.18, 172.67.185.18 (Cloudflare)
- NS: elly.ns.cloudflare.com, carter.ns.cloudflare.com
- MX: route1-3.mx.cloudflare.net

## 5. Path Analysis
- /login → 302 (redirect)
- /checkout → 301 (redirect)
- /cart → 301 (redirect)
- /.env → 403 (blocked)

---
*Evidence collected via nmap, dig, curl, openssl*