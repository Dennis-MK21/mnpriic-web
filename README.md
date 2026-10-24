# JuaSize — Solar PV System Calculator

Sizes a solar PV system (panels, battery bank, inverter, charge controller) from an appliance load list, and estimates system cost. Built for Kenyan solar installers and DIY users.

## How it works
- Add appliances with wattage, quantity, and daily usage hours
- Set system parameters (voltage, battery type, autonomy, sun hours, losses)
- Results update live: PV array size, battery bank, inverter, charge controller
- Add your pricing to get a total cost estimate
- Save multiple projects (stored on your own device — no account needed)
- Generate a shareable report to send to a client via WhatsApp, etc.

## Hosting
No backend needed — this is a single static `index.html` file. Host it for free on GitHub Pages:
Settings → Pages → Deploy from branch → main → / (root).

## Notes
- All saved projects are stored locally in the browser (localStorage) — they stay on the device you used to save them, not shared between devices.
- Figures are engineering estimates; always apply your own safety margins and local code requirements for real installations.
