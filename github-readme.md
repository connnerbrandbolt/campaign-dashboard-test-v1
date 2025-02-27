# Campaign Dashboard

A responsive and interactive dashboard for monitoring ad campaign performance with a focus on ROAS (Return on Ad Spend).

## Features

- **Real-time campaign monitoring**: Track the performance of up to 100 campaigns at once
- **ROAS-based highlighting**: Visual indicators for campaign performance (green for good ROAS, red for poor ROAS)
- **Toggle controls**: Easily activate or pause campaigns directly from the dashboard
- **Filtering options**: Filter by account, status, ROAS performance, and search terms
- **Dashboard statistics**: View total active campaigns, average ROAS, total spend, and total revenue
- **Pagination**: Navigate through large datasets with ease
- **Responsive design**: Works well on desktop and mobile devices
- **Data refresh**: Manual refresh option to update campaign data

## Automation Ready

This dashboard includes special markers for automation tools:
- `#page-status[data-status="ready"]` element appears when the page is fully loaded
- Campaign toggle buttons have unique data attributes for automation targeting

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/campaign-dashboard.git
   cd campaign-dashboard
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python to create a simple HTTP server
   python -m http.server
   ```

3. Visit `http://localhost:8000` in your browser

## Deployment

Deploy to GitHub Pages:

1. Go to your repository settings
2. Navigate to the "Pages" section
3. Select your main branch as the source
4. Click "Save"

Your dashboard will be available at `https://yourusername.github.io/campaign-dashboard/`

## Automation Script

This dashboard is designed to work with the included Playwright automation script (`gumloop-monitor.js`), which can:

- Automatically monitor campaign performance
- Toggle campaigns based on ROAS thresholds
- Run on a schedule or manually
- Generate reports of changes made

## License

MIT
