# Tote-ily

Built in a weekend at HackDFW 2022 by a team of five.

Reusable tote bags with a QR code on each. A camera at the store entrance and at the checkout
reads the code, ties the visit and the purchase to that bag, and charts habits over time. A store
can hand the bags out for free, reward people for bringing them back, cut down on plastic, and
see how a promotion or a season changes what sells.

## What is here

| File | Role |
|---|---|
| `live_cam.py` | Reads QR codes from a live camera feed |
| `processor.py` | Ties scans to customers and purchases |
| `customer.py` | The customer model |
| `graphs.py` | Builds the charts (`itemsPurchasedOnTime.png`, `totalSpentOnTime.png`) |
| `main.py` | Runs the pipeline |
| `assets/` | Mock customer and store-visit data |

The demo videos from the hackathon weekend are not included; they were large and showed people.

## Run

Python 3 with the libraries the scripts import at the top (OpenCV and the QR reader). The code
is kept as it was that weekend.
