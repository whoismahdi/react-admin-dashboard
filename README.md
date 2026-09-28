# React Admin Dashboard

A modern and responsive admin dashboard built with **React** and **Material UI**.

This project is a frontend dashboard application designed to demonstrate reusable UI components, data visualization, tables, calendar management, forms, routing, and responsive layouts.

## Features

* Responsive admin dashboard layout
* Collapsible sidebar navigation
* Material UI based interface
* Dashboard overview with statistics and charts
* Data tables with sorting, filtering, and pagination
* Calendar with event creation and deletion
* Multiple chart types
* Form handling and validation
* Client-side routing
* Custom application theme and color tokens
* Responsive layout for different screen sizes

## Tech Stack

### Core

* React 19
* React Router
* JavaScript (ES6+)

### UI & Styling

* Material UI
* Emotion
* React Pro Sidebar

### Data Visualization

* Nivo Bar
* Nivo Line
* Nivo Pie
* Nivo Geo

### Data Grid

* MUI X Data Grid

### Calendar

* FullCalendar

### Forms & Validation

* Formik
* Yup

## Project Structure

```text
src/
├── components/
│   ├── ...
│
├── scenes/
│   ├── dashboard/
│   ├── contacts/
│   ├── calendar/
│   ├── forms/
│   ├── charts/
│   └── ...
│
├── data/
│   └── ...
│
├── theme.js
├── App.js
└── index.js
```

The project is organized into reusable components and separate scenes/pages to keep the application maintainable as it grows.

## Getting Started

### Prerequisites

Make sure you have installed:

* Node.js
* npm

### Installation

Clone the repository:

```bash
git clone https://github.com/whoismahdi/react-admin-dashboard.git
```

Navigate to the project directory:

```bash
cd react-admin-dashboard
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## Available Scripts

### `npm start`

Runs the application in development mode.

### `npm test`

Runs the test suite.

### `npm run build`

Creates an optimized production build.

## Dashboard Modules

The dashboard currently includes several sections:

* **Dashboard**: Overview with statistics, charts, and key metrics
* **Contacts**: Data grid for displaying and managing contact information
* **Calendar**: Interactive calendar with event management
* **Forms**: Form examples with validation
* **Charts**: Bar, line, pie, and geographical visualizations
* **Other Pages**: Additional dashboard views and UI examples

## Customization

The application uses a centralized theme configuration for colors and styling.

This makes it easier to maintain a consistent visual system across components and pages.

The dashboard also uses custom styling for components such as:

* Sidebar
* Data Grid
* Charts
* Calendar
* Navigation
* Buttons and interactive elements

## Screenshots

Screenshots can be added here as the project UI evolves.

```text
Coming soon
```

## Learning Goals

This project is also being used as a practical React project to explore:

* Component-based architecture
* React hooks
* Routing
* UI component libraries
* Data visualization
* Responsive layouts
* State management
* Reusable components
* Working with third-party React libraries
* Adapting libraries to their current APIs

## License

This project is intended for learning and portfolio purposes.

---

Built with React and Material UI.
