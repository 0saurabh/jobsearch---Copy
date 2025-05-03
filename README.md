# JobSearch Application

A modern Job Search Single Page Application (SPA) built with React, Vite, and Bootstrap 5. This application allows users to search for jobs using Boolean logic and various filters.

## Features

- Boolean search functionality (AND, OR, NOT) for refined job searching
- Advanced filtering by job category, employment type, date posted, and more
- Fully responsive design that works on all devices
- Detailed job view with comprehensive information
- Saved jobs feature for keeping track of interesting positions
- Modern UI built with Bootstrap 5

## Tech Stack

- React 18 with hooks for state management
- Vite for fast development and optimized builds
- Bootstrap 5 for responsive design
- React Router for navigation
- Axios for API requests
- JSearch API from RapidAPI for job data

## Getting Started

### Prerequisites

- Node.js 14.x or later
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/jobsearch.git
   cd jobsearch
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory based on `.env.example`:
   ```
   VITE_RAPID_API_KEY=your_rapidapi_key_here
   ```

   You can get an API key by signing up at [RapidAPI](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch).

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`

## Usage

### Search for Jobs

1. Enter keywords in the search bar. Use Boolean operators for more precise searches:
   - `Developer AND React` - Jobs containing both "Developer" and "React"
   - `Frontend OR Backend` - Jobs containing either "Frontend" or "Backend"
   - `Developer NOT Junior` - Jobs containing "Developer" but not "Junior"

2. Use filters to narrow down results:
   - Select job category
   - Choose employment type
   - Filter by date posted
   - Toggle remote-only jobs

### View Job Details

Click on any job card to view detailed information about the position, including:
- Job description
- Qualifications
- Responsibilities
- Benefits
- Salary information (when available)

### Save Jobs

Click the bookmark icon on any job card or in the job details modal to save a job for later reference. View all saved jobs in the "Saved Jobs" section.

## Building for Production

To build the application for production:

```
npm run build
```

This will generate optimized files in the `dist` directory.

## License

[MIT](LICENSE)
