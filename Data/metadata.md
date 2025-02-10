# 📜 Metadata for *Optimizing Bromoform Content in Gracilaria parvispora* Dataset

This file provides a detailed description of the dataset, including the treatments, units, and column explanations.

---

## **📂 Data Files and Descriptions**

### **1️⃣ Desiccation_blocked.csv**
- **Treatment**: Categorical values (0, 1, 2, 3) corresponding to desiccation duration in minutes:
  - **0** = 0 min  
  - **1** = 15 min  
  - **2** = 30 min  
  - **3** = 45 min  
- **Bromoform Content** (ng/g DW): Bromoform concentration in dry weight tissue.
- **Bromoform Emissions** (ng/g/hr DW): Emissions of bromoform per hour per dry weight.

---

### **2️⃣ Shading_blocked.csv**
- **Treatment**: Percentage of light reduction using shade cloth:
  - **0%** (Full sunlight)  
  - **30%** reduction  
  - **60%** reduction  
- **Bromoform Content** (ng/g DW): Bromoform concentration in dry weight tissue.
- **Bromoform Emissions** (ng/g/hr DW): Emissions of bromoform per hour per dry weight.

---

### **3️⃣ Thermal_blocked.csv**
- **Treatment**: Categorical values (1, 2, 3, 4) representing temperature conditions:
  - **1** = Control (ambient, ~17°C)  
  - **2** = ~19°C  
  - **3** = ~21°C  
  - **4** = Hottest condition (~24°C)  
- **Bromoform Content** (ng/g DW): Bromoform concentration in dry weight tissue.
- **Bromoform Emissions** (ng/g/hr DW): Emissions of bromoform per hour per dry weight.

---

### **4️⃣ diurnal_emission.csv**
- **Time**: Time recorded in Pacific Standard Time (PST).
- **Bromoform Emissions** (ng/g/hr DW): Emissions of bromoform per hour per dry weight.
- **PPFD** (µmol m⁻² s⁻¹): Photosynthetic photon flux density, representing available light.

---

### **5️⃣ diurnal_content.csv**
- **Time**: Time recorded in Pacific Standard Time (PST).
- **Bromoform Content** (ng/g DW): Bromoform concentration in dry weight tissue.
- **PPFD** (µmol m⁻² s⁻¹): Photosynthetic photon flux density, representing available light.

---

## 📢 **Additional Notes**
- Units:  
  - **ng/g DW** = Nanograms per gram of dry weight  
  - **ng/g/hr DW** = Nanograms per gram of dry weight per hour  
  - **PPFD** = Photosynthetic photon flux density (µmol m⁻² s⁻¹)  
- Missing values: If any data points are missing, they are represented as blank or `NaN`.

---

If you have any questions about the dataset, please contact:  
📧 **Steven Cunningham** - ✉️ steven.cunningham@sjsu.edu  
