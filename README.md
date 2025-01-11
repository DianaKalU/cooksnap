# CookSnap - Recipe Finder

CookSnap is a web application that allows users to search for recipes by entering a list of ingredients. The app fetches recipe data from the Edamam API and displays the results, including ingredients, recipe details, and a link to the full instructions.

## Features
- **Ingredient-based Search**: Enter ingredients to find recipes.
- **Responsive Design**: Works seamlessly on various screen sizes.
- **Detailed Results**: Displays recipe images, ingredient lists, and a link to the full recipe.
- **API Integration**: Uses the Edamam Recipe Search API for fetching recipes.

---

## Technologies Used
- **HTML**: Markup structure for the web application.
- **CSS**: Styling for responsive and visually appealing design.
- **JavaScript**: Core logic for API interaction and dynamic content rendering.

---

## Project Structure
```
CookSnap/
├── index.html       # Main HTML file
├── style.css        # CSS file for styling
├── script.js        # JavaScript file for functionality
```

---

## Prerequisites
To run this project locally, ensure you have the following:
- A modern web browser (e.g., Chrome, Firefox).
- An active internet connection (to fetch recipes via the Edamam API).

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/DianaKalU/cooksnap.git
   cd cooksnap
   ```

2. Open `index.html` in your preferred web browser:
   ```bash
   open index.html
   ```

3. Enjoy using CookSnap!

---

## How to Use

1. Enter ingredients in the search box (e.g., "chicken, rice").
2. Click the **Search** button.
3. Browse through the displayed recipes.
4. Click on **View Recipe** to see detailed cooking instructions on the original source website.

---

## API Integration
CookSnap leverages the Edamam Recipe Search API. Update the API credentials in `script.js` if needed:
```javascript
const response = await fetch(`https://api.edamam.com/search?q=${searchValue}&app_id=YOUR_APP_ID&app_key=YOUR_APP_KEY&from=0&to=10`);
```

Replace `YOUR_APP_ID` and `YOUR_APP_KEY` with your own API credentials from [Edamam](https://developer.edamam.com/).

---

## Screenshots
### Search Page
![CookSnap Search Page](path/to/screenshot1.png)

### Recipe Results
![Recipe Results](path/to/screenshot2.png)

---

## Future Enhancements
- Add pagination for more results.
- Include dietary filters (e.g., vegetarian, keto, etc.).
- Display loading indicators during API calls.
- Enhance error handling for API failures.

---

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork.
4. Open a pull request.

---

## Acknowledgments
- **[Edamam API](https://developer.edamam.com/)**: For providing recipe data.
- **Community**: For supporting open-source projects.

Enjoy using CookSnap and happy cooking! 🥗✨
