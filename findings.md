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

The Night Watch (1642) is Rembrandt's largest and most famous canvas, painted at the height of his Amsterdam reputational peak, midway between his early Leiden-era history pieces (e.g. the allegorical *Music Company*, 1626) and his late masterworks such as *The Sampling Officials* (1662) and *The Jewish Bride* (c. 1665–1669).

Sources: Rijksmuseum collection API record for SK-C-5 ( https://id.rijksmuseum.nl/200107928 ) and collection page https://www.rijksmuseum.nl/en/collection/SK-C-5.

## 2. Product findings with prices (Amazon US, prices read from product pages)

| # | Product | ASIN | Listing title | Current price | Availability | Seller / notes |
|---|---------|------|---------------|---------------|--------------|----------------|
| 1 | ARTCANVAS canvas reproduction | B07CX7N2TJ | ARTCANVAS The Return of the Prodigal Son 1669 Canvas Art Print Stretched Framed Painting Picture Poster Giclee Wall Decor by Rembrandt van Rijn - 26" x 18" (0.75" Deep) | $64.99 | In stock — buy box $64.99 (NEW), Amazon's Choice badge, 4.7★ (93 ratings); free delivery; 30-day refund/replacement | ARTCANVAS (seller_id A2ZTFYORSYOG9); ships from and sold by ARTCANVAS; Made in USA; ready-to-hang with hanging kit; lifetime manufacturer's warranty; archival Epson fade-resistant inks |
| 2 | ARTCANVAS canvas reproduction | B07DJP87L7 | ARTCANVAS The Apostle Paul in Prison 1627 Canvas Art Print Stretched Framed Painting Picture Poster Giclee Wall Decor by Rembrandt van Rijn - 18" x 18" (0.75" Deep) | $59.99 | In stock — buy box $59.99 (NEW); 30-day refund/replacement; free delivery | ARTCANVAS (seller_id A2ZTFYORSYOG9); ships from and sold by ARTCANVAS; Made in USA; ready-to-hang with hanging kit; lifetime manufacturer's warranty; archival Epson fade-resistant inks |
| 3 | MyPuzzle jigsaw puzzle | B0BFVYLRCK | MyPuzzle.com 1000-piece jigsaw puzzle (design by IgorZh / Shutterstock; reference poster approx. 13" × 17.5") | $39.99 | In stock; buy box by MyPuzzle LLC (seller_id A1VIZ6KNY2RFWU); ships from and sold by MyPuzzle LLC; FREE 30-day refund/replacement; free delivery Thu Nov 5 (Prime: tomorrow Nov 1) | MyPuzzle LLC; produced and shipped directly from the US; genuine blue puzzle cardboard ~0.08" thick; 1000 pieces; finished 19.25" × 26.625"; piece size ~1.2" × 0.8"; 25+ years producing board games, playing cards and puzzles |

Notes:
- Prices and availability were read from the product detail pages themselves (not search snippets) at the time of audit.
- Product 1 depicts a different Rembrandt painting (Return of the Prodigal Son, 1669); see the cut rationale below.

## 3. Audit trail

- **Repository:** mcpmark-eval-liuhezi/nightwatch-merch-audit (public; initialized with README.md)
- **Parent issue:** #22 — "Merch audit: The Night Watch" (https://github.com/mcpmark-eval-liuhezi/nightwatch-merch-audit/issues/22)
- **Sub-issues created (one per product examined):**
  - #23 — ARTCANVAS The Return of the Prodigal Son 1669 Canvas Art Print (B07CX7N2TJ)
  - #24 — ARTCANVAS The Apostle Paul in Prison 1627 Canvas Art Print (B07DJP87L7)
  - #25 — MyPuzzle.com 1000-Piece Jigsaw Puzzle (B0BFVYLRCK)
- **Product cut:** ARTCANVAS The Return of the Prodigal Son 1669 Canvas (B07CX7N2TJ, sub-issue #23) — cut from parent #22 because it depicts a *different* painting (Return of the Prodigal Son, 1669) rather than the actual Night Watch, making it the least faithful to the painting under audit. Cut rationale comment posted on issue #22.
- **Sub-issues remaining linked under parent #22:** #24 (ARTCANVAS The Apostle Paul in Prison 1627 Canvas Art Print) and #25 (MyPuzzle.com 1000-Piece Jigsaw Puzzle). Sub-issue #23 was removed from the parent link list.
- **Write-up location:** findings.md at the repo root on branch `audit-findings`, opened as PR into `main` (default branch).
