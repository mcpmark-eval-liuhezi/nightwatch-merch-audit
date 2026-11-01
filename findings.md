# findings.md — Night Watch Merchandise Audit

Art research findings for the art newsletter piece on whether museum blockbusters translate into a healthy merchandise market, anchored on Rembrandt's The Night Watch (Rijksmuseum object number SK-C-5).

## 1. Artwork record (Rijksmuseum collection, SK-C-5)

- **Official title (English):** The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq
- **Former/Dutch title:** Het korporaalschap van kapitein Frans Banninck Cocq en luitenant Willem van Ruytenburch, bekend als de 'Nachtwacht'
- **Object number:** SK-C-5
- **Maker:** Rembrandt van Rijn (painter), Amsterdam
- **Dating:** 1642 (signed and dated on the canvas: 'Rembrandt f 1642')
- **Technique/materials:** oil on canvas (materials listed: canvas, textile materials, oil paint)
- **Physical dimensions:** height 379.5 cm x width 453.5 cm
- **Location:** On display in the Night Watch Gallery, Rijksmuseum, Amsterdam

**Career context (one line):** The Night Watch (1642) is Rembrandt's largest and most famous canvas, painted at the height of his Amsterdam civic-guard portrait activity - it precedes his late masterpieces such as The Syndics (1662) and The Jewish Bride (c. 1665-1669), so it sits near the peak of his Amsterdam period rather than at the end of his career.

Sources: Rijksmuseum collection record via the collection API (object number SK-C-5) and the collection page (https://www.rijksmuseum.nl/en/collection/SK-C-5).

## 2. Product findings with prices (Amazon US, monitored at zip 10001)

| # | Product | ASIN | Listing title | Current price | Availability | Seller / notes |
|---|---------|------|---------------|---------------|--------------|----------------|
| 1 | ARTCANVAS Night Watch canvas print | B07CX7N2TJ | ARTCANVAS The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq, 1642 - Oil on Canvas Print by Rembrandt van Rijn - 24x36 inch (60x90cm) Unframe-style | $64.99 | Only 2 left in stock - order soon. | Sold & shipped by ARTCANVAS (A2ZTFYORSYOG9); Amazon's Choice badge. Ready-to-hang canvas with hanging kit; archival Epson fade-resistant inks on artist-grade canvas with American Pine frame; Made in the USA; lifetime manufacturer's warranty; 30-day refund/replacement. FREE delivery. Category: Home & Kitchen > Wall Art > Posters & Prints. |
| 2 | Aether Puzzles 1000-piece jigsaw (CUT) | B0F1VB8HRB | Premium 1,000 Piece Jigsaw Puzzles for Adults - Aether Puzzles - Gift Edition | $29.99 (New); $20.78 (Used - Like New) | Only 10 left in stock - order soon. | Sold by Aether Puzzles (A34EJ4YB2YPPGP), Amazon fulfilled; Prime eligible. 1000-piece matte soft-touch glare-free finish; gold foil-stamped linen box with fabric storage bag and art print; made in the USA; never AI-generated. **Cut: listing bullets reference Van Gogh landscapes, not the Night Watch** - least faithful to the actual painting of SK-C-5. |
| 3 | ARTCANVAS Return of the Prodigal Son 1669 canvas | B07DJRZFRJ | ARTCANVAS The Return of the Prodigal Son 1669 Canvas Art Print Stretched Framed Painting Picture Poster Giclee Wall Decor by Rembrandt van Rijn - 18" x 12" (0.75" Deep) | $64.99 | Only 1 left in stock - order soon. | Sold & shipped by ARTCANVAS (A2ZTFYORSYOG9). Ready-to-hang canvas with hanging kit; archival Epson fade-resistant inks on artist-grade canvas with American Pine frame; Made in the USA; lifetime manufacturer's warranty; 30-day refund/replacement. FREE delivery. Category: Home & Kitchen > Wall Art > Posters & Prints. Note: this is Rembrandt but a different subject (Return of the Prodigal Son, 1669) rather than the Night Watch itself. |

Notes on methodology: search results on Amazon US for "Rembrandt Night Watch print poster" (116 results) and "Rembrandt Night Watch puzzle canvas reproduction" (204 results) were reviewed; product detail pages for the ASINs above were parsed directly for title, price, buy-box stock, and seller data rather than relying on search snippets. Prices and stock change frequently; treat as a point-in-time snapshot.

## 3. Audit trail

- **Repository:** mcpmark-eval-liuhezi/nightwatch-merch-audit (public; initialized with README.md)
- **Parent issue:** #18 - "Merch audit: The Night Watch" (https://github.com/mcpmark-eval-liuhezi/nightwatch-merch-audit/issues/18) - body carries the artwork record from the SK-C-5 collection record.
- **Sub-issues created (one per product examined):**
  - #19 - ARTCANVAS Night Watch canvas print (B07CX7N2TJ) - $64.99, 2 left
  - #20 - Aether Puzzles 1000-piece jigsaw (B0F1VB8HRB) - $29.99, 10 left
  - #21 - ARTCANVAS Return of Prodigal Son canvas (B07DJRZFRJ) - $64.99, 1 left
- **Cut:** Issue #20 (Aether Puzzles 1000-piece jigsaw, B0F1VB8HRB) was cut from the parent because its listing bullets describe "Van Gogh's landscapes" as the artwork used - it is not actually a Night Watch product, making it the least faithful to the actual painting of SK-C-5. A comment naming the cut product and reason was added on issue #18.
- **Remaining linked sub-issues under #18:** #19 and #21 (verified via the sub-issues list on the parent).
- **Write-up branch:** audit-findings (existing branch; findings.md placed at repo root).
- **Pull request:** PR into main (default branch) - see PR number below.
