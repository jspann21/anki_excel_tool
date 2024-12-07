# Anki ↔ Excel Converter

This tool simplifies the process of converting Anki decks to Excel-friendly formats and back again, without the hassle of manual encoding adjustments or dealing with Excel's Text Import Wizard. This lightweight web-based converter handles the hard work for you.

## Features

- **Convert Anki decks to Excel CSV**  
  Export your Anki decks into a CSV format that opens directly in Excel with proper UTF-8 encoding.
  
- **Convert Excel files back to Anki format**  
  Save your edited Excel files as UTF-8 tab-delimited `.txt` files ready to import into Anki.

- **Drag-and-Drop Simplicity**  
  Just drag and drop your files into the tool to convert instantly. No complex configurations or manual steps required.

- **Supports Proper Filename Handling**  
  Automatically updates filenames, replacing `-excel_ready` with `-anki_ready` (and vice versa) for smooth workflows.

---

## How to Use

1. **Export from Anki (for "Anki to Excel" mode):**
   - In Anki, go to `File > Export`.
   - Select `"Notes in Plain Text"` as the export format.
   - Optionally include tags, HTML, or media references as needed.
   - Export the deck as a `.txt` file.

2. **Convert Files:**
   - Open this tool in your browser (hosted on [GitHub Pages here](https://jspann21.github.io/anki_excel_tool/)).
   - Choose your mode:
     - **Anki to Excel**: Converts `.txt` files to UTF-8 CSV files that open directly in Excel.
     - **Excel to Anki**: Converts CSV files back into UTF-8 tab-delimited `.txt` files.
   - Drag and drop your file into the upload area, or click to select it.
   - Your file will be converted instantly, and a download prompt will appear.

3. **Edit in Excel (optional):**
   - Open the generated CSV directly in Excel by double-clicking it.
   - Make your edits. Each column corresponds to a field in your Anki note type.
   - Save changes using `File > Save` or `Ctrl+S` to retain UTF-8 encoding.

4. **Import Back into Anki:**
   - Drag and drop the edited CSV into the tool (set to **Excel to Anki** mode).
   - Download the newly generated `.txt` file.
   - Import it into Anki using `File > Import`.

---

## Example Workflow

1. Export your Anki deck as a `.txt` file.  
2. Convert the `.txt` file to a UTF-8 CSV using the **Anki to Excel** mode.  
3. Open the CSV in Excel, make changes, and save using `Ctrl+S`.  
4. Convert the updated CSV back to a `.txt` file using **Excel to Anki** mode.  
5. Import the `.txt` file back into Anki.

---

## Notes

- This tool assumes a modern version of Excel (e.g., Excel 2016 or later, or Microsoft 365) that preserves UTF-8 encoding when saving files with `File > Save` or `Ctrl+S`.
- Filenames are intelligently updated during conversion to prevent clutter:
  - Files ending with `-excel_ready` will have this replaced with `-anki_ready` when converting back to Anki format.
  - Otherwise, appropriate suffixes are appended.

---

## Limitations

- This tool is **experimental**—proceed with caution. If your Anki deck starts insisting on spelling everything backward, you’ve been warned!  
- Always create backups of your Anki decks before using the tool.

---

## Contributing

Contributions, feedback, and bug reports are welcome! Feel free to submit an issue or open a pull request.

---

## Credits

- Adapted from the original process: [Original Instructions Document](https://docs.google.com/document/u/0/d/12YE_FS6A9ANLTESJNtPP116ti4nNmCBghyoJBRtno_k/mobilebasic?pli=1)
- Additional guidance: [Anki Importing Guide](https://docs.ankiweb.net/importing.html)

---
