# Preventivator 3000

[Italiano](README.md) | **English**

**3D printing quotes, from the file to the PDF.** Load your models, get weight and print time from your slicer, and arrive at a price based on real costs: material, energy, printer depreciation, waste and labor.

![Preventivator 3000 dashboard](docs/screenshots/en/dashboard.png)

*All screenshots use sample data.*

## What it does

- **Complete quotes:** customers, discounts, shipping, deposits, VAT and extra services.
- **Automatic slicing with Bambu Studio, OrcaSlicer or PrusaSlicer:** process 3MF, STL and STEP files without opening the slicer window, including several files at once.
- **Files from any slicer:** reads time, weight, colors and preview from already sliced files from Bambu Studio, OrcaSlicer, PrusaSlicer (including .bgcode), Cura (including .ufp), Simplify3D and ideaMaker.
- **Real costs:** the printer's hourly cost is calculated from its price and service life.
- **3D preview:** place and rotate the model on the Bambu Lab A1 plate.
- **Material stock:** remaining amount for each spool and low-stock alerts.
- **Import from your slicer:** printers, materials and print profiles from Bambu Studio, OrcaSlicer or PrusaSlicer.
- **Color library:** import color tables from PDF and pick a material color with one click.
- **PDF:** a quote for the customer and a work order for production.
- **Dashboard:** orders, revenue, profit, material and print hours.
- **Italian and English:** choose the language of the app and of the PDFs.
- **Autosave and updates:** automatic saving once a customer is selected, and update checks at startup.

## The quote

Every change immediately updates the summary: costs, profit and final total.

![Filling in a quote](docs/screenshots/en/quote.png)

## All your quotes

Status, total and quick actions to open, duplicate or export to PDF.

![Quote list](docs/screenshots/en/quotes.png)

## Materials and printers

![Material management](docs/screenshots/en/materials.png)

![Printer management](docs/screenshots/en/printers.png)

## Color library

Import a color table from a PDF, check the preview and add it to the library. In the material form, choose the line and click a color: its name and code are filled in for you. If a PDF cannot be read, you can enter the colors by hand.

![Color library](docs/screenshots/en/color-library.png)

![Quick color selection](docs/screenshots/en/color-picker.png)

## Installation

**Windows:** download `Preventivator3000-Setup` from the [latest release](../../releases/latest) and open it. If Windows shows "Windows protected your PC", choose **More info** → **Run anyway**: the installer does not have a digital signature yet.

To slice from the app, a slicer must be installed on the same computer: [Bambu Studio](https://bambulab.com/en/download/studio), [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer/releases) or [PrusaSlicer](https://www.prusa3d.com/page/prusaslicer_424/) 2.6 or later. Choose it in **Settings → Slicer**.

## License

Copyright (c) 2026 Nicolò Casella. All rights reserved. See the [LICENSE](LICENSE) file (in Italian).

Bambu Lab, Bambu Studio, OrcaSlicer, Prusa, PrusaSlicer, UltiMaker Cura, Simplify3D and ideaMaker are trademarks of their respective owners. Preventivator 3000 is an independent project.
