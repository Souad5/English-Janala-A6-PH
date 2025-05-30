# English Janala - Assignment 6

English Janala is an interactive web application designed to help users learn English vocabulary and grammar in an engaging and user-friendly way. This project is part of the Programming Hero course's Assignment 6.

## Features

- **Interactive Lessons**: Users can select lessons to learn new vocabularies.
- **Responsive Design**: The application is fully responsive and adapts to different screen sizes.
- **Dynamic Content**: Lessons and vocabularies are fetched dynamically from an API.
- **FAQ Section**: Provides answers to frequently asked JavaScript-related questions.
- **Modal Popups**: Displays detailed information about vocabularies in a modal.
- **User Authentication**: Simple login functionality with a predefined password.

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling, including Tailwind CSS and DaisyUI for utility-first and component-based design.
- **JavaScript**: For interactivity and dynamic content loading.
- **SweetAlert2**: For beautiful alert popups.
- **Font Awesome**: For icons.
- **API Integration**: Fetches data from the Programming Hero API.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Souad5/English-Janala-A6-PH.git
   ```
2. Navigate to the project directory:
   ```bash
   cd English-Janala-A6-PH
   ```
3. Open the `index.html` file in your browser to view the application.

## Usage

1. Enter your name and the password `123456` to log in.
2. Explore the lessons and select one to view vocabularies.
3. Click on a vocabulary to view its details in a modal.
4. Use the FAQ section to learn about JavaScript concepts.

## Project Structure

```
English-Janala-A6-PH/
├── assets/               # Images and other static assets
├── script/               # JavaScript files
│   └── script.js         # Main script for interactivity
├── style.css             # Custom styles
├── index.html            # Main HTML file
└── README.md             # Project documentation
```

## API Endpoints

- **Fetch all levels**: `https://openapi.programming-hero.com/api/levels/all`
- **Fetch vocabulary by level**: `https://openapi.programming-hero.com/api/level/{id}`
- **Fetch vocabulary details**: `https://openapi.programming-hero.com/api/word/{id}`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- **Programming Hero**: For providing the API and project guidelines.
- **DaisyUI** and **Tailwind CSS**: For simplifying the design process.
- **SweetAlert2**: For enhancing user experience with beautiful alerts.
