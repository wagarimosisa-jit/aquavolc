AquaVolc: Open-Source Groundwater Modeling for Volcanic Aquifers

Contributing to AquaVolc

Thank you for your interest in **AquaVolc**! This project aims to revolutionize groundwater modeling for **volcanic aquifers**—a critical resource for **200+ million people globally**. Your contributions, whether as a **developer, hydrogeologist, or data scientist**, will help bring **clean, reliable water** to communities that need it most.

 **Why AquaVolc?**
Volcanic aquifers are **notoriously complex** due to:
- **Fracture-controlled flow** (transmissivity can vary by **2–3 orders of magnitude** over short distances).
- **Extreme spatial heterogeneity** (interbedded lava, tuff, ash, and clay layers).
- **Limited data availability** (single-well pumping tests are the norm in developing countries).

AquaVolc addresses these challenges by providing:
1. **GPS Enforcement** – Every data upload **requires latitude, longitude, and elevation** to ensure spatial integrity.
2. **Google Earth Integration** – Users **visualize and verify well locations** on satellite imagery in real time.
3. **Single-Well Pumping Test Support** – Estimates transmissivity (T) from specific capacity (SC) using the **empirically derived relationship**:
   > **log₁₀(T) = 0.98 × log₁₀(SC) – 0.06** *(R² = 0.89, validated on the Jimma dataset, Ethiopia)*
4. **Multi-Well Test Handling** – Supports **≥2 observation wells**, each with its own GPS coordinates.
5. **Expanded Analytical Solutions Library** – **20+ solutions**, including:
   - Theis (1935)
   - Cooper-Jacob (1946)
   - Hantush-Jacob (1955)
   - Neuman (1972)
   - Boulton (1963)
   - Warren-Root (1963)
   - Kazemi (1969)
   - Moench (1984)
   - Gringarten (1982)
   - Papadopulos-Cooper (1967)
   - And more...
6. **Automatic Solution Detection** – Uses a **hybrid rule-based + Random Forest ML classifier** (trained on 10,000 synthetic pumping tests) to recommend the best analytical solution.
7. **NLP-Powered Lithology Parsing** – Automatically converts **free-text drilling logs** into structured aquifer/aquitard layers.
8. **Web-Based Interpolation** – Temporal and spatial **kriging** for climate data, piezometric surfaces, and hydraulic parameters.
9. **High-Resolution Exports** – Generate **600 DPI PNGs, SVG vector graphics, and PDF reports**.

 **How to Contribute**
I welcome contributions from **developers, hydrogeologists, data scientists, and domain experts**! Below are ways you can help me, regardless of your background.

**💻 For Developers**: *(No hydrogeology experience required! We’ll guide you.)*

**1. Set Up Your Environment**
1. **Fork the repository** by clicking the **"Fork"** button at the top-right of [this page](https://github.com/wagarimosisa-jit/aquavolc).
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/wagarimosisa-jit/aquavolc.git
   cd aquavolc

   Contact & Support
Have questions or ideas? I’d love to hear from you!
Project Lead: Wagari Mosisa
Email: wagari.mosisa@ju.edu.et
LinkedIn: https://www.linkedin.com/in/wagari-mosisa-phd-9b50ab85/
GitHub: wagarimosisa
Project Repository: https://github.com/wagarimosisa-jit/aquavolc

Let us change something together!


