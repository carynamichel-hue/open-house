# Printable poster — Open House schedule

**`poster-open-house-schedule.pdf`** — Letter, portrait, ready to print.

Put it at check-in and anywhere someone might wonder what is on next.

**There is a second poster**, for the plant tool, and it lives with that project:
`dev/farm-hub-next/plantpicks-nuxt/poster/`. It is deliberately a separate sheet —
the two belong in different places and at different moments. That one is used
*during* the new-plant talk; this one is used all day.

## Printing
Just print the `.pdf`. The `.html` beside it is the same poster and is what you
edit if the wording changes — open it in a browser and press **Ctrl + P**. Two
things to watch in the print dialog:

- **Leave "background graphics" on** if it asks. Off, the lavender panel and the
  numbered circles disappear.
- **Do not pick "fit to page" at a reduced scale.** Shrinking the sheet shrinks
  the code, and the code is the point.

The file is completely self-contained — the QR is drawn into the page itself, so
there is no image to go missing and nothing to download. Copy it anywhere and it
still prints. It is also served from the live site, so you can print it from any
machine at the farm:
`carynamichel-hue.github.io/open-house/poster/poster-open-house-schedule.pdf`

## What is on it
The code at 3.9 inches (comfortably scannable across a room), the URL spelled out
underneath for anyone whose camera will not cooperate, and a **"Never used one of
these?"** panel: open the Camera app, hold it up, *don't press the button*, tap
the link. That third step is the one that matters — people hesitate because they
think they are about to take a photograph. It ends by pointing at a yellow shirt,
the same as the schedule page itself.

## If the URL changes
The code itself is in `../qr/`. Regenerate it there first, then rebuild this
poster — a QR cannot be edited, only remade.

`printview-open-house.png` is just a picture of how the sheet comes out; it is
not for printing.

## Before you print a stack
**Scan it with a real phone.** The code was generated, rendered into this poster,
then read back out of the finished page and checked against the URL — but that is
a computer reading a screen. A phone reading paper is the test that counts, and
it takes ten seconds.
