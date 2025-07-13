# Compose Compiler Reports Comparator

## Overview
The **Compose Compiler Reports Comparator** is a web-based tool designed to compare two Jetpack Compose compiler reports, specifically focusing on composables and classes. It provides a side-by-side comparison of composables (with details like skippability, restartability, and parameter count) and classes (with details like stability and fields). This tool is useful for Android developers working with Jetpack Compose to analyze and optimize their UI components by comparing changes between different reports.

## Features
- Upload and compare two Jetpack Compose compiler reports.
- Visualize differences in **Composables** (e.g., skippable, restartable, parameter count).
- Visualize differences in **Classes** (e.g., stability, fields).
- Simple and intuitive HTML interface for displaying results.
- Responsive design for easy use on various devices.

## Usage
1. **Run the Tool**: Open the `compose-compiler-reports.html` file directly in a web browser.
2. **Upload Reports**: Use the provided input fields to upload two Compose compiler reports (JSON or text format).
3. **View Comparison**: Once uploaded, the tool parses the reports and displays the results in two sections:
   - **Composables Comparison**: Shows composable names, skippability, restartability, and parameter counts for both reports.
   - **Classes Comparison**: Shows class names, stability, and fields for both reports.
4. **Analyze**: Compare the differences between the two reports to identify changes in composable or class behavior, aiding in performance optimization.

<img width="1777" height="726" alt="image" src="https://github.com/user-attachments/assets/b70aabb7-6d67-4a51-845a-01a0700a6dc2" />


## Project Structure
- `compose-compiler-reports.html`: The main HTML file containing the structure and placeholder content for the comparator tool.
- (Future additions): JavaScript for parsing reports, CSS for enhanced styling, and support for additional report formats.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a detailed description of your changes.

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Future Enhancements
- Add JavaScript to parse and process uploaded JSON/text reports dynamically.
- Implement a diff view to highlight specific changes between reports.
- Add support for exporting comparison results as a downloadable file.
- Enhance the UI with modern CSS frameworks (e.g., Tailwind CSS or Bootstrap).

## Contact
For questions or feedback, please open an issue on this repository.
