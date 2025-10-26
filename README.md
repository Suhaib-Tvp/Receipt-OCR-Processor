# Receipt OCR Processor

A Python-based Optical Character Recognition (OCR) system for extracting and processing data from receipt images. This tool automatically identifies and structures key information from receipts including items, prices, dates, and transaction details.

## Features

- **Image Preprocessing**: Enhances image quality for better OCR accuracy.
- **Multi-format Support**: Handles various receipt layouts and formats.
- **Structured Data Extraction**: Identifies and categorizes:
  - Store information
  - Transaction dates and receipt numbers
  - Itemized purchases with prices
  - Financial totals (subtotal, total, cash, change)
  - Cashier information
- **CSV Export**: Saves extracted data to structured CSV files.
- **Multi-language Support**: Handles special characters and mixed languages.

### Prerequisites
- Python 3.7+
- Tesseract OCR engine
