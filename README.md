# Modern Vehicle Tax Calculator - Turkey

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A sleek, single-page web application designed to demystify the complex tax structure of new vehicles in Turkey. This tool provides a detailed breakdown of a vehicle's final price, reverse-calculating the base cost from the turnkey price and clearly visualizing the amounts for ÖTV (Special Consumption Tax) and KDV (VAT).

---

*Replace the URL below with a path to a screenshot of your application to make this README more engaging.*

![Application Screenshot](https-path-to-your-project-screenshot.png)

---

### ✨ Key Features

-   **Detailed Tax Calculation:** Accurately reverse-calculates the tax-free base price, ÖTV amount, and KDV (VAT) amount from the final turnkey price.
-   **Multiple Vehicle Types:** Supports different tax brackets for:
    -   Gasoline / Diesel
    -   Hybrid
    -   Electric Vehicles
-   **Dynamic Brackets:** Automatically uses the correct ÖTV brackets based on the vehicle's base price and engine specifications (cylinder capacity for combustion/hybrid, motor power for electric).
-   **Interactive Donut Chart:** Visually represents the distribution of the final price between the vehicle's base cost, ÖTV, and KDV.
-   **Insightful Analysis:**
    -   Calculates how many months of minimum-wage work are required to pay off the total tax amount.
    -   Compares the tax paid for a fossil fuel or hybrid vehicle to a similarly priced electric vehicle, highlighting potential tax savings.
-   **Modern UI:** A clean, dark-themed, and fully responsive interface built with Tailwind CSS.
-   **Showcase Section:** Features a list of the most affordable new cars currently available in the Turkish market.

---

### 🚀 Technologies Used

-   **Frontend:**
    -   **HTML5:** The structural foundation of the application.
    -   **Tailwind CSS:** For rapid, utility-first styling (via CDN).
    -   **Vanilla JavaScript:** Powers all the calculation logic, DOM manipulation, and interactive elements.

---

### 🛠️ How to Use

This project is entirely self-contained in a single HTML file and requires no installation or build steps.

1.  **Clone or download the repository:**
    ```bash
    git clone [https://github.com/vkaiber/arac-vergisi-hesaplayici.git](https://github.com/vkaiber/arac-vergisi-hesaplayici.git)
    ```
2.  **Open the file:**
    -   Navigate to the project directory and open the `index.html` file in any modern web browser.

That's it! You can now start analyzing vehicle prices.

---

### ⚖️ Disclaimer

This tool is intended for informational and educational purposes only. The calculations are based on the ÖTV and KDV rates embedded within the source code at the time of development. These rates are subject to change by government regulation. The author is not responsible for any financial decisions made based on the results from this application. Always consult official sources for the most current tax information.

---

### 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find a bug, please feel free to:

1.  **Fork** the Project.
2.  Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a **Pull Request**.

---

### 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
