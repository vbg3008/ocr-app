# Django OCR Application

Welcome to the Django OCR Application! This application leverages the power of Tesseract OCR to extract text from images. It is built using the Django framework and provides users with the flexibility to either upload an image or capture one using a live webcam feed.

## Features

- **Image Upload:** Users can upload images directly from their devices for text extraction.
- **Webcam Capture:** Users can capture an image using their device's webcam and process it instantly.
- **Text Extraction:** The application uses Tesseract OCR to extract text from the uploaded or captured images.
- **Display Results:** Extracted text is displayed on the screen, with an option to download it as a text file or PDF.
- **Data Storage:** The extracted text and related metadata are stored in a database for future reference.

## Technologies Used

- **Django:** The web framework used to build the application.
- **Tesseract OCR:** The Optical Character Recognition engine used to extract text from images.
- **Bootstrap:** Used for creating a responsive and user-friendly interface.
- **SQLite/MySQL/SSMS:** Databases used to store extracted text and metadata.

## Setup Instructions

### Prerequisites

- Python 3.x
- Django 4.x
- Tesseract OCR (Make sure it is installed and accessible in your system's PATH)
- A database (SQLite, MySQL, or SSMS)

### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/vbg3008/ocr-app.git
    cd ocr-app
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Tesseract:**
   - Install Tesseract OCR based on your operating system.
   - Ensure `pytesseract` can locate the Tesseract executable.

4. **Configure the Database:**
   - Update the `settings.py` file in your Django project with your database configuration.

5. **Run Migrations:**
    ```bash
    python manage.py migrate
    ```

6. **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```

7. **Access the Application:**
   - Open your web browser and navigate to `http://127.0.0.1:8000/` to start using the application.

## Usage

1. **Upload an Image:**
   - Click on "Upload Image" in the navigation bar.
   - Select an image file and upload it.
   - View the extracted text on the results page.

2. **Capture an Image:**
   - Click on "Capture Image" in the navigation bar.
   - Use your webcam to take a photo.
   - The captured image will be processed, and the text will be extracted.





## Acknowledgements

- **Tesseract OCR:** For providing a robust OCR engine.
- **Django:** For the powerful web framework.
- **Bootstrap:** For the responsive UI components.

---

Thank you for using the Django OCR Application! If you encounter any issues or have suggestions, please do reach out.
