# Bizcardx: Business Card Data Extraction

Bizcardx is a Streamlit-based web application designed to extract and manage information from business cards using Optical Character Recognition (OCR) technology. This project leverages EasyOCR for text extraction, SQLite for database management, and several Python libraries for handling and displaying images.

## Problem Statement

In today's fast-paced business world, managing contacts and networking effectively can be challenging. Business professionals often accumulate a large number of business cards, making it difficult to keep track of contacts and their details. Manually entering information from business cards into digital formats is time-consuming and prone to errors. Bizcardx addresses this problem by providing a streamlined, automated solution for extracting and organizing information from business cards.

## Features

- **Upload Business Card**: Easily upload images of business cards in various formats (JPG, PNG, JPEG).
- **OCR Extraction**: Automatically extract text from the uploaded business card using EasyOCR.
- **Data Review and Editing**: Review extracted information and make any necessary edits directly within the app.
- **Database Integration**: Store and manage business card details in an SQLite database.
- **Search and Filter**: Search and filter through the stored contacts.
- **View and Modify**: View and modify existing business card information.
- **Remove Records**: Delete business card records from the database.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/bizcardx.git
    cd bizcardx
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run b.py
    ```

## Usage

1. **Upload a Business Card**: Click on the "Upload Business Card Image" button and select an image file.
2. **Review Extracted Data**: The application will display the extracted text for review. You can edit any field if necessary.
3. **Confirm and Upload**: Click the "Confirm & Upload" button to save the data to the database.
4. **View Database Table**: View the stored business card details in the "Database Table" section.
5. **Modify or Remove Entries**: Select a cardholder name to view or modify details, or use the "Remove" button to delete entries from the database.

## Dependencies

- **Streamlit**: For creating the web application interface.
- **Pandas**: For data manipulation and analysis.
- **SQLite3**: For database management.
- **EasyOCR**: For text extraction from images.
- **Pillow (PIL)**: For image processing.
- **io**: For handling byte objects.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements or features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [your-email@example.com].

