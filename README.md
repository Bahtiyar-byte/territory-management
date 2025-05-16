# Territory Management Dashboard

A modern React TypeScript dashboard for visualizing sales territory management data.

## Getting Started

### Prerequisites
- Node.js (v14 or newer)
- npm or yarn

### Installation and Running the Application

1. Navigate to the project directory:
```bash
cd /Users/haydarovbahtiyar/Desktop/territory_management/web
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
src/
├── components/
│   ├── Dashboard/
│   │   └── widgets/         # Chart components
│   ├── Header/              # Top navigation
│   ├── Layout/              # Page layout
│   └── Sidebar/             # Side navigation
├── pages/
│   └── Dashboard/           # Main dashboard page
├── utils/                   # Utilities and data
└── App.tsx                  # Main app component
```

## Features

- Modern, responsive UI design
- Interactive charts and visualizations
- Metric cards for KPI tracking
- Expandable chart widgets
- Loading states and animations
- Clean sidebar navigation

## Technologies

- React 18
- TypeScript
- CSS modules
- Recharts for data visualization

## Development

This project is structured for a Spring Boot + React TypeScript application, with the frontend providing visualization for data coming from a Java backend.

### Key Components:

- **MainLayout**: Provides the overall page structure with sidebar navigation
- **Dashboard**: Contains the metrics and chart widgets
- **Chart Widgets**: Reusable components for different types of data visualization
  - MetricCard
  - BarChartWidget
  - PieChartWidget
  - FunnelChartWidget
  - ColumnChartWidget

For development, mock data is provided to simulate API responses.
