# User Search Card Application

This project is a responsive user search card application built using HTML, CSS, and JavaScript. It displays user information in visually appealing profile cards and allows users to search for profiles in real time.

As the user types a name into the search field, JavaScript filters the user data and displays only the matching profile cards. If no user matches the search query, a helpful “No user found” message is displayed.

## Features

- Real-time user search
- Dynamic profile card generation
- User name, email, bio, and profile image
- Case-insensitive search
- No-results message
- Blurred image overlay effect
- Responsive layout
- Clean and simple user interface

## Technologies Used

- HTML5
- CSS3
- JavaScript

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/user-search-card.git
   ```

2. Open the project folder.

3. Open the `index.html` file in your browser.

## Project Structure

```text
user-search-card/
│
└── index.html
```

## How It Works

The user data is stored in a JavaScript array. The `filter()` method searches the array according to the entered name, while `forEach()` generates and displays the matching cards dynamically.

## Future Improvements

- Add category-based filtering.
- Add sorting by name.
- Add pagination.
- Add a dark and light theme switcher.
- Connect the application to a backend API.
- Add user profile detail pages.

## Author

Abhay Chandel
