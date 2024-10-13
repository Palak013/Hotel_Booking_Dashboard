# Hotel_Booking_Dashboard

The Hotel Booking Dashboard is a single-page application that visualizes booking data. The dashboard includes four different charts that update based on a user-selected date range. The charts provide insights into the number of visitors per day, per country, and break down the number of adults, children, and babies.

Features
Date Selector: Filter the data based on a user-selected date range.
Charts:
Time Series Chart: Shows the number of visitors per day (adults + children + babies).
Column Chart: Displays the number of visitors per country.
Sparkline Charts: Two small charts showing total visitors for adults and children with trend lines.
Responsive Design: Dashboard is fully responsive and works across different screen sizes.
Tech Stack
Frontend: React.js (with TypeScript)
Charts Library: ApexCharts (https://apexcharts.com/)
State Management: React Hooks
Backend (Optional): Node.js / Express for serving data through an API
Data Source: JSON file or a simple API that serves hotel booking data
Installation
Prerequisites
Node.js (>= 14.x)
npm or yarn (preferred)
Steps
Clone the repository:


git clone https://github.com/your-username/Hotel_Booking_Dashboard.git
cd Hotel_Booking_Dashboard
Install dependencies:


yarn install
Start the development server:

yarn start
Access the app: Open http://localhost:3000 in your browser.

Usage
Data Source: You can choose to store the booking data in a JSON file or a database. If using a database, ensure that your backend API is running and serves the required data to the frontend.

Date Selection: Use the date picker at the top of the dashboard to filter the data displayed in the charts.

Charts:

The Time Series Chart shows the number of visitors per day.
The Column Chart visualizes the number of visitors by country.
The Sparkline Charts show the total visitors for adults and children.
Project Structure:

├── public
├── src
│   ├── api          # API setup for fetching data (if using a backend)
│   ├── components   # React components for charts and other UI elements
│   ├── data         # Static data (if using a JSON file)
│   ├── hooks        # Custom React hooks
│   ├── styles       # CSS/SCSS files
│   └── utils        # Utility functions (e.g., for data formatting)
├── README.md
├── tsconfig.json
└── package.json
