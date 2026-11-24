# Dummy / fake data in the demo store (change before going live)

Everything below is made up for the client demo. Replace each item with the client's real details.

## Brand and contact
- Store name **Chandni Silver** and the moon logo (logo.svg, icon-512.png)
- Brand story: "started in 1985", "two-man karigar workshop", "second generation", "15,000 families"
- Address: Shop 12, Silver Market, Saddar, Karachi, and the Google map pin
- Opening hours: Mon–Sat, 11 am – 9 pm
- WhatsApp number 923001234567 (changeable in Admin)
- Social links (Facebook, Instagram, TikTok, YouTube) only open the main websites

## Prices and settings (all changeable in Admin)
- Silver rate Rs 6,500 per tola
- Delivery Rs 250, free above Rs 10,000
- Discount code EID10 = 10% off (no minimum), FLAT500 = Rs 500 off above Rs 8,000 (FLAT500 is set in code)
- Engraving charge Rs 800 (set in code)
- Silver rate history for the last 7 days (dummy numbers 6,380 → 6,500)
- Gift box Rs 300
- Finish charges: Rhodium +Rs 400, Gold plated +Rs 900 (set in code)
- Admin PIN 1234

## Products
- All 23 product names, weights, making charges, descriptions, sizes, stock counts and sale % are samples
- Product photos are free Unsplash photos, not the client's pieces
- 3 aqeeq / stone rings, 3 Islamic pieces and the name pendant have drawings only (no photo)
- Product codes (SKU) are generated automatically

## Promises and policies (client must confirm)
- Certificate of authenticity with every order
- Free lifetime replating
- 6-month warranty on stones, clasps and locks
- Buyback: 80% of silver value in cash, or 100% as exchange credit
- Skin-friendly / nickel-free claim
- Engraving: up to 12 letters, 5–7 extra days, no exchange
- Video call time slots (11 am – 9 pm)
- Custom order budget ranges
- 7-day exchange
- Delivery times: Karachi 1–2 days, Lahore/Islamabad/Rawalpindi/Hyderabad 2–3, others 3–5
- Shipping, Return, Privacy and Terms text
- FAQ answers and the 3 Silver journal articles
- "Natural aqeeq" claim

## Demo-only behaviour
- Orders, reviews, stock and settings save only in the visitor's own browser
- The admin PIN lock is not real security; the real store needs a proper login (Supabase)

## To switch on later
- Facebook Pixel and Google Analytics: paste the client's IDs in `window.CS_TRACK={pixel:'',ga:''}` at the top of index.html
- Google Search Console: add the site, verify, then submit sitemap.xml
- Urdu translation covers the main page text; product names, descriptions, FAQ answers and articles stay in English. A native reader should check the Urdu.
- Links in sitemap.xml, robots.txt, canonical and link preview point to the GitHub Pages address; change them when the site moves to the client's domain
