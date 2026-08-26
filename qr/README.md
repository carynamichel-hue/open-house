# QR code — Open House schedule

Points at **https://carynamichel-hue.github.io/open-house/**

| File | Use it for |
|------|-----------|
| `open-house-qr.svg` | **Printing.** Vector — sharp at any size, from a table card to a barn-door poster. |
| `open-house-qr.png` | Anywhere that will not take an SVG — email, slides, a Word document. 1023px square. |

**Error correction is level H (30%).** That is the highest, and it is deliberate:
these get taped to a wall and photographed at an angle in daylight, so a scuff,
a crease or a patch of glare should not stop it scanning.

## Printing it
- **Two inches square is the practical minimum**; four is comfortable across a
  room. Bigger is always safer than smaller.
- **Keep the white border.** That empty margin is part of the code — scanners
  need it, and cropping to the edge of the pattern is the usual reason a
  printed QR stops working.
- Do not recolour it to something pale. The dark is the page's purple-black
  (#241a2e) and the contrast against white is what a phone camera reads.

## If the URL ever changes
Regenerate rather than editing — a QR is not editable. The generator and the
check that reads each code back out of its own pixels live in the session notes
for 2026-08-26; any QR tool will do as long as you **scan the result with a real
phone before printing a hundred of them**.

Both codes in this project and in PlantPicks were verified by decoding the
generated image and comparing the text to the URL it was made from.
