
# My AI - File Upload and Chat Application

**Live Website**: [https://my-ai-146ba.web.app/](https://my-ai-146ba.web.app/)

My AI is a React-based web application that allows users to upload files (PDF, Word, Excel) or process Google Docs/Sheets links to extract text and interact with the content via a chatbot powered by the Gemini API.

## Features

- **File Upload and Text Extraction**:
  - Supports **PDF**, **Word (.docx)**, and **Excel (.xlsx)** files.
  - Automatically extracts text from uploaded files for further interaction.

- **Google Docs/Sheets Integration**:
  - Accepts public Google Docs and Sheets links.
  - Extracts and processes content from the provided link.

- **Chatbot Functionality**:
  - Users can ask questions related to the uploaded/processed content.
  - Powered by the Gemini API for intelligent responses.

- **Responsive Design**:
  - Fully responsive and optimized for both desktop and mobile devices.
  - Clean and modern UI with an intuitive user experience.

## Installation

Follow these steps to run the application locally:

### Prerequisites
- [Node.js](https://nodejs.org/) installed on your machine.
- Basic knowledge of React.js.

### Steps
1. Clone the repository:
   ```bash
   git clone  https://github.com/Inch62/My_AI.git
   cd my-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Add your Gemini API key:
   - Open `src/services/geminiApi.js`.
   - Add your Gemini API credentials in the file.

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## File Structure

```
src/
├── App.js          # Main application logic
├── App.css         # Styling for the application
├── services/
│   └── geminiApi.js # API service for interacting with Gemini API
└── index.js        # Application entry point
```

## How to Use

1. **File Upload**:
   - Click **Choose File** to upload a PDF, Word, or Excel file.
   - Click **Upload & Extract** to process the file and extract its text.

2. **Google Docs/Sheets**:
   - Paste a public Google Docs or Sheets link into the text box.
   - Click **Process Google Docs/Sheets** to extract its content.

3. **Chat**:
   - After uploading or processing, type your question in the chat box.
   - Click **Send** or press **Enter** to receive responses related to the content.

4. **Extract Another File**:
   - Click **Extract Another File** to reset the app and upload or process a new file.

## Technologies Used

- **Frontend**: React.js
- **Libraries**:
  - `xlsx`: For Excel file parsing.
  - `mammoth`: For Word file parsing.
  - `pdf.js`: For PDF text extraction.
- **API**: Gemini API for chatbot responses.
- **Styling**: CSS with responsive design.

## Responsive Design

The app is fully responsive and adapts to different screen sizes:
- On mobile devices, the main card automatically adjusts its height to provide a better user experience.
- Buttons, input fields, and other components are optimized for smaller screens.

## Screenshots

### Desktop View
![Desktop View](screenshots/desktop-view.png)

### Mobile View
![Mobile View](screenshots/mobile-view.png)

## Future Enhancements

- Add support for additional file formats.
- Integrate advanced NLP for more intelligent chatbot responses.
- Improve UI/UX with animations and themes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits

- Developed by **Inchara**.
- Libraries and APIs:
  - `xlsx`, `mammoth`, `pdf.js`
  - Gemini API

---

### Contact

For any questions or issues, please contact **Inchara** at [your-email@example.com](mailto:your-email@example.com).
