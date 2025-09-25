# 🎬 usePopcorn

A movie search and watchlist app built with **React**, as part of the Jonas Schmedtmann React course. The project demonstrates core React concepts like components, props, state, effects, and custom hooks.

---

## 🚀 Features

- Search movies using the OMDb API
- Add movies to your personal watchlist
- Rate movies after watching
- Persist your watchlist between sessions with local storage
- Clean, responsive UI

---

## 📦 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/usepopcorn.git
   cd usepopcorn
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

---

## 🔑 Environment Variables

This project requires an API key from [OMDb API](https://www.omdbapi.com/).

1. Create a file named `.env` in the project root (same folder as `package.json`).
2. Add your API key like this:

   ```env
   REACT_APP_OMDB_KEY=your_api_key_here
   ```

3. Restart the development server after adding the `.env` file.

⚠️ Note: The `.env` file is ignored by Git, so you need to create your own locally.

---

## 📖 Acknowledgements

This project is part of [Jonas Schmedtmann's React Course](https://www.udemy.com/course/the-ultimate-react-course/).
