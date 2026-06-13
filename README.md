# Equatorial-Power-Operations-Dashboard

An interactive dashboard for visualizing and analyzing weekly purchase data across multiple sites. This dashboard provides insights into revenue, energy consumption, and customer metrics with filtering capabilities and multiple chart visualizations.

## Features

- **Interactive Visualizations**: Multiple chart types, including line charts, bar charts, and summary metrics
- **Filtering Options**: Filter data by site and month to focus on specific information
- **Summary Metrics**: Key performance indicators for revenue, energy consumption, customer counts, and ARPU
- **Responsive Design**: Works on both desktop and mobile devices
- **Data Table**: Detailed tabular view of all data with proper formatting

## Data Source

This dashboard uses actual purchase data from multiple sites, including:
- Bugarula
- Kishenyi
- Gakagati
- Kashiraboba
- Bunyakiri
- Buyumbu
- Mugote
- Lolwe

The dashboard reads the published `Dashboard` tab in the connected Google Sheet at runtime. The available date range is derived from the sheet, so newly added months appear without changing the HTML.

The page refreshes the live CSV every five minutes and whenever an inactive tab becomes visible again. A manual **Refresh data** button is also available.

## Technologies Used

- HTML5, CSS3, JavaScript
- Chart.js for data visualizations
- Google Fonts (Roboto) for typography
- GitHub Pages for hosting

## How to Use

1. Use the site filter to focus on specific locations
2. Select a date range to view a particular reporting period; the initial range automatically ends at the latest available month
3. Choose different metrics to visualize from the dropdown
4. Hover over charts to see detailed values
5. Scroll down to view the complete data table

## Hosting on GitHub Pages

This dashboard is hosted on GitHub Pages for easy access without any server requirements.

Live demo: [https://kagodo707.github.io/Equatorial-Power-Operations-Dashboard/](https://Kagodo707/Equatorial-Power-Operations-Dashboard/)

## Installation

No installation required! Simply open the `index.html` file in any modern web browser, or visit the GitHub Pages URL.

## File Structure


## Customization

To customize this dashboard with your own data:
1. Replace the CSV data in the JavaScript section of index.html
2. Update the chart configurations if needed
3. Modify the color scheme by changing the CSS variables

## Browser Support

This dashboard works in all modern browsers, including:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/Kagodo707/Equatorial-Power-Operations-Dashboard/issues).

## Contact

Your Name - [Emmanuel Kagodo](kagsemma@gmail.com)

Project Link: [https://kagodo707.github.io/Equatorial-Power-Operations-Dashboard/](https://Kagodo707/Equatorial-Power-Operations-Dashboard/)

