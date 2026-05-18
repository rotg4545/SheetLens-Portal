# SheetLens-Portal
A local tool to automate repetitive filtering of .xlsx, .xlsm, and .csv files. Create custom filters, save the config, and process single files or entire batches with the same structure at once. Runs completely offline to ensure data privacy, saving time on routine administrative and data-cleaning tasks.


---

## 💡 Ideal Use Cases

*   **Daily/Weekly Reporting:** Automate the extraction of specific data rows from routine administrative or engineering reports.
*   **Data Preprocessing:** Clean and slice massive datasets before feeding them into database management systems or analytical models.
*   **Bulk File Standardization:** Apply identical structural filters across hundreds of historically segmented data sheets at once.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Would you like me to add a specific section detailing how the filter logic is structured (like a JSON configuration snippetHere is a clean, professional, and well-structured GitHub `README.md` description tailored for your repository. It highlights the core features, use cases, and includes a placeholder for usage instructions.

---

# Local Data Filter Tool (LDFT)

A powerful, privacy-focused desktop utility designed to filter large datasets across `.xlsx`, `.xlsm`, and `.csv` files entirely locally. If you find yourself repeatedly opening massive spreadsheets to apply the same complex filters day after day, this tool automates that workflow in seconds.

## 🚀 Key Features

*   **Multi-Format Support:** Seamlessly handles Excel workbooks (`.xlsx`), macro-enabled sheets (`.xlsm`), and comma-separated values (`.csv`).
*   **Saveable Filter Configurations:** Build your filter logic once and save the configuration. Perfect for routine, repetitive data-cleaning tasks.
*   **Batch Processing Mode:** Apply a single filter configuration to multiple files simultaneously, provided they share the same table/column structure. 
*   **Dynamic Empty-Filter Handling:** Smart filtering logic—if a configured filter field contains no data, the tool automatically yields clean, blank outputs for that parameter rather than breaking or throwing errors.
*   **100% Local & Secure:** Your data never leaves your machine. No cloud uploads, no external API dependencies—fully compliant with strict data privacy workflows.

---

## 🛠️ How It Works
[ Input File(s) ] ──> [ Saved Config (.json) ] ──> [ Local Filter Engine ] ──> [ Cleaned Output File(s) ]


1.  **Load:** Import your source file(s).
2.  **Configure:** Set up your filtering criteria (e.g., column matching, value ranges, exclusions).
3.  **Save:** Save your criteria as a configuration profile for future use.
4.  **Run/Batch:** Process a single file or point the tool to a folder of files for rapid batch execution.

---

## 📋 Quick Start

### Prerequisites
* node js
1. Install dependencies:
   npm install

2. Run the app:
   npm run dev

 
