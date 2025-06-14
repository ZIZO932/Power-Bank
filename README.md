# DIY 120W Power Bank

Disclaimer: This project is still in progress, and there may be slight imperfections in the models or component fit.

I set out to build a high-power, compact 120-watt power bank. My goals were: high output power and a custom-designed circuit. The case has cutouts for ports (USB-A, USB-C, DC input). The outer shell is engraved with my logo and name to give it a personal touch.

![P3.png](/CAD/Images/P3.png) ![P1.png](/CAD/Images/P1.png)
---

## How to Build

- **Print the case**: The enclosure was designed in SolidWorks and is best printed in PETG for its thermal resistance and strength. A 3 mm wall thickness work well.
  
- **Prepare the electronics**:
  - Solder battery connectors to the 3S BMS board. Ensure polarity is correct.
  - Splice a USB-C cable and connect it to the BMS or buck-boost converter input for charging.
  - Connect the boost converter output to both the USB-A and USB-C output ports.
  - Attach the DC barrel jack to the BMS and buck module input if you plan to support DC charging.
  - Dont forget to add the voltmeter and battery lcds.

- **Install components**:
  - Begin by placing the battery cells securely in the case and soldering them to the BMS.
  - Mount the BMS, buck/boost converter, and output modules using screws or adhesive pads.
  - Fit the USB-A, USB-C, and DC jack into their respective cutouts.
  - Tidy up wiring with shrink tubing or small cable ties to prevent short circuits.

- **Power it up**:
  - Double-check all connections, especially battery polarity and grounding.
  - Insert a multimeter to test voltage on the output before plugging in any devices.
  - Once verified, you can use the power bank to charge phones, laptops, or any compatible USB devices up to 120 watts.

---

## BOM 


# Component List and Cost Breakdown

| Component                          | Qty | EGP/Unit | Sum EGP | Sum USD | Purpose                 | Link |
|-----------------------------------|-----|----------|---------|---------|--------------------------|------|
| 18650 Li-ion 3350mAh battery      | 6   | 130      | 780     | 15.69   | Battery cells            | [Link](https://makerselectronics.com/product/li-ion-rechargeable-bak-18650-battery-high-drain-3-6v-3350mah-10a-n18650cp-used-like-new) |
| 3S 10A BMS board                  | 2   | 65       | 130     | 2.62    | Battery protection       | [Link](https://makerselectronics.com/product/bms-3s-10a-12-6v-lithium-battery-charger-protection-module) |
| USB-PD trigger board             | 1   | 200      | 200     | 4.02    | PD 12V trigger           | [Link](https://makerselectronics.com/product/usb-pd-decoy-trigger-board-adjustable-volt-5v-9v-12v) |
| DC jack w/ terminal block        | 1   | 75       | 75      | 1.51    | Power connector          | [Link](https://makerselectronics.com/product/female-dc-jack-adapter-with-terminal-block) |
| Mini push-button 6x6x9mm         | 2   | 5        | 10      | 0.20    | Manual input             | [Link](https://makerselectronics.com/product/mini-push-button-4-pin-6x6x9mm) |
| DC-DC Boost Converter 400W       | 1   | 350      | 350     | 7.04    | Voltage step-up          | [Link](https://makerselectronics.com/product/dc-dc-boost-converter-voltage-step-up-module-400w-12a) |
| Digital Voltmeter & Ammeter      | 1   | 175      | 175     | 3.52    | Display voltage/current  | [Link](https://makerselectronics.com/product/dc-0-100v-10a-digital-voltmeter-and-ammeter-dual-display) |
| Battery capacity LCD (GY-6)      | 1   | 170      | 170     | 3.42    | Charge indicator         | [Link](https://microohm-eg.com/product/battery-capacity-indicator-tester-lcd-panel-gy-6) |
| QC 4.0 Step-Down Module (AliExpress) | 2 | 300  | 600     | 12.07   | Fast charging input      | [Link](https://www.aliexpress.us/item/3256808964103204.html) |
| USB-C female board (RAM-E)       | 1   | 75       | 75      | 1.51    | USB-C output             | [Link](https://www.ram-e-shop.com/shop/kit-usb9-c-type-usb-type-c-female-interface-board-8031) |
| AWG 12 wire (1m)                 | 1m  | 100      | 100     | 2.01    | Main high-current wiring | [Link](https://store.fut-electronics.com/products/copy-of-wire-awg-12-black-0-5-m) |
| PVC heat-shrink tube (battery wrap) | 1m | 35     | 35      | 0.70    | Insulates packs          | [Link](https://microohm-eg.com/ar/product/lithium-battery-pvc-heat-shrink-blue-tube-for-85mm-180mm-1-meter/) |
| 0.2×8 mm plated nickel strip (1m)| 1m  | 18       | 18      | 0.36    | Battery weld tabs        | [Link](https://microohm-eg.com/ar/product/0-2-x-8-mm-plated-nickel-strip-for-battery-connection-welding-1-meter/) |
| Aluminium soldering flux (10mL)  | 1   | 60       | 60      | 1.21    | Soldering aid            | [Link](https://makerselectronics.com/product/aluminium-soldering-liquid-flux-10ml) |

---

### 💰 Summary

- **Total Cost (EGP):** 2778 EGP  
- **Total Cost :** $56


