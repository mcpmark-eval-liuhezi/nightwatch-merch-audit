# Night Watch Merchandise Audit — findings.md

Art newsletter research trail: Rijksmuseum SK-C-5 (Rembrandt's Night Watch) artwork record plus Amazon merchandise market findings. This write-up was produced on branch `audit-findings` and PR'd into `main`.

## 1. Artwork record (Rijksmuseum collection record, SK-C-5)

- **Official title (EN):** The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq (collection record titles: *Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'*; also *Officers and other civic guardsmen of District II in Amsterdam, under the command of Captain Frans Banninck Cocq and Lieutenant Willem van Ruytenburch, known as 'The Night Watch'*)
- **Object number:** SK-C-5
- **Dating:** 1642 (signed and dated on the canvas: 'Rembrandt f 1642')
- **Maker:** Rembrandt van Rijn (painter), Amsterdam
- **Type:** Painting
- **Technique / materials:** Oil on canvas (catalogued as textile materials / canvas / oil paint; physical description: oil on canvas)
- **Dimensions:** height 379.5 cm × width 453.5 cm (weight 337 kg / 170 kg)
- **Location:** On display in the Night Watch Gallery, Rijksmuseum, Amsterdam

### Career context — one-line note

The Night Watch (1642) is Rembrandt's largest and most famous canvas, painted at the height of his Amsterdam reputational peak, midway between his early history pieces (e.g. the allegorical Music Company, 1626) and his late masterworks such as The Sampling Officials (1662) and The Jewish Bride (c. 1665–1669).

Sources: Rijksmuseum collection API record for SK-C-5 (https://id.rijksmuseum.nl/200107928) and collection page https://www.rijksmuseum.nl/en/collection/SK-C-5.

## 2. Product findings with prices (Amazon US, prices read from product pages)

| # | Product | ASIN | Listing title | Current price | Availability | Seller / notes |
|---|---------|------|---------------|---------------|--------------|----------------|
| 1 | ARTCANVAS Night Watch canvas | B07DJMXQ1Z | ARTCANVAS The Night Watch 1642 Canvas Art Print Stretched Framed Painting Picture Poster Giclee Wall Decor by Rembrandt van Rijn - 40" x 26" (0.75" Deep) | $59.99 | Only 2 left in stock - order soon | Seller: ARTCANVAS (A2ZTFYORSYOG9); ships from ARTCANVAS; archival Epson fade-resistant inks + artist-grade canvas + American Pine frame; ready-to-hang with hanging kit; Made in USA; lifetime manufacturer's warranty; 30-day refund/replacement; FREE delivery Monday Nov 9; not Prime eligible in buy box; Amazon's Choice badge. Category: Home & Kitchen > Wall Art > Posters & Prints. |
| 2 | CP CANVASPATH gold-framed print | B0DWV4FGTD | The Night Watch by Rembrandt van Rijn, Gold-Framed Art | $75.98 | In Stock | Seller: CANVASPATH (A1LYTYP43AO858); shipped from CANVASPATH; made in USA, ready to hang; gold framed size 18x22", image size 16x20"; professional printer with original high-quality pigment ink, certified eco-friendly and odorless; museum-quality giclée on acid-free cotton-base canvas; max quantity 30; not Prime eligible in buy box; FREE delivery from Nov 5; 30-day refund/replacement. BSR: #470,891 in Home & Kitchen; #7,375 in Posters & Prints. |
| 3 | Bayby 1000-piece puzzle | B0GYJT7MTK | Bayby 1000 Pieces Jigsaw Puzzle for Adults, The Night Watch by Rembrandt Van Rijn, Premium Pla... | $25.99 | Only 3 left in stock - order soon | Seller: BAYBY PUZZLES (A3I6RMW63I61TA); ships from Amazon; Prime eligible; 1000-piece jigsaw, plastic pieces (odorless, bend-resistant, precision-cut click fit); completed size approx. 29.7 x 19.5 in (75x50cm), ideal for framing after completion; age 14 years and up; included components: Poster + Puzzle Piece; water resistant; max quantity 3; 30-day refund/replacement. BSR: #751,131 in Toys & Games; #31,230 in Jigsaw Puzzles. Category: Toys & Games > Puzzles > Jigsaw Puzzles. |

Notes:
- Prices and availability were read from the product detail pages themselves (Amazon US, ASIN lookups), not search snippets.
- Products 1 and 2 are direct giclée/canvas reproductions of the painting; product 3 is an indirect engagement (a jigsaw puzzle featuring the composition).

## 3. Audit trail

- **Repository:** mcpmark-eval-liuhezi/nightwatch-merch-audit (public; initialized with README.md)
- **Parent issue:** #29 — "Merch audit: The Night Watch" (https://github.com/mcpmark-eval-liuhezi/nightwatch-merch-audit/issues/29)
- **Sub-issues created (one per product examined this session):**
  - #35 — ARTCANVAS The Night Watch 1642 Canvas Art Print Stretched Framed Painting Picture Poster Giclee Wall Decor by Rembrandt van Rijn - 40" x 26" (0.75" Deep) (B07DJMXQ1Z) - $59.99, Only 2 left in stock
  - #36 — CP CANVASPATH The Night Watch by Rembrandt van Rijn, Gold-Framed Art (B0DWV4FGTD) - $75.98, In Stock
  - #37 — Bayby 1000 Pieces Jigsaw Puzzle for Adults, The Night Watch by Rembrandt Van Rijn (B0GYJT7MTK) - $25.99, Only 3 left in stock
- **Product cut:** Bayby 1000 Pieces Jigsaw Puzzle for Adults, The Night Watch by Rembrandt Van Rijn (ASIN B0GYJT7MTK) — sub-issue #37 — cut from parent #29 linkage because (1) it is least faithful to the actual painting as art merchandise — a 1000-piece jigsaw puzzle rather than a reproduction of The Night Watch as a painting/canvas, with only an HD-printed image on plastic pieces; and (2) availability is constrained — only 3 left in stock with a max quantity of 3, effectively near-unavailable beyond the last units. Cut rationale comment posted on issue #29.
- **Sub-issues remaining linked under parent #29:** #35 (ARTCANVAS Night Watch 1642 canvas, B07DJMXQ1Z, $59.99, 2 left) and #36 (CP CANVASPATH gold-framed Night Watch, B0DWV4FGTD, $75.98, In Stock). Sub-issue #37 (Bayby puzzle) was cuts from the parent link list per the cut rationale comment on issue #29.
- **Write-up location:** findings.md at the repo root on branch `audit-findings`, opened as PR into `main` (default branch).
