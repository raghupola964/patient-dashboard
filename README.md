# Patient Dashboard

## Overview

This project is a patient dashboard built for a Coalition Technologies skills test. It displays Jessica Taylor's monthly blood pressure data (October 2023 to March 2024) in a graph, using Google Charts for visualization. The dashboard was developed with HTML, Tailwind CSS, and vanilla JavaScript, ensuring a responsive and accessible user interface. Key features include a dynamic graph, patient details, metrics (respiratory rate, temperature, heart rate), diagnostic list, and lab results.

## Features

- **Blood Pressure Graph**: Displays systolic and diastolic blood pressure data for the last 6 months using Google Charts.
- **Responsive Design**: Built with Tailwind CSS to ensure the dashboard works on both desktop and mobile devices.
- **Accessibility**: Includes ARIA labels and semantic HTML for better accessibility.
- **Fallback Mechanism**: Uses mock data if the API fails, ensuring the app remains functional.
- **Clean UI**: Matches the Adobe XD template provided, with a random company logo and no patient images.

## Tech Stack

- **HTML**: Structure of the dashboard.
- **Tailwind CSS**: Styling for a responsive and modern UI.
- **JavaScript**: Logic for fetching data and rendering the graph.
- **Google Charts**: Visualization of blood pressure data.
- **Axios**: For making API requests to fetch patient data.

## How to Run

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/[YourGitHubUsername]/patient-dashboard.git
   ```
2. **Open the Project**:
   - Navigate to the project folder.
   - Open `index.html` in a web browser (e.g., Chrome, Firefox).
3. **Dependencies**:
   - The project uses CDN links for Tailwind CSS, Axios, and Google Charts, so no additional installation is required.
   - Ensure you have an internet connection for the CDNs to load.

## Project Structure

- `index.html`: The main file containing the HTML, CSS (via Tailwind), and JavaScript for the dashboard.
- `README.md`: Documentation for the project.

## API Usage

- The dashboard fetches patient data from the API endpoint `https://fedskillstest.coalitiontechnologies.workers.dev` using Basic Auth (username: `coalition`, password: `skills-test`).
- If the API fails, the app falls back to mock data to ensure functionality.

## Screenshots

*(You can add a screenshot of the dashboard here by taking a screenshot and uploading it to the repository. For now, this section is a placeholder.)*

## Live Demo

*(You can host the project on GitHub Pages or another platform and add the link here. For now, this section is a placeholder.)*

## License

This project is licensed under the MIT License—see the LICENSE file for details.

## Contact

- **Name**: Raghu Pola
- **Email**: raghupola964@gmail.com
