# Reservia React [REFACTORED]
Originally called "Reservia Vacation Tool " and now "booki-holoday-app", this app is a mock-up that allows users to find accommodations and activities in the city of their choice.
This project is a refactored version of the original HTML/CSS site "Turn-Mock-ups-Into-a-Web-Page" (find t on my github), now built from scratch using React for a modern, component-based architecture.


## APP STRUCTURE BELOW: 
```
Here’s a diagram of my app’s structure based on my workspace:
- All styling is managed in `src/assets/css/style.css` and component-specific CSS files.
- Images are organized by type and size in images and `src/assets/images/`.


booki-holiday-app/
├── public/
│   └── images/
│       ├── activites/
│       └── hebergements/
├── src/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   ├── images/
│   │   └── ...
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── SearchSection.jsx
│   │   ├── Filters.jsx
│   │   ├── Accommodations.jsx
│   │   ├── MostPopular.jsx
│   │   ├── Activities.jsx
│   │   ├── Footer.jsx
│   │   └── (corresponding .css files)
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── README.md
```

**Component hierarchy (as rendered in App.jsx):**
```
<App>
  ├── <Header />
  ├── <SearchSection />
  ├── <Filters />
  ├── <div class="main-sections-row">
  │     ├── <section id="accom"><Accommodations /></section>
  │     └── <section id="most-popular"><MostPopular /></section>
  ├── <Activities />
  └── <Footer />
</App>
```




## Features
- **Browse Accommodations:** View a list of available places to stay, filterable by theme (e.g., budget, atmosphere).
- **Discover Activities:** Explore activities and attractions in the selected city.
- **Responsive Design:** Fully responsive layout, adapting seamlessly to mobile, tablet, and desktop devices.
- **Modern UI:** Built with React components for maintainability and scalability.
- **Filter System:** Easily filter accommodations by various criteria.

## Getting Started

### Prerequisites
- Node.js (v16+ recommended by time of development)
- npm

### Installation guide

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd booki-holiday-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:...](http://localhost:....) in your browser.

## Credits
- Original design and mockups: [Reservia Project](https://ebosterix.github.io/Project-2-Turn-Mock-ups-Into-a-Web-Page)
- Refactored to React by [Okile Moses Ebokorait]

## License

## Credits This project is for educational purpose only. Contact me in any other case.
