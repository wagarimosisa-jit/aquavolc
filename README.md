AquaVolc
Web-Based Automated Groundwater Modeling System for Volcanic Aquifers

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-20232A?logo=react)](https://reactjs.org/)

AquaVolc is the first open-source, web-based tool** for modeling **volcanic aquifers, designed for **developing countries where data is scarce and expertise is limited.

🚀Demo: [Coming Soon!]
📖 Docs: [Wiki](https://github.com/wagarimosisa/aquavolc/wiki)
💬 Join our Slack: [Request Invite](#) (Email me for invite)
📧 Contact: wagari.mosisa@ju.edu.et 


 Why AquaVolc?
Volcanic aquifers supply drinking water to 200M+ people globally, yet they remain among the most challenging hydrogeological systems due to:
- Fracture-controlled flow (transmissivity varies by 2–3 orders of magnitude over short distances).
- Extreme spatial heterogeneity (interbedded lava-tuff-ash sequences).
- Limited data (single-well pumping tests are the norm in developing countries).

AquaVolc fixes this by:
1. Enforcing GPS in every data upload (latitude, longitude, elevation).
2. Integrating Google Earth for real-time location verification.
3. Handling single-well tests via the empirical relationship:log₁₀(T) = 0.98 log₁₀(SC) – 0.06 (R² = 0.89, validated on Jimma dataset).
4. Supporting multi-well tests with ≥2 observation wells (each with GPS).
5. Automating lithology parsing** using NLP.
6. Detecting the best analytical solution using ML (Random Forest).
7. Providing 20+ solutions: Theis, Cooper-Jacob, Hantush-Jacob, Neuman, Warren-Root, Kazemi, etc.

 How to Contribute
I welcome developers, hydrogeologists, and data scientists! Here’s how to help:

 For Developers
1. Fork this repo and create a branch 
2. Pick an issue 
3. Commit to changes 
4. Push to the branch 
5. Open a Pull Request.

Good First Issues (for beginners):
1. Implement the Theis solution in FastAPI.
2. Add Excel file parsing (pandas + openpyxl).
3. Create a basic frontend form for well data upload.
4. Set up PostgreSQL + PostGIS locally.

 For Hydrogeologists
- Test the tool and report bugs.
- Provide datasets (anonymized, with GPS).
- Review scientific accuracy of models.

For Data Scientists
- Help train the NLP model (lithology parsing).
- Improve the Random Forest classifier for solution detection.


Contact
- Wagari Mosisa – wagari.mosisa@ju.edu.et | https://www.linkedin.com/in/wagari-mosisa-phd-9b50ab85/
- Project Link: [https://github.com/wagarimosisa/aquavolc](https://github.com/wagarimosisa/aquavolc)
