# STEAM Integration Generator (Web Version)

## Overview

The **STEAM Integration Generator (Web Version)** is a browser-based tool designed to help educators and curriculum developers generate creative and practical STEAM (Science, Technology, Engineering, Arts, and Mathematics) integration ideas and lesson plans. Built using **HTML, CSS, and JavaScript**, it ensures broad accessibility without requiring installation.

> **Note:** A Python-based version of this tool is also available. You can find it [here](https://github.com/rajat-ed/steam-integration-generator). This web version offers a lightweight, platform-independent alternative.

### Key Features

✅ **Generate STEAM Integration Ideas** – Quickly receive innovative and actionable STEAM integration ideas for any topic.
✅ **Create Detailed Lesson Plans** – Generate structured lesson plans following the **5E Model** (Engage, Explore, Explain, Elaborate, Evaluate) with STEAM elements.
✅ **Dark/Light Mode** – Switch between modes for a comfortable user experience inspired by Apple’s design language.
✅ **Markdown Output** – View generated content in a clean, easy-to-read format.
✅ **Text Export** – Download STEAM ideas and lesson plans as `.txt` files for easy sharing and documentation.
✅ **Fully Client-Side** – Runs entirely in your browser, ensuring privacy and ease of use with no installation required.

---

## How to Use

### 1. Open in Browser
Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge, etc.).

### 2. Get a Gemini API Key
You need a **Google Gemini API key** to generate content. Get a free API key from [Google AI for Developers](https://makersuite.google.com/app/apikey).

### 3. Enter API Key
In the navigation bar, enter your Gemini API key in the "Gemini API Key" field.

### 4. Set Input Parameters
Fill in the **Input Parameters** panel:
- **Topic:** Enter a subject/topic (e.g., "Photosynthesis," "Simple Machines").
- **Learning Outcomes:** List desired outcomes (e.g., "Understand the process, Identify key components").
- **Age Group:** Specify the target learners (e.g., "10-12," "Middle School").
- **Output Type:** Select **"Ideas"** for integration ideas or **"Lesson Plan"** for a structured lesson plan.
- **Class Time (minutes):** Indicate lesson duration.
- **Location (Optional for Lesson Plan):** Specify a setting (e.g., "Science lab," "Outdoor garden").

### 5. Generate Content
Click **"Generate"** to create your STEAM integration ideas or lesson plan.

### 6. View & Export
- The generated content appears in the **Output Panel**.
- Click **"Export"** to download the content as a `.txt` file.
- Click **"Clear All"** to reset fields and start fresh.

### 7. Customize Experience
- **Dark/Light Mode:** Toggle the theme for comfortable reading.
- **Update API Key:** Click "API Key" to enter a new key anytime.
- **Learn More:** Click "About" to view project details.

---

## Technologies Used

- **HTML** – Provides the webpage structure.
- **CSS** – Styles the interface with an Apple-inspired theme (`styles.css`).
- **JavaScript** – Handles user input, API calls, and dynamic content updates (`script.js`).
- **Google Gemini API** – Powers AI-driven STEAM content generation.

---

## Important Notes & Limitations

🔒 **API Key Security** – Your API key is stored **only in your browser’s memory** and is **not saved** after a refresh or closure.

🌍 **Language** – Content is generated in **English**.

💡 **Client-Side Operation** – No server or database is required; everything runs locally in your browser.

🌐 **Internet Required** – The tool needs an active internet connection to interact with the Gemini API.

---

## License

This project is open-source under the [MIT License](https://opensource.org/licenses/MIT). Feel free to **use, modify, and distribute** it for educational and personal purposes.

🚀 **Start generating engaging STEAM integration ideas today!**

