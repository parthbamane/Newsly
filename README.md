# 📰 Newsly

**Newsly** is a modern news website built with **React.js** that delivers the latest headlines in real time. It fetches news from the [NewsAPI](https://newsapi.org/) based on country, category, and page size.

## 🚀 Features
- Live top headlines from multiple categories and countries
- Responsive and clean UI built using React
- Fetching data from NewsAPI with dynamic props

## 🔧 Tech Stack
- **React.js**
- **NewsAPI**
- **Bootstrap / CSS Modules** (if used)

## 🌐 API Endpoint Format Used

```
https://newsapi.org/v2/top-headlines?country=${props.country}&category=${props.category}&apiKey=YOUR_API_KEY&pagesize=${props.pagesize}
```

> Replace `YOUR_API_KEY` with your actual API key from [NewsAPI.org](https://newsapi.org/)

---

## 📦 Getting Started

### 1. Clone the repository
```
git clone https://github.com/your-username/newsly.git
cd newsly
```

### 2. Install dependencies
```
npm install
```

### 3. Setup environment variables
Create a `.env` file in the root directory and add:
```
REACT_APP_NEWS_API_KEY=your_api_key_here
```

### 4. Start the development server
```
npm start
```

---

## 📁 Folder Structure
```
newsly/
│
├── public/
├── src/
│   ├── components/
│   │   ├── News.js
│   │   └── NewsItem.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── .env
├── package.json
└── README.md
```

---

## 💡 Author

Built by Parth Bamane ([https://github.com/](https://github.com/parthbamane))

Give a ⭐️ if you found this project helpful!
