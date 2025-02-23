# 🌟 Market Dash: Stock Market Dashboard 🌟

> **Track, Analyze, and Invest in the Stock Market with Ease! 🚀**

**Market Dash** is a modern, responsive web app that lets you monitor stock market data, manage your personal portfolio, track your watchlist, and participate in a vibrant community of investors. Whether you are a beginner or a seasoned pro, **Market Dash** has everything you need in a single dashboard. 📊📈

---

## 🚀 Features:

- **User Authentication**: Secure sign-up, login, and profile management using **Appwrite** 🔐
- **Stock Watchlist**: Easily track your favorite stocks 🏦
- **Portfolio Tracker**: Keep an eye on your investments 📈
- **Real-Time Stock Data**: Live stock data with interactive **Chart.js** graphs 📉
- **Dark Mode**: Because everyone loves dark mode! 🌙
- **Responsive Design**: Mobile-friendly, designed with **TailwindCSS** 📱
- **Error Tracking**: Integrated **Sentry** for error reporting and monitoring 🚨
- **Form Validation**: **Zod** handles all your form validations with ease 📝
- **Community Discussions**: Join and engage with other investors 💬
- **DayJS**: Effortlessly handle dates, times, and time zones ⏰

---

## 💻 Technologies Used

- **HTML5** & **CSS3** for building the base and styling 🖥️
- **Chart.js** for interactive data visualization 📊
- **Zod** for validation 🔏
- **Sentry** for error tracking 🛠️
- **Appwrite** for backend services (auth, database) 🛠️
- **Axios** for making HTTP requests 🚚
- **TanStack Query** for data fetching ⚡
- **Day.js** for date formatting 🗓️
- **Lodash** for utility functions 🧰

---

## 🔥 Project Structure

```bash
market-dash/
│
├── index.html                # Home page (Static base HTML)
├── 404.html                  # Custom error page (optional)
├── assets/                   # Folder for images, icons, etc.
│   ├── logo.svg              # Logo image
│   └── favicon.ico           # Favicon
│
├── css/                      # Custom CSS styles
│   ├── main.css              # Tailwind CSS (compiled)
│   └── custom.css            # Custom styles
│
├── scripts/                  # JavaScript files for functionality
│   ├── components/           # Reusable UI components
│   ├── pages/                # Page-specific JS files
│   ├── utils/                # Utility functions (virtual DOM, routing)
│   └── app.js                # Main app file
├── libs/                     # External libraries (via CDN)
├── .gitignore                # Git ignore file
├── README.md                 # This file
└── favicon.ico               # Favicon
```

---

## 🚀 Getting Started

### 1. **Clone the repo**

```bash
git clone https://github.com/yourusername/market-dash.git
cd market-dash
```

### 2. **Install Parcel**

Parcel is the bundler used to compile assets:

```bash
npm install --global parcel-bundler
```

### 3. **Start the Development Server**

Run the development server with:

```bash
parcel index.html
```

Go to **`http://localhost:1234`** in your browser to start interacting with the app. 🎉

### 4. **Appwrite Setup**

Make sure to configure **Appwrite** SDK for authentication, databases, and API calls in your `appwrite.js` file. You’ll need your **Appwrite Project ID** and **API Keys**.

### 5. **Build for Production**

To generate a production-ready build, run:

```bash
parcel build index.html
```

This creates the `/dist` folder with the optimized files. 🚀

---

## 📦 Libraries Included (via CDN)

- **Zod** – Form validation
- **TanStack Query** – Data fetching
- **Sentry** – Error tracking
- **TailwindCSS** – Styling
- **ShadCN/UI** – UI components
- **Appwrite** – User authentication and data
- **Day.js** – Date manipulation
- **Axios** – HTTP requests
- **Lodash** – Utility functions
- **Chart.js** – Interactive charts
- **UUID** – Generate unique IDs

---

## 🌟 Screenshots

**1. Home Page**

![Home Page](https://via.placeholder.com/600x300?text=Home+Page+Screenshot)

**2. Dashboard View**

![Dashboard](https://via.placeholder.com/600x300?text=Dashboard+Screenshot)

**3. Watchlist**

![Watchlist](https://via.placeholder.com/600x300?text=Watchlist+Screenshot)

---

<!-- ## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

--- -->

<!-- ## 📞 Contact

If you have any questions or need help, feel free to reach out! ✉️

- Email: [youremail@example.com](mailto:youremail@example.com)
- Twitter: [@yourusername](https://twitter.com/yourusername)

--- -->

🚀 **Happy investing!** 🚀

---
