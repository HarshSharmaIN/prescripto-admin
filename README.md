# Prescripto Admin

Prescripto Admin is a modern, responsive admin dashboard built with React and Vite. It provides a comprehensive interface for managing appointments, patients, doctors, and earnings, making it ideal for healthcare administration and clinic management.

## Features

- ⚡ **Fast Development**: Powered by Vite for lightning-fast builds and hot module replacement.
- 🧩 **Component-Based**: Modular React components for maintainability and scalability.
- 🎨 **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- 🔒 **ESLint Integration**: Enforced code quality with custom ESLint configuration.
- 🔄 **React Router**: Seamless navigation between pages.
- 📦 **API Ready**: Easily integrate with REST APIs using Axios.
- 📅 **Appointment Management**: Manage appointments, patients, and doctors efficiently.
- 📊 **Dashboard Analytics**: Visualize earnings and other key metrics.
- 🖼️ **Rich Asset Library**: Includes SVG icons for UI consistency.

## Project Structure

```
.
├── public/                # Static assets
├── src/
│   ├── assets/            # SVGs and asset management
│   ├── components/        # Reusable React components
│   ├── context/           # React context providers
│   ├── pages/             # Application pages (Dashboard, Patients, Appointments, etc.)
│   ├── App.jsx            # Main app component
│   ├── index.css          # Global styles (Tailwind)
│   └── main.jsx           # Entry point
├── .env                   # Environment variables
├── package.json           # Project metadata and scripts
├── tailwind.config.js     # Tailwind CSS configuration
├── vite.config.js         # Vite configuration
├── eslint.config.js       # ESLint configuration
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/HarshSharmaIN/prescripto-admin.git
   cd prescripto-admin
   ```

2. **Install dependencies:**

   ```sh
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**

   ```sh
   npm run dev
   # or
   yarn dev
   ```

   The app will be available at [http://localhost:5174](http://localhost:5174).

### Building for Production

```sh
npm run build
# or
yarn build
```

### Linting

```sh
npm run lint
# or
yarn lint
```

## Configuration

- **Environment Variables:**  
  Create a `.env` file in the root directory to store sensitive configuration (API keys, endpoints, etc.).
  ```sh
  VITE_BACKEND_URL=Backend Url of Prescripto App
  VITE_STREAM_API_KEY=Stream API Key
  ```

- **Vite Config:**  
  See `vite.config.js` for dev server and plugin setup.

- **ESLint:**  
  Custom rules are defined in `eslint.config.js`.

- **Tailwind CSS:**  
  Tailwind is configured in `tailwind.config.js` and imported in `src/index.css`.

## Scripts

| Command           | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Build for production     |
| `npm run lint`    | Run ESLint               |
| `npm run preview` | Preview production build |

## Dependencies

- React
- Vite
- Tailwind CSS
- Axios
- React Router DOM
- Framer Motion
- React Hot Toast
- React Toastify
- Lucide React

## License

This project is licensed under the MIT License.

---

**Maintained by [Your Name/Organization].**

For questions or support, please open an issue or contact the maintainer.
