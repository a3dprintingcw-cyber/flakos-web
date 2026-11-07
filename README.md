# The Flako's Grill · ordering demo

Pitch demo of pickup ordering for The Flako's Grill, Curaçao. Built by A3D.

- `index.html`: the customer ordering app and the truck kitchen board in one page
- `images.js`: the Flako's logo (embedded)

Each truck has its own link, so a QR at a truck only ever orders from that truck:

| Truck | Link |
| --- | --- |
| Caracasbaaiweg (697-6181) | `index.html#caracasbaai` |
| Sta Maria (663-9666) | `index.html#santamaria` |
| Beach Station (666-1166) | `index.html#beachstation` |

The grey bar at the top is for the pitch only: it switches between the trucks and between the customer phone and the kitchen screen.

This is a demo. Orders stay in the browser and nothing is sent anywhere. The live version would follow the Volcano setup: a Cloudflare Worker and database, a kitchen board per truck, Sentoo payments and WhatsApp or push updates when the food is ready.

Menu and prices (XCG) are in the `MEATS`, `PLATS` and `SIMPLE` lists in `index.html`. Still to confirm with Flako's: Kapsalon and Moro prices, Mix 2 and Mix 3 meat choices, and opening hours per truck.
