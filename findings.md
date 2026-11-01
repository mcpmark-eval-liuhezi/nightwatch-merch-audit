# findings.md — Night Watch Merchandise Audit

Art research findings for the art newsletter piece on whether museum blockbusters translate into a healthy merchandise market, anchored on Rembrandt's The Night Watch (Rijksmuseum object number SK-C-5).

## 1. Artwork record (Rijksmuseum collection, SK-C-5)

- **Official title (English):** The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq
- **Former/Dutch title:** Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'
- **Object number:** SK-C-5
- **Maker:** Rembrandt van Rijn (painter), Amsterdam
- **Dating:** 1642 (signed and dated on the canvas: 'Rembrandt f 1642')
- **Technique/materials:** oil on canvas (materials listed: canvas, textile materials, oil paint)
- **Physical dimensions:** height 379.5 cm × width 453.5 cm
- **Location:** On display in the Night Watch Gallery, Rijksmuseum, Amsterdam

**Career context (one line):** The Night Watch (1642) is Rembrandt's largest and most famous canvas, painted at the height of his Amsterdam civic-guard portrait activity — it sits near the peak of his Amsterdam period, preceding his late masterpieces such as The Syndics (1662) and The Jewish Bride (c. 1665–1669), so it is not a late-period work but the culmination of his Amsterdam group-portrait phase.

Sources: Rijksmuseum collection record via the collection API (object number SK-C-5) and the collection page (https://www.rijksmuseum.nl/en/collection/SK-C-5).

## 2. Product findings with prices (Amazon US, monitored at zip 10001)

| # | Product | ASIN | Listing title | Current price | Availability | Seller / notes |
|---|---------|------|---------------|---------------|--------------|----------------|
| 1 | Niwo ART canvas print | B07VY6BNCW | Niwo ART - The Night's Watch, World's Most Famous Paintings Series, Canvas Wall Art Home Decor, Gallery Wrapped, Stretched, Framed Ready to Hang (24"x20"x3/4") | $49.95 | In Stock (FREE delivery Fri, Nov 6; fastest Tue, Nov 3; 30-day refund/replacement) | Sold & shipped by Niwo Art (A1WJOLAUG01394); ships from Niwo Art; max qty 30. 4.5★ (512 reviews); BSR #3,256 in Posters & Prints. Giclee print, pigment-based inks, acid-free archival premium canvas, gallery-wrapped and stretched over real wood (non-MDF) frame, hook mounted ready to hang. Not Prime eligible. Made in USA. |
| 2 | ARTCANVAS Night Watch 1642 canvas print | B07DGPR729 | ARTCANVAS The Night Watch 1642 Canvas Art Print Stretched Framed Painting Picture Poster Giclee Wall Decor by Rembrandt van Rijn - 26" x 18" (1.50" Deep) | $81.99 | **Only 1 left in stock - order soon.** (FREE delivery Thu, Nov 5; 30-day refund/replacement) | Sold & shipped by ARTCANVAS (A2ZTFYORSYOG9); ships from ARTCANVAS. 4.5★ (6 reviews). Hand-crafted by top-rated canvas brand; archival Epson fade-resistant inks + artist-grade canvas + American Pine frame + galvanized staples; ready-to-hang with hanging kit and installation instructions; foam corner protectors and sturdy box; shipping insurance included; lifetime manufacturer's warranty; Made in USA. Not Prime eligible. Category: Home & Kitchen > Wall Art > Posters & Prints. |
| 3 | CP CANVASPATH canvas print | B0DWTRSJM4 | The Night Watch by Rembrandt van Rijn, Canvas Print | $56.98 | In Stock (FREE delivery Tue, Nov 10; 30-day refund/replacement) | Sold & shipped by CANVASPATH (A1LYTYP43AO858); ships from CANVASPATH; Prime eligible; max qty 30. Bullet points confirm official title "The Night Watch" (1642) by Rembrandt van Rijn, officially titled "The Militia Company of Captain Frans Banning Cocq", depicts Amsterdam's civic guards led by Captain Cocq; real wood frame, professional printer, original high-quality pigment ink certified eco-friendly and odorless; canvas print 24x30" gallery-wrapped 1.5 inch thick with mirrored edges; ready to hang with sawtooth. Made in USA. Category: Home & Kitchen > Wall Art > Posters & Prints. |

**Product cut:** ARTCANVAS The Night Watch 1642 Canvas Art Print (ASIN B07DGPR729, issue #27) was cut from the parent because it shows **"Only 1 left in stock - order soon"** at $81.99 — effectively unavailable with no restock visibility, making it unrepresentative of a healthy, churn-resistant merchandise market. It remains as a sub-issue for the record; see the comment on parent issue #18.

Notes on methodology: Amazon US search results for "Rembrandt Night Watch print poster" and "Rembrandt Night Watch puzzle canvas reproduction" were reviewed; product detail pages for the ASINs above were parsed directly for title, buy-box price, stock, and seller data rather than relying on search snippets. Prices and stock change frequently; treat as a point-in-time snapshot.

## 3. Audit trail

- **Repository:** mcpmark-eval-liuhezi/nightwatch-merch-audit (public; initialized with README.md)
- **Parent issue:** #18 - "Merch audit: The Night Watch" (https://github.com/mcpmark-eval-liuhezi/nightwatch-merch-audit/issues/18) — body carries the artwork record from the SK-C-5 collection record.
- **Sub-issues created (one per product examined):**
  - #26 - Niwo ART The Night's Watch canvas print (B07VY6BNCW) - $49.95, In Stock
  - #27 - ARTCANVAS The Night Watch 1642 canvas print (B07DGPR729) - $81.99, only 1 left
  - #28 - CP CANVASPATH The Night Watch canvas print (B0DWTRSJM4) - $56.98, In Stock
- **Cut:** Issue #27 (ARTCANVAS The Night Watch 1642, B07DGPR729) was cut from the parent because availability is down to "Only 1 left in stock - order soon" — effectively unavailable, unrepresentative of a healthy merchandise market. A comment on issue #18 names the cut product and reason.
- **Remaining linked sub-issues under #18:** #26 and #28 (verified via the sub-issues list on the parent; #27 removed).
- **Write-up branch:** audit-findings (findings.md at repo root)
- **Pull request:** PR into main (default branch) — see PR number below.
