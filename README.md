# 📰 NewsView – Category-Wise Live News App

**NewsView** is a fully functional, category-wise live news application developed using **React** and the **NewsAPI**. It allows users to browse real-time news articles across multiple categories such as Business, Technology, Sports, Health, and more. The app is designed with a clean, responsive UI and smooth navigation to provide an intuitive user experience.

This project is inspired by [CodeWithHarry’s React tutorial](https://www.youtube.com/watch?v=x9p-4QGh-OI&list=PLu0W_9lII9agx66oZnT6IyhcMIbUMNMdt&index=22), and is further enhanced with user-centric design principles, modular components, and dynamic routing.

---

## 🚀 Features

- 🔴 **Live News Feed**  
  Fetches the latest news from NewsAPI in real time, ensuring fresh and up-to-date content.

- 📁 **Category-Wise Browsing**  
  Users can easily navigate between different categories (e.g., General, Sports, Business, Technology) using React Router.

- 🔄 **Pagination Support**  
  News is displayed page-wise, with navigation controls to load more articles without cluttering the interface.

- 🌀 **Loading Spinner**  
  A visual indicator is displayed while data is being fetched, improving perceived performance and UX.

- 📱 **Responsive Design**  
  Optimized for mobile, tablet, and desktop using modern layout techniques.

- 💡 **Component-Based Architecture**  
  Built using reusable and modular React components to ensure clean code and scalability.

---

## 🧱 Tech Stack

| Technology       | Usage                                      |
|------------------|--------------------------------------------|
| React            | Front-end library for building UI          |
| NewsAPI          | REST API to fetch real-time news           |
| React Router     | Enables category-based navigation          |
| Bootstrap / CSS  | For layout and responsive design           |
| JavaScript (ES6+)| Core logic and state management            |

---

## 🛠️ Installation & Setup

## 📁 Clone the Repository

```bash
git clone https://github.com/your-username/NewsView-Category-Wise-Live-News-App.git
cd NewsView-Category-Wise-Live-News-App
```

---


## 📦 Install Dependencies

```bash
npm install
```

🔑 Add Your API Key using .env
Go to https://newsapi.org/ and sign up for a free account.

After logging in, copy your API key.

In the root directory of your project, create a file named:

bash
Copy
Edit
```
.env
```
Inside .env, add the following line (replace with your actual API key):

env
Copy
Edit
REACT_APP_NEWS_API_KEY=your_api_key_here

---
⚠️ Important:

The variable must start with REACT_APP_ for Create React App to recognize it.

Restart your dev server (npm start) after creating or editing .env.

Never share your .env file or API key publicly. It's automatically ignored by Git using .gitignore.

---

▶️ Start the App
bash
Copy
Edit
npm start
Visit http://localhost:3000 in your browser.

---

🧪 How It Works
App.js: Manages routes and layout.

News.js: Fetches and renders news based on the selected category.

Navbar.js: Provides category navigation using React Router links.

Spinner.js: Displays loading animation.

API Handling: Uses fetch API to call NewsAPI endpoints with category and page parameters.

---

🎓 Learning Outcome
Gained hands-on experience with React fundamentals like components, props, and state.

Learned to handle API integration and async operations.

Practiced routing and pagination in a real-world scenario.

Improved understanding of responsive design and UI/UX best practices.
---

📄 License
This project is for learning and educational purposes. You are free to use, modify, and share it.
---

🙋‍♀️ Author
Tejaswini Venkatesh Gudigar
Computer Science and Engineering Graduate



