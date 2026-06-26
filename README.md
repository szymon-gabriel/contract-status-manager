Contract Status Manager v1.0

A professional utility tool engineered to streamline contract coordination workflows. It eliminates manual data entry errors and accelerates operational efficiency by enabling direct Excel file processing and status management through an intuitive, interactive interface.
🚀 Live Demo & Sandbox

To ensure data privacy and demonstrate the tool's effectiveness in a controlled environment, a dedicated simulation interface has been deployed.

Test the application live here: [https://szymon-gabriel.github.io/contract-status-manager/]
🛠️ How to Install & Test

    Clone or download this repository to your local machine.

    Open the project folder.

    Use the provided "Test_Contracts_List.xlsx" file for immediate testing.

    Open index.html in your web browser.

    Click "Load selected file" and select the "Test_Contracts_List" file.

    Modify statuses or dates directly in the table and click "Save Excel report" to generate the finalized document.

🏗️ Project Structure

    index.html - Main application interface and data processing logic.

    style.css / dmstyle.css - Custom UI styling supporting light and dark mode themes.

    lib/scripts/xlsx.full.min.js - Core SheetJS library for high-performance spreadsheet parsing.

    Test_Contracts_List.xlsx - Sample dataset for testing application functionality.

⚙️ Tech Stack

    JavaScript (ES6): Logic for file parsing, data manipulation, and state management.

    SheetJS (xlsx): Advanced spreadsheet processing and data export.

    HTML5 / CSS3: Modern, responsive interface with a focus on usability and data clarity.

    LocalStorage API: Persistence layer allowing users to resume work on previously loaded data.