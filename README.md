EPONYMOUS DICTIONARY (EpoDict)
==============================

**EpoDict** is a structured, editable digital dictionary of biostatistical eponyms.  
It combines an **interactive Shiny editor** for maintaining entries with **Quarto publishing** for PDF and web output.

---

## Project structure

EPONYMOUS DICTIONARY/
│
|── Publishing/ # Quarto publishing
│ ├── EpoDict.qmd # Dictionary content
│ ├── EpoDict_overview.R # Progress statistics
│ └── outputs/ # Rendered PDF/HTML
│
├── EpoDict_data (.xlsx or .csv) (the EpoDict's dataset)
├── images/ # Portrait images (used in the dictionary)
├── drafts/ # Drafts and working notes
├── texts/ # Narrative or text snippets
├── sql/ # SQL scripts if needed
│
├── README.md # Project documentation
└── EPONYMOUS_DICTIONARY.Rproj

---

## Version Control
This project is Git-ready. Temporary files and outputs are ignored via `.gitignore`.
