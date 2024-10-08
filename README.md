**Handwritten-text-detector**

### Overview
This repository contains the source code for a web application built with Flask for performing Optical Character Recognition (OCR) on uploaded images. The application utilizes PyTorch Lightning and the Transformers library for deep learning-based OCR tasks.

### Features
- Upload images in various formats (png, jpg, jpeg, gif) for OCR processing.
- Real-time OCR processing of uploaded images.
- Display of extracted text from uploaded images.
- Error handling for invalid file formats and missing files.

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/roopeshkumarm/Handwritten-text-detector
   ```
2. Navigate to the cloned directory:
   ```
   cd Handwritten-text-detector
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

### Usage
1. Run the Flask application:
   ```
   python app.py
   ```
2. Access the application via a web browser at `http://localhost:5000`.
3. Upload an image file using the provided form.
4. Click the "Upload" button to initiate OCR processing.
5. View the extracted text displayed on the webpage.

### Dependencies
- Flask
- PyTorch Lightning
- Transformers
- PIL (Python Imaging Library) (pillow)

### File Structure
- **app.py**: Main Flask application file containing routes and OCR functionality.
- **templates/**: Directory containing HTML templates for rendering web pages.
  - **index.html**: Homepage template with file upload form and OCR results display.
- **uploads/**: Directory for storing uploaded images.
- **requirements.txt**: File containing a list of Python dependencies.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Author
[TEAM 404](https://github.com/roopeshkumarm)


### Acknowledgements
- This project utilizes pre-trained models from the Transformers library.
- Special thanks to the PyTorch and Flask communities for their valuable resources and documentation.

### Contributions
Contributions are welcome! If you would like to contribute to this project, please open an issue or submit a pull request.

### Support
For any inquiries or issues, please contact [email@example.com](kroopeshm@gmail.com).

### Roadmap
- Implement support for additional file formats.
- Improve OCR accuracy and performance.
- Enhance user interface with additional features.
- Integrate with cloud storage services for image uploads.
- Implement user authentication and authorization.

Feel free to suggest any other features or improvements you'd like to see in this project!

![image](https://github.com/user-attachments/assets/9fb25270-5553-4eb6-88ad-2ad7b757b0bd)

![image](https://github.com/user-attachments/assets/bbcea584-fe26-48f7-93bc-0a4b13e27815)

![image](https://github.com/user-attachments/assets/7ed959f3-6872-4f5f-9ef5-7cb7ac1151f2)







