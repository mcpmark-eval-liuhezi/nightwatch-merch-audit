# Findings: Night Watch Merchandise Market Audit

**Project:** nightwatch-merch-audit · **Object:** Rembrandt's *The Night Watch* (Rijksmuseum SK-C-5) — official title *The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq* · **Source:** Rijksmuseum collection record (SK-C-5) + Amazon US product pages (data pulled 2026-10-30)

## 1. Artwork record (Rijksmuseum collection)

| Field | Value |
|---|---|
| Title | *The Night Watch Militia Company of District II under the Command of Captain Frans Banninck Cocq* (also known as "De Nachtwacht" / "The Night Watch") |
| Object number | SK-C-5 |
| Maker | Rembrandt van Rijn (painter, Amsterdam) |
| Dating | 1642 (signed and dated "Rembrandt f 1642") |
| Type | Painting |
| Physical characteristics | Oil on canvas |
| Dimensions | height 379.5 cm x width 453.5 cm (weight 337 kg / 170 kg) |
| Current location | On display in the Night Watch Gallery, Rijksmuseum, Amsterdam |
| Collection URL | https://www.rijksmuseum.nl/en/collection/SK-C-5 |

**Position in Rembrandt's career:** the Night Watch (1642) is Rembrandt's largest and most famous canvas and the lynchpin of his Amsterdam peak. It follows the late-1630s civic-guard commissions same collection e.g. *The Stone Bridge* (1638) and *An Oriental* (1635), and the Portrait of Haesje Jacobsdr van Cleyburg (1634), and precedes the monumental late masterpieces still in the museum — *The Syndics* (1662) and *The Jewish Bride* (c. 1665-1669). It is not an early or it late work: it is the single-pair肖像 breakthrough (captain Cocq ordering the company to march; the girl with the dead chicken as the mascot; light used to focus attention) that defines the painting as a turning point in Dutch group-portrait history.

## 2. Amazon product findings (US, prices at time of check)

| # | Product (title) | ASIN | Price | Availability | Seller / source |
|---|---|---|---|---|---|
| 1 | ARTCANVAS The Night Watch 1642 Canvas Art Print, Stretched Framed Giclee Wall Decor by Rembrandt van Rijn - 40" x 26" (0.75" Deep) | B07DFQDYND | **$91.99** | Only 2 left in stock - order soon | ARTCANVAS (seller); free delivery by Fri Nov 6; 30-day refund/replacement |
| 2 | The Night Watch Rembrandt Barnwood Wood Framed Print - Painting Replica with Ped, 16"x16" (Barnwood, Charcoal, Black or Walnut) | B097RRYTP4 | **$36.96** | Only 14 left in stock - order soon | Crossroads Home Decor; free delivery Thu Nov 5; 30-day refund/replacement |
| 3 | The Night Watch by Rembrandt, 1000 Piece Jigsaw Puzzle for Adults (2 mm thick pieces, reference poster included) | B0BMQQQ76N | **$39.99** | Only 1 left in stock - order soon | INFINITE PHOTOGRAPHS via Historic Photographs and Maps (Amazon-fulfilled); Prime eligible; free delivery Sat Nov 7; free 30-day refund/replacement |
| 4 | ~~CUT~~ Nachtwacht (or The Night Watch) by Rembrandt Famous Fine Art Reproduction - Wood Framed Canvas Art Wall Art - 16" x 16" | B00U1AH89K | $32.99 | In Stock (hanging kit) | wall26 — cut: least faithful to the actual oil on canvas painting (see section 3) |

**Category coverage:** canvas reproductions / giclée wall art (#1, #2) and a puzzle (#3) - covering the two required product kinds (prints/posters and puzzles or canvas reproductions).

## 3. Audit trail

- **Purpose:** track the research trail for the art-newsletter piece on whether museum blockbusters translate into a healthy merchandise market.
- **Products examined:** 4 Amazon US listings, all pulled from the product pages themselves (not search snippets): #1 ARTCANVAS canvas, #2 Crossroads barnwood framed print, #3 INFINITE PHOTOGRAPHS 1000-piece puzzle, #4 wall26 Nachtwacht print.
- **Product cut:** #4 - "Nachtwacht (or The Night Watch) by Rembrandt" (ASIN B00U1AH89K, $32.99, wall26, In Stock). **Reason:** least faithful to the actual painting. The page's itself specification data lists paint type "Watercolor," material "Wood," paper finish "Semi-Gloss," theme "Holidays" - inconsistent with Rembrandt's oil on canvas original (SK-C-5). Cut per the audit rule ("unavailable or least faithful to the actual painting").
- **Parent issue:** #11 "Merch audit: The Night Watch" - artwork facts in the body, plus all four findings and the parent cut note; 1 comment on the parent naming the cut product and why.
- **Sub-issues linked to parent #11:** #12 ARTCANVAS The Night Watch 1642 Canvas Art Print; #13 The Night Watch Barnwood Framed Print; #14 The Night Watch 1000-Piece Jigsaw Puzzle. (#15 Nachtwacht wall26 print was cut and removed from the parent.)
- **Write-up branch:** audit-findings -> pull request into main (PR #15).

## 4. Why this product was cut

#4 (wall26 Nachtwacht print) was cut. It was In Stock - the "unavailable" side of the cut criterion was not the trigger - but it failed the fidelity test decisively: its own product specifications declare it a "watercolor print" tagged "Holidays," which is a mismarked generic print presented as a Rembrandt reproduction rather than a faithful copy of the oil on canvas original that the Rijksmuseum actually holds (SK-C-5).
