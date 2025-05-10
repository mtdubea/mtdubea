# Generate a polished GitHub profile README for Matthew Dubea

cleaned_readme_md = """\
# Matthew Dubea – Mechanical Engineering Portfolio

![Trike Design](https://mtdubea.github.io/matthew-dubea.github.io/trike.png)

Hi, I’m Matthew — a mechanical engineering senior graduating in **May 2025** from the University of Louisiana at Lafayette. I specialize in hands-on mechanical systems, **CAD design**, and **performance-based engineering** with real-world application. My focus is on **design-for-manufacturability**, structural analysis, and creative solutions backed by fabrication and testing.

---

## 🏁 Senior Design – Human-Powered Tricycle (Acadiana 500)

**Team:** Fast Pedal Engineers  
**Result:** 🥇 1st Place Overall  
**Top Speed:** ~14.5 mph  
**Final Time:** 3 minutes 31 seconds  
**Track:** 0.66-mile relay w/ 8-person rotation

We engineered and fabricated a racing trike from scratch to meet all competition rules: no chains, no gears, and direct pedal-to-wheel front-drive. The frame was TIG-welded steel with a custom rear axle, brass bushings, seat anchors, and optimized center of gravity for speed and balance.

### 🔧 My Contributions

- Designed full CAD assembly in **SolidWorks** (frame, fork, stem, axle)
- Ran **FEA** (σ_vm ≈ 2.8e8 N/m²) to validate critical stresses and safety factor
- Created all **engineering documentation**: spec sheets, tolerances, bill of materials
- Managed fabrication: **CNC sleeves**, bushings, brass spacers
- Modeled tipping angle, lateral acceleration, and lap-time performance

---

## 📂 Project Files

| 📄 Document Type        | Link |
|------------------------|------|
| 📦 Trike Assembly ZIP  | [Download](https://mtdubea.github.io/matthew-dubea.github.io/Trike_Assembly.zip) |
| 📄 Senior Design Poster | [View PDF](https://mtdubea.github.io/matthew-dubea.github.io/MCHE484_FinalPoster_TrikeDesignAndFab.pdf) |
| 📊 FEA Report           | [View PDF](https://mtdubea.github.io/matthew-dubea.github.io/FEA_Results.pdf) |
| 🧾 Engineering Memo     | [View PDF](https://mtdubea.github.io/matthew-dubea.github.io/Engineering_Memo_Report.pdf) |
| 📈 Race Performance     | [Race Data (XLSX)](https://mtdubea.github.io/matthew-dubea.github.io/Race_Performance_Data.xlsx) |

---

## ⚙️ Additional Projects

### 🔩 CNC Fixture Design  
Adjustable clamp fixture modeled in SolidWorks with parametric constraints for multi-width stock.  
[Drawing (PDF)](https://example.com/placeholder_CNCFixture.pdf)

### 🔧 Suspension System Simulation  
Simulated 2-DOF suspension model in MATLAB/Simulink. Validated natural frequency and damping from impulse & step input.  
[Code](https://example.com/placeholder_SimulationCode.m)

### 🛩️ SR-30 Jet Turbine Lab  
Collected and analyzed compressor/turbine performance from real jet engine testbed using thermodynamic calculations.  
[Lab Report](https://example.com/placeholder_JetEngineLab.pdf)

---

## 🧠 Technical Skills

- **Design & Simulation**: SolidWorks, AutoCAD, Fusion 360, ANSYS, Simulink  
- **Programming**: MATLAB, Python, Arduino, Excel VBA  
- **Fabrication**: TIG Welding, CNC Machining, 3D Printing  
- **Documentation**: LaTeX, MS Word, Excel (regression plots, technical memos)  
- **Methods**: DFM, FEA, FMEA, GD&T, Tolerance Stackups

---

## 🎓 Certifications

- ✅ FE Mechanical Exam – *Passed*  
- ✅ OSHA 30 – *Construction Safety*  
- ⏳ Lean Six Sigma – *In Progress*

---

## 📬 Contact

📧 Email: [mattdubea@outlook.com](mailto:mattdubea@outlook.com)  
🔗 LinkedIn: [linkedin.com/in/matthew-dubea-4188ac311](https://linkedin.com/in/matthew-dubea-4188ac311)  
💻 GitHub: [github.com/mtdubea](https://github.com/mtdubea)  
📍 Location: Lafayette, Louisiana

---

> Thanks for checking out my portfolio. I’m open to full-time roles in product design, advanced manufacturing, and applied mechanical systems engineering.
"""

# Save the final README as a .md file
readme_path = "/mnt/data/README_MatthewDubea_Profile.md"
with open(readme_path, "w") as f:
    f.write(cleaned_readme_md)

readme_path
