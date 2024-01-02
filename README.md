# Convert Excel/Div/Image to PDF

This Python project provides a simple tool to convert Excel spreadsheets, HTML div content, or image files to PDF format using various libraries and modules.

## Features

- **Excel to PDF Conversion:** Converts Excel files (`.xlsx`, `.xls`) to PDF format.
- **HTML Div to PDF Conversion:** Converts HTML div content to PDF.
- **Image to PDF Conversion:** Converts image files (`.jpg`, `.png`, `.gif`, etc.) to PDF.

## Getting Started

### Prerequisites

- Python 3.x
- Install required libraries using `pip install -r requirements.txt`

### Usage

1. For Excel to PDF conversion:
    ```bash
    python excel_to_pdf.py input_excel_file.xlsx output_pdf_file.pdf
    ```

2. For HTML div to PDF conversion:
    ```bash
    python div_to_pdf.py input_html_file.html output_pdf_file.pdf
    ```

3. For Image to PDF conversion:
    ```bash
    python image_to_pdf.py input_image_file.jpg output_pdf_file.pdf
    ```

## Libraries Used

- **openpyxl:** For Excel file handling.
- **pdfkit:** For converting HTML content to PDF.
- **Pillow:** For image handling and conversion to PDF.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
