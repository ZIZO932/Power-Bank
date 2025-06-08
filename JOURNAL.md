# DIY 120W Power Bank

**Total time spent:** 14 hr

I have set out to build a high-power, compact 120-watt power bank. This project includes a custom-designed power circuit and a 3D-printed case. The circuit was modeled using Cirkit Designer, and the case was created in SolidWorks.

---

## Wednesday 4th June: Designing the Power Circuit (4 hr)

Today I began researching and designing the core circuit for my power bank. My goal was to achieve a stable 120W output.

After reviewing different buck-boost converters and protection circuits, I designed a system based on a high-efficiency module capable of both charging and discharging at high current levels. Key features included:

- Over-voltage and over-current protection (BMS)
- Support for multiple output formats (USB-A and USB-C)
- Charging via DC barrel jack and USB-C

I sketched the initial design using Cirkit Designer.
![Circuit diagram.png](/CAD/Circuitdiagram.png) 
---

## Thursday 5th June: Component Selection and Sourcing (2 hr)

I spent today sourcing critical components online. The most important were:

- **Battery cells**: I selected 3350mAh Li-ion cells with a continuous discharge rate of 10A.
- **Battery Management System (BMS)**: I chose a 3S BMS with balancing capabilities and a 10A current limit.
- **Power output modules**: After researching various options, I found that QC 4.0 modules offer up to 60W. These are hard to find locally (in Egypt) and more expensive, but worth the performance gain.

I created an initial Bill of Materials (BOM) based on these parts.

---

## Friday 6th June: 3D Case Design – First Stage (3 hr)

Today I opened SolidWorks and began designing the case for the power bank. My main design goals were:

- Easy access to internal components for assembly and maintenance
- A compact form factor
- Aesthetic personalization — I added my logo and name to the case to make it unique
![P1.png](/CAD/Images/P1.png) ![P3.png](/CAD/Images/P3.png)

---

## Saturday 7th June: Finalizing the Design (5 hr)

Today I finalized the 3D case design by:

- Adding port cutouts (USB-A, USB-C, DC input)
- Increasing the wall thickness to 3mm to ensure structural strength
- Optimizing the layout for better airflow and thermal performance

I also updated the BOM to prioritize local component shops, reducing costs and improving flexibility. I plan to 3D print the enclosure using PETG for its thermal resistance and mechanical durability.

Finally, I wrote a README file to document the project structure and usage.

---
