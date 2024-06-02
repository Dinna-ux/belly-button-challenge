# belly-button-challenge
# Belly Button Biodiversity Dashboard

Welcome to the Belly Button Biodiversity Dashboard! This interactive dashboard allows users to explore the microbial biodiversity of human navels based on samples collected from volunteers. Users can select a volunteer ID from the dropdown menu to visualize the top 10 microbial species (OTUs) found in that individual's navel, as well as the associated metadata.

This project uses Plotly.js for creating the interactive charts and D3.js for data manipulation and DOM manipulation.

## Files in this Repository

- **index.html**: Main HTML file containing the structure of the dashboard.
- **static/js/app.js**: JavaScript file containing the code to create the dashboard and handle user interactions.
- **samples.json**: JSON file containing the data used for the dashboard, including names, metadata, and samples.
- **static/css/style.css**: CSS file for styling the dashboard.

## Dashboard Layout

The dashboard is divided into two main sections:

1. **Dropdown Menu**: Users can select a volunteer ID from the dropdown menu (`#selDataset`). This dropdown is populated with the list of volunteer IDs (`names`) available in the `samples.json` file.

2. **Charts and Metadata Panel**:
   - **Bubble Chart**: Shows the distribution of all OTUs found in the selected individual's navel.
   - **Bar Chart**: Displays the top 10 OTUs found in the selected individual's navel.
   - **Metadata Panel**: Displays demographic information (age, ethnicity, gender, etc.) for the selected individual.

## How to Use the Dashboard

1. **Select a Volunteer ID**:
   - Use the dropdown menu to select a volunteer ID from the list.
   - The charts and metadata panel will update based on the selected volunteer ID.

2. **Interact with Charts**:
   - Hover over the Bubble Chart to see the OTU ID and the number of samples.
   - Hover over the Bar Chart to see the OTU ID, OTU label, and sample value.

## Running the Dashboard

To run the dashboard locally, follow these steps:

1. Clone the repository to your local machine:

git clone https://github.com/your-username/belly-button-biodiversity.git
cd belly-button-biodiversity

markdown
Copy code

2. Open the `index.html` file in your web browser.

3. Select a volunteer ID from the dropdown menu to see the dashboard in action.

## Dependencies

- **Plotly.js**: Used for creating interactive charts.
- **D3.js**: Used for data manipulation and DOM manipulation.

## Credits

This project was completed as part of the Data Analytics Bootcamp at Monash University, Australia
