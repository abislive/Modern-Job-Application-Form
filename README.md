# Modern Job Application Form

**Made by ABISLIVE**

A responsive, animated job application form built with HTML, CSS, and vanilla JavaScript.  
The form auto-generates essential fields like Post Number, Closing Date, and Interview Date, and provides a unique reference number on submission for tracking. It also includes a print option for offline submission.
To view the page please visit - https://abislive.github.io/Modern-Job-Application-Form/

## ✨ Features

- **Auto‑generated fields** – Post Number, Closing Date, and Interview Date are automatically populated when the page loads (and regenerated on reset).
- **Unique reference number** – On submission, a tracking reference (e.g., `APP-XXXXXXXX`) is generated and displayed in a modal. The reference can be copied to the clipboard.
- **Print option** – A dedicated button allows users to print the form for in‑person submission.
- **Modern UI/UX** – Clean card layout, smooth animations, focus/hover effects, and responsive design.
- **Form validation** – Built‑in HTML5 `required` attributes and visual feedback on invalid fields.
- **Local storage** – Submitted applications (including reference) are stored in the browser's `localStorage` (simulated backend).
- **Customizable sections** – Education, Employment History, References, and Declaration sections included.
- **Title & Identification Type dropdowns** – Multiple options for title and ID type.

## 🛠️ Technologies Used

- **HTML5** – Semantic structure and form elements.
- **CSS3** – Custom properties, gradients, animations, flexbox, and print media queries.
- **Vanilla JavaScript** – DOM manipulation, event handling, date calculations, and localStorage integration.

## 📁 File Structure
├── index.html # Main application form (self-contained)

└── README.md # Project documentation

## 🚀 How to Use

1. **Clone or download** the repository.
2. Open `index.html` in any modern web browser.
3. Fill out the required fields.  
   *Note: Post Number, Closing Date, and Interview Date are pre‑filled automatically.*
4. Click **Submit Application** to generate and view your tracking reference.
5. Use **Copy Reference** to save it, or click **Close**.
6. To print a blank form, click **Print Form** (the print layout hides all buttons and adjusts styling).

## 📌 Important Notes

- The generated reference number is stored only in the browser’s `localStorage` for demo purposes. In a production environment, you would replace this with server‑side storage.
- The form uses `checkValidity()` for built‑in validation; no external libraries are required.
- The print stylesheet ensures the form prints cleanly on A4 paper.

## 🔧 Customization

- **Auto‑generated dates**: The closing date is set to 14 days from today, and the interview date to 28 days. You can adjust these values in the `generateClosingDate()` and `generateInterviewDate()` functions inside the `<script>` tag.
- **Post Number format**: Modify the `generatePostNumber()` function to change the prefix or number pattern.
- **Title / ID Type options**: Edit the `<option>` elements inside the corresponding `<select>` tags.
- **Colors & styles**: The CSS variables at the top of the `<style>` block allow quick theming.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
If you find any bugs or have suggestions, please open an issue or submit a pull request.
