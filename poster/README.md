# Two printable posters — one per QR code

Letter paper, portrait. **Print one of each and put them where people will be.**

| Poster | Points at | Where it belongs |
|--------|-----------|------------------|
| `poster-open-house-schedule.pdf` | the schedule page | Check-in, the tractor barn, anywhere someone might wonder what is on next |
| `poster-new-plant-selections.pdf` | the plant tool | Wherever the new-plant talk happens — this is the one people use *during* it |

## Printing
**Just print the `.pdf`.** It is already Letter, portrait, with the margins set.

The `.html` beside it is the same poster, and it is what you edit if the wording
needs to change — open it in a browser and press **Ctrl + P**. Two things to
watch in the print dialog:

- **Leave “background graphics” on** if it asks. Off, the lavender panel and the
  numbered circles disappear.
- **Do not pick “fit to page” at a reduced scale.** Shrinking the sheet shrinks
  the code, and the code is the point.

Each file is completely self-contained — the QR is drawn into the page itself,
so there is no image to go missing and nothing to download. Copy the file to any
computer and it still prints.

## What is on them
The code, big (3.9 inches — comfortably scannable across a room), the URL spelled
out underneath for anyone whose camera will not cooperate, and a **“Never used
one of these?”** panel: open the Camera app, hold it up, *don't press the button*,
tap the link. It ends by pointing at a yellow shirt, same as the schedule page.

## If a URL ever changes
The codes live in `../qr/` and in `plantpicks-nuxt/qr/`. Regenerate the code
first, then rebuild these posters — a QR cannot be edited, only remade.

`printview-*.png` are just pictures of how each sheet comes out; they are not for
printing.

## Before you print a hundred
**Scan both with a real phone.** Every code here was generated, rendered into the
poster, then read back out of the finished page and checked against its URL — but
that is a computer reading a screen. A phone reading paper is the test that
counts, and it takes ten seconds.
