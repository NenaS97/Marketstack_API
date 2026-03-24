# Marketstack API Documentation

---

## Project Overview

This project is a structured API documentation site built using **DITA XML**, designed to document and demonstrate the usage of the **Marketstack API**.

The goal of this project was not just to document an API, but to showcase:
- Structured authoring using DITA
- Clean, readable documentation design
- API testing and validation using Postman
- Deployment of documentation using GitHub Pages

---

## Technologies & Tools Used

- **DITA XML** - for structured documentation authoring  
- **VS Code** - for writing and managing DITA files  
- **Marketstack API** - open-source API for stock market data (https://marketstack.com/)
- **Postman** - for API testing and request validation  
- **HTML5 Output (DITA-OT)** - for generating the final documentation  
- **Custom CSS** - for UI styling and layout design  
- **Git & GitHub** - for version control and deployment  
- **GitHub Pages** - for hosting the live documentation  

---

## Documentation Structure

The project follows a modular DITA-based structure with:

### Index Page
- Centralized navigation  
- Clean UI with structured topic linking  

### Topic Pages
- Overview  
- Authentication  
- End-of-Day Data  
- Errors  
- Tickers Endpoint  
- Use Cases  

Each topic is structured with:
- Headings and subheadings  
- Paragraph content  
- Lists and bullet points  
- Tables for structured data  
- Code blocks for API examples  
- Notes for additional context  

---

## Components & Elements Used

The documentation includes:

- `<title>` - Topic titles  
- `<p>` - Paragraph content  
- `<ul>`, `<li>` - Lists and navigation  
- `<table>`, `<tr>`, `<td>` - Data representation  
- `<codeblock>` - API request examples  
- `<codeph>` - Inline code references  
- `<note>` - Highlighted informational sections  

These elements ensure clarity, readability, and a structured flow of information.

---

## Styling & UI (CSS)

Custom CSS was implemented to enhance the visual experience.

### Key Design Features:
- Dark theme with a deep blue background  
- Neon blue highlights for headings  
- Centered layout for index page  
- Responsive content alignment  
- Clean spacing and padding  

### Styled Components:
- Tables with borders and contrast backgrounds  
- Code blocks with contained styling  
- Inline code highlighting  
- Note boxes with visual emphasis  
- Navigation layout improvements  

---

## Deployment Setup

- Renamed `outputs` → `docs` for GitHub Pages  
- Moved all required assets inside `/docs`  
- Updated file paths for deployment compatibility  
- Configured GitHub Pages
---

## API Testing (Postman)

Postman was used to:
- Test API endpoints  
- Validate request/response behavior  
- Structure API workflows  

### Included:
- Postman Collection (`.json`)  
- Postman Environment (`.json`)  

These files can be imported directly into Postman.

---

## Final Output

👉 https://nenas97.github.io/Marketstack_API/

---
