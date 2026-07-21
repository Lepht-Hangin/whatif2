# Fixed Ops Gross Profit Tools

Two self-contained web pages (no build step, no dependencies) for auto dealership
service departments. A nav bar at the top switches between them.

## 1. What-If Calculator (`index.html`)

Model the *additional* gross profit from raising your effective labor rate (ELR) and
increasing hours per repair order (RO).

### Two modes

- **Manual** — enter an ELR increase and hours-per-RO increase, see the projected
  gross profit.
- **Goal Seek** — enter a target annual gross profit instead, and the calculator
  reverses the math to show the ELR increase and hours-per-RO increase needed. A
  **Mix slider** trades the goal between the two levers: slide toward ELR to lean on
  rate, or toward Hours to lean on production. The two levers always sum to your
  target for any slider position.

## 2. Gross Profit Goal Planner (`goal.html`)

Work backwards from a target. Enter a gross-profit goal (monthly or annual) and pick
**one driver to solve for** — RO count, hours per RO, or ELR. The other two become
live sliders; move either one and the solved driver re-computes instantly so the plan
always lands exactly on the goal. Shows the full KPI chain: hours sold, labor/parts
sales, and the labor + parts gross-profit breakdown.

  Total GP = ROs × Hours/RO × ELR × (Labor GP% + Parts:Labor% × Parts GP%)

## Use it

Open `index.html` in any browser, or visit the hosted GitHub Pages link, then use the
top nav to switch pages.

On iPhone/iPad: open the hosted link in Safari, then **Share → Add to Home Screen**
to install it as a full-screen app.

## Files

- `index.html` — What-If Calculator (HTML + CSS + JS in one file)
- `goal.html` — Gross Profit Goal Planner (HTML + CSS + JS in one file)
- `manifest.webmanifest` — makes it installable on a phone home screen
- `icon.svg` — app icon

## Notes

Derived from the original "Hours & ELR Increase Sheet" spreadsheet.
C.P. = Customer Pay · ELR = Effective Labor Rate · RO = Repair Order.
All figures are estimates based on the assumptions you enter.
