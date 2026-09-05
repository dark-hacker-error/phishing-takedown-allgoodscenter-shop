# 🚨 Phishing Network Takedown Report

## Target
- **Domain:** allgoodscenter.shop
- **Type:** Fake Walmart / Credit Card Stealer
- **IP:** 104.21.76.18, 172.67.185.18 (Cloudflare)
- **Status:** ACTIVE (Cloudflare 403 - Suspected Phishing)

## Evidence
1. Cloudflare has flagged this as "Suspected Phishing"
2. Part of 120+ fake .shop domains impersonating Walmart
3. WordPress/WooCommerce fake storefront
4. Captures credit card at checkout
5. Auto-generated SSL certificate

## Related Domains (Same Network)
- broadbasket.shop
- dailygoodspark.shop
- homegoodsway.shop
- usefulmarket.shop
- valuegoodspark.shop
- smartbasketplace.shop
- allneedsbay.shop
- allneedsmarket.shop
- allneedsstore.shop
- And 100+ more...

## Technical Details
- **Framework:** WordPress + WooCommerce
- **CDN:** Cloudflare (hides real IP)
- **SSL:** Google Trust Services (WE1) - 90-day auto-generated
- **NS:** elly.ns.cloudflare.com, carter.ns.cloudflare.com

## Reports Needed
- [ ] Cloudflare: abuse@cloudflare.com
- [ ] Google Safe Browsing: https://safebrowsing.google.com/safebrowsing/report_phish/
- [ ] PhishTank: https://phishtank.org/phish_submit.php
- [ ] .shop Registry: https://www.nic.shop/abuse
- [ ] FTC: https://reportfraud.ftc.gov/
- [ ] FBI IC3: https://ic3.gov/

## Date
September 5, 2026

---
*This report is based on public security research and confirmed phishing indicators.*