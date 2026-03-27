# Piano Rebuilding Tool: Piano Scaling & Bass String Design Calculator

### Automatic calculation of string tensions, loads, and wound bass string specifications.

---

## 🎹 Overview
Hello,

I am providing this specialized tool designed to calculate and optimize **piano scaling (stringing plans)**. This spreadsheet allows you to analyze frame loads, determine bass string winding diameters, and assess inharmonicity risks.

As a practical example, the tool is pre-filled with data from a real restoration: 
**Weber (Aeolian Co. New York) - Duo Art, 5F Frame, 183cm (6') - SN 73211 (1918).**

---

## 🚀 Discover ViGAPhone Synth Lab
If you are interested in piano technology, check out my other project:  
**[ViGAPhone Synth Lab](https://github.com/ViGAWorld-FR/ViGAWorld-ViGAPhone)**

This application provides innovative tools for **tuning and voicing pianos**. It incorporates an Electronic Tuning Device (ETD), spectral analyzer, and a physical modeling synthesizer allowing for real-time testing of temperaments and analysis of string harmonics.

---

## 📜 Licensing & Usage
* **Free to Use:** This tool is provided **free of charge** for both personal and professional use by piano technicians and rebuilders.
* **Integrity & Safety:** While the tool is fully configurable, the core calculation formulas are protected. This is to ensure the technical integrity of the results and prevent the circulation of modified versions that could lead to dangerous tension levels for an instrument.

---

## 🛠 Key Features
* **Manufacturer Integration:** Pre-configured with technical data from **Stephen Paulello** and **Röslau**. It can be customized for other wire manufacturers if technical specifications are provided.
* **Inharmonicity Assessment:** Includes formulas to estimate inharmonicity risks. While these are theoretical models, they provide a valuable baseline for scale smoothing (note: not applicable to wound strings).
* **Safety & Integrity:** The tool is fully configurable. However, calculation formulas are protected to ensure the integrity of the tool and prevent the distribution of modified versions that could lead to dangerous tension levels for an instrument.

---

## 📐 Technical Philosophy
The tool follows the empirical principle that steel strings achieve their best tonal quality near their elastic limit. We assume an optimal "speaking" stress of approximately **60% of the breaking limit**.

This 60% target is derived from a safety margin: a deformation limit of ~75–80%, minus an additional 20% to account for friction constraints along the entire string path:
$$80\% \text{ of } 75\% \text{ of } 100\% = 60\%$$

* **Standard Steel:** Target limit is **80% stress** for the speaking length.
* **High-Tensile Steel (Treble):** Target limit is **85% stress**.
* **Tuning Margin:** Note that during the pull, the non-speaking segment (pinblock side) may momentarily reach **100% stress** due to friction.

---

## 📋 Usage Recommendations
* **Documentation:** Once your restringing is complete, remember to print, date, and sign the stringing plan to leave it inside the piano for future technicians.
* **Software Compatibility:** For full access to all tabs (Calculations, Graphs, Data), download the file and open it locally. It is compatible with **µS-Excel**, **LibreOffice** (PC/Mac), and **OnlyOffice** (Mobile).

---

## 📥 Downloads
The [GitHub Releases](https://github.com/ViGAWorld-FR/Piano-Scale-Design/releases) contains French and English files versions in **.xlsx** formats.


---
*Created by ViGA-FR*
