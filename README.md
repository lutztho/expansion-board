# Battery Extension Board for Seeed Studio XIAO nRF52840 & Wio-SX1262

Custom expansion board designed for the Seeed Studio XIAO nRF52840 paired with the Wio SX1262 LoRa module, tailored for Meshtastic deployments. 

## 🔋 Design Features
- **Modular Power**: Designed without a fixed, permanent battery so you can easily swap or service batteries in the field.
- **Standardized Pinout**: JST PH 2.0 battery connector polarity matches the **RAK 4630** standard for seamless battery cross-compatibility.
- **Pogo Pin Connections**: Utilizes 3.0mm DIP pogo pins for clean, reliable contact with the main module.

## 📸 Gallery

<p float="left">
  <img src="images/preview.jpg" width="32%" alt="Preview Render" />
  <img src="images/top-view.jpg" width="32%" alt="Top View" />
  <img src="images/bottom-view.jpg" width="32%" alt="Bottom View" />
</p>

## 📋 Bill of Materials (BOM)
See the detailed component list and supplier links in [bom.md](bom.md).

## 📁 Repository Structure
- **`fabrication/`** - Production archive (`XIAO.zip`) containing Gerber and drill files ready for JLCPCB.
- **Root files** - KiCad schematic (`.kicad_sch`), PCB layout (`.kicad_pcb`), and project files.