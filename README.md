# MultiLanguage Invoice Extractor


MultiLanguage Invoice Extractor is a web application that utilizes the Gemini Pro Vision model to extract information from invoices. It allows users to upload an image of an invoice and provide a prompt, and then generates a response based on the content of the image and the provided prompt.

## Features
- Upload Invoice Image: Users can upload an image of an invoice in JPG, JPEG, or PNG format.
- Input Prompt: Users can provide a prompt to specify the information they want to extract from the invoice.
- Real-time Analysis: The application provides real-time feedback during the analysis process, indicating that the analysis is in progress.
- Error Handling: If an error occurs during the analysis, the application displays an error message to the user.
- MultiLanguage Support: The Gemini Pro Vision model supports multiple languages, allowing users to analyze invoices in various languages.
## Usage
- Input Prompt: Enter the desired prompt in the "Input Prompt" text box.
- Upload Invoice Image: Click on the "Choose an image of the invoice..." button to upload an image of the invoice.
- Analyze Invoice: Click on the "Tell me about the invoice" button to initiate the analysis process.
- View Results: Once the analysis is complete, the application displays the extracted information from the invoice.
## Technologies Used
- Streamlit: Streamlit is used to create the web application and interface with the Gemini Pro Vision model.
- PIL (Python Imaging Library): PIL is used to process and display images uploaded by users.
- Google GenerativeAI: The Gemini Pro Vision model, provided by Google GenerativeAI, is used for analyzing invoices and generating responses.
