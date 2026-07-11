# Hours & ELR Increase — What-If Calculator

A Fixed Ops what-if calculator for auto dealership service departments. Model the
additional gross profit from raising your effective labor rate (ELR) and increasing
hours per repair order (RO).

Built as a single self-contained web page (no build step, no dependencies).

## Two modes

- **Manual** — enter an ELR increase and hours-per-RO increase, see the projected
  gross profit.
- **Goal Seek** — enter a target annual gross profit instead, and the calculator
  reverses the math to show the ELR increase and hours-per-RO increase needed. A
  **Mix slider** trades the goal between the two levers: slide toward ELR to lean on
  rate, or toward Hours to lean on production. The two levers always sum to your
  target for any slider position.

## Use it

Open `index.html` in any browser, or visit the hosted GitHub Pages link.

On iPhone/iPad: open the hosted link in Safari, then **Share → Add to Home Screen**
to install it as a full-screen app.

## Files

- `index.html` — the app (HTML + CSS + JS in one file)
- `manifest.webmanifest` — makes it installable on a phone home screen
- `icon.svg` — app icon

## Notes

Derived from the original "Hours & ELR Increase Sheet" spreadsheet.
C.P. = Customer Pay · ELR = Effective Labor Rate · RO = Repair Order.
All figures are estimates based on the assumptions you enter.
