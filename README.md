# Bank Info

A simple, interactive web tool that allows users to look up information about banks in Vietnam. Search by full Vietnamese name, full English name, short name, SWIFT code, stock code, or bank type to get detailed information about each bank.

## 🚀 Live Demo

Check out the live demo: [https://www.xn--msiu-goa8b.vn/github/bank-info](https://www.xn--msiu-goa8b.vn/github/bank-info)

## ✨ Features

- **Multiple Search Fields** – Search by full Vietnamese name, full English name, short name, SWIFT code, stock code, or bank type
- **Real-Time Suggestions** – Get up to 5 autocomplete suggestions as you type
- **Keyboard Navigation** – Navigate suggestions with arrow keys and press Enter to search
- **Detailed Results** – View comprehensive information for each bank, including:
  - Full Vietnamese name
  - Full English name
  - Short name(s)
  - Stock code
  - SWIFT code
  - Bank type
  - Website
  - Mobile app links (iOS and Android)
- **Previous Name Highlighting** – Banks with a `next_name` field are visually highlighted
- **Clean Interface** – Simple, user-friendly design with a clear layout
- **Responsive** – Works on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- JSON (bank data)

## 📁 Project Structure

```
bank-info/
├── index.html    # Main HTML file
├── style.css     # Stylesheet
├── script.js     # JavaScript logic for bank lookup
├── data.json     # Bank information data
└── README.md     # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/bank-info.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd bank-info
   ```
   
3. **Run the application with a local server**

⚠️ Important: This project loads data from a JSON file, so you need to use a local development server instead of opening `index.html` directly in your browser to avoid CORS issues.

- **Using VS Code** – Install the "Live Server" extension, right-click on `index.html`, and select "Open with Live Server"
- **Using Python** – Run `python -m http.server` (Python 3) or `python -m SimpleHTTPServer` (Python 2) and open `http://localhost:8000`
- **Using Node.js** – Install `http-server` globally (`npm install -g http-server`) and run `http-server` in the project folder

## 📝 How It Works

1. **Select a search field** – Choose from the dropdown menu:
   - Tên đầy đủ (VN) – Full Vietnamese name
   - Tên đầy đủ (EN) – Full English name
   - Tên ngắn – Short name
   - Mã SWIFT – SWIFT code
   - Mã chứng khoán – Stock code
   - Loại ngân hàng – Bank type
2. **Enter a search query** – Type your search term into the input field. Suggestions will appear in real-time as you type.
3. **Select a suggestion or press Enter** – Click on a suggestion or press Enter to perform the search.
4. **View the results** – A table displays all matching banks with their detailed information:
   - Full Vietnamese name
   - Full English name
   - Short name(s)
   - Stock code / SWIFT code
   - Bank type
   - Website (with a direct link)
   - Mobile app links (iOS and Android)

**Keyboard Shortcuts:**

- **Arrow Down / Arrow Up** – Navigate through suggestions
- **Enter** – Search with the selected suggestion or current input
- **Escape** – Close the suggestions list

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open-source and available under the MIT License.
