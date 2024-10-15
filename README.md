# National Day 

This project is a simple web application that displays the national day(s) for countries around the world based on the current date.

## Features

- Automatically detects the current date
- Displays the national day(s) for countries celebrating on the current date
- Shows country flags using the [flagcdn.com](https://flagcdn.com/) API
- Responsive design using Bootstrap

## How it works

The application uses a JavaScript array containing information about national days for various countries. When loaded, it:

1. Determines the current date
2. Checks the data array for any countries with a national day matching the current date
3. If matches are found, it displays the country name(s) and flag(s)
4. If no matches are found, it displays a message indicating there are no national days today

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- [flagcdn.com](https://flagcdn.com/) for flag images

## Setup

To run this project locally:

1. Clone the repository or download the HTML file
2. Open the HTML file in a web browser

No server or build process is required as this is a client-side application.

## Customization

You can easily customize the project by modifying the `data` array in the JavaScript section. Each country object in the array has the following properties:

- `name`: The name of the country
- `code`: The two-letter country code (used for fetching the flag image)
- `data`: The date of the national day in text format
- `intdate`: The date of the national day in MM/DD format

## Contributing

Contributions to improve the project or add more countries/national days are welcome. Please feel free to submit a pull request or open an issue.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This project is for educational purposes only. Please ensure you have the right to use any country flags or national day information in your specific use case.
