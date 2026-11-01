# Night Watch Merchandise Audit — findings.md

Art newsletter research trail: Rijksmuseum SK-C-5 (Rembrandt's Night Watch) artwork record plus Amazon merchandise market findings. This write-up was produced on branch `audit-findings` and PR'd into `main`.

## 1. Artwork record (Rijksmuseum collection record, SK-C-5)

- **Official title (EN):** The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq
- **Object number:** SK-C-5
- **Dating:** 1642 (signed and dated on the canvas: 'Rembrandt f 1642')
- **Maker:** Rembrandt van Rijn (painter), Amsterdam
- **Type:** Painting
- **Technique / materials:** Oil on canvas (canvas; oil paint; textile materials)
- **Physical description:** oil on canvas
- **Dimensions:** height 379.5 cm × width 453.5 cm (weight 337 kg / 170 kg)
- **Location:** On display in the Night Watch Gallery, Rijksmuseum

### Career context — one-line note

The Night Watch (1642) is Rembrandt's largest and most famous canvas, painted at the height of his Amsterdam reputational peak, midway between his early history pieces (e.g. the allegorical Music Company, 1626) and his late masterworks such as The Sampling Officials (1662) and The Jewish Bride (c. 1665–1669).

Sources: Rijksmuseum collection API record for SK-C-5 (https://id.rijksmuseum.nl/200107928) and collection page https://www.rijksmuseum.nl/en/collection/SK-C-5.

## 2. Product findings with prices (Amazon US, prices read from product pages)

| # | Product | ASIN | Listing title | Current price | Availability | Seller / notes |
|---|---------|------|---------------|---------------|--------------|----------------|
| 1 | Infinite Photographs jigsaw puzzle | B0BMQQQ76N | The Night Watch by Rembrandt, 1000 piece Jigsaw Puzzle for Adults \| Dramatic lighting, expressive figures and intricate clothing give art lovers plenty to explore (INFINITE PHOTOGRAPHS brand) | $39.99 | **Only 1 left in stock - order soon.** FREE delivery Thursday Nov 5; Prime members Tue Nov 3. FREE 30-day refund/replacement. | Sold and shipped by Historic Photographs and Maps (seller ID A3U2E3FF9HHX2B); Amazon-fulfilled. 2 mm thick cardboard pieces, matte finish; reference poster included; completed puzzle 70 × 50 cm; illustrated rectangular ivory puzzle box. Category: Toys & Games > Jigsaw Puzzles. |
| 2 | wall26 Nachtwacht canvas print | B00U1AHIZE | Nachtwacht (or The Night Watch) by Rembrandt Famous Fine Art Reproduction World Famous Painting Replica on Ped Frame Print Wood Framed - Canvas Art Wall Art - 24" x 24" | $38.49 | **In Stock.** FREE delivery Wednesday Nov 4; 30-day refund/replacement. Not Prime eligible per buybox data. | Sold and shipped by wall26 (seller ID A1ZGY3RE5LH1AU); ships from wall26; max quantity 30. Brand: wall26. 1.5" stretcher bars; Wood frame; 24"L × 24"W; Square; Landscape; Material Wood; Mounting Type Wall Mount; Paint Type Watercolor; Paper Finish Semi-Gloss; Pattern Printed; Product Style Fine Art; Theme Holidays; UPC 711717754215. Customer reviews 5.0 out of 5 stars (11 reviews). Best Sellers Rank #468,583 in Posters & Prints. |
| 3 | Crossroads Home Decor framed print | B097RTV2JM | Crossroads Home Décor The Night's Watch by Rembrandt ... (Crossroads Home Decor brand; framed print, 14"x11" wall display) | $36.99 | **Only 14 left in stock - order soon.** FREE delivery Thursday Nov 5; 30-day refund/replacement. | Sold and shipped by Crossroads_Home_Decor (seller ID A1L7X7SELZ1Z4K); ships from Crossroads_Home_Decor. Made in USA — each print reproduced and framed to order by an American family business; arrival as museum-quality Rembrandt framed print. Bullet points describe it as a 14"x11" wall display in Barnwood, Charcoal, Black, or Walnut, with warm chiaroscuro of amber, red and deep shadow; titled in full for the militia of captain Frans Banninck Cocq; painted in 1642 by Rembrandt van Rijn; faithful to the original in the Rijksmuseum in Amsterdam. |

Notes:
- Prices and availability were read from the product detail pages themselves (Amazon US, ASIN lookups), not search snippets.
- Product 1 (puzzle) is an indirect engagement with the painting rather than a direct reproduction; the listing itself notes actual colors may slightly differ from pictures due to monitor display issues.
- Product 2 is a wood-framed canvas print; product 3 is a smaller 14×11" framed print rather than a large-format reproduction.

## 3. Audit trail

- **Repository:** mcpmark-eval-liuhezi/nightwatch-merch-audit (public; initialized with README.md)
- **Parent issue:** #29 — "Merch audit: The Night Watch" (https://github.com/mcpmark-eval-liuhezi/nightwatch-merch-audit/issues/29)
- **Sub-issues created (one per product examined):**
  - #32 — Infinite Photographs The Night Watch 1000-Piece Jigsaw Puzzle (B0BMQQQ76N) - $39.99, Only 1 left in stock
  - #33 — wall26 Nachtwacht Canvas Print 24x24 Wood Framed (B00U1AHIZE) - $38.49, In Stock
  - #34 — Crossroads Home Decor The Night Watch Framed Print 14x11 (B097RTV2JM) - $36.99, Only 14 left in stock
- **Product cut:** Infinite Photographs The Night Watch 1000-Piece Jigsaw Puzzle (B0BMQQQ76N) — sub-issue #32 — cut from parent #29 because availability is critically low (buy box: "Only 1 left in stock - order soon" at $39.99 from third-party seller Historic Photographs and Maps, Amazon-fulfilled), making it effectively near-unavailable beyond a single unit; as a 1000-piece puzzle it is also an indirect engagement with the painting rather than a direct reproduction, and the listing notes colors may differ from pictures due to monitor display issues. Cut rationale comment posted on issue #29.
- **Sub-issues remaining linked under parent #29:** #33 (wall26 Nachtwacht canvas print, B00U1AHIZE, $38.49, In Stock) and #34 (Crossroads Home Decor Night Watch framed print, B097RTV2JM, $36.99, Only 14 left in stock). Sub-issue #32 was removed from the parent link list.
- **Write-up location:** findings.md at the repo root on branch `audit-findings`, opened as PR into `main` (default branch).
