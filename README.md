# Ellis Automotive — concept website

A single-page concept site for **Ellis Automotive**, a family-run auto repair shop on
Wagon Trail Rd in Pearland, TX (4.7★, 88 Google reviews). Built as a pitch preview by
Rashad — not the official Ellis Automotive website.

## The idea
The hero is a **paper repair order**. Visitors fill it in (the text appears in a
handwriting font), press "Book it in writing", a rubber stamp lands, the shop's sheet
tears away, and a yellow carbon **customer copy** is left showing exactly what was booked.
It answers the shop's real review complaint (appointments not being recorded) and
leans into its family, old-school character.

## Build
- Single `index.html`, inline CSS + vanilla JS, no build step or dependencies.
- Photos in `images/` are free Unsplash stock (placeholders): `shop-lift.jpg`,
  `mechanic.jpg`, `electrical.jpg`, `classic-truck.jpg`. Swap for real shop photos.
- Fonts: Bitter + Nunito Sans + Kalam (Google Fonts).
- Marked `noindex, nofollow`; footer labels it a concept preview.
- The repair-order form is front-end only. Before launch, connect Formspree / Web3Forms
  and an SMS/email confirmation (e.g. Formspree autoresponse, Twilio) so the promise
  "booked in writing" is real.
- `[CONFIRM WITH CLIENT]` tags mark facts to verify (names/titles, older vehicles
  accepted, warranty, state inspections, lead time).
