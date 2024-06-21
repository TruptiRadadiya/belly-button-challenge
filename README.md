# belly-button-challenge

## Belly Button Biodiversity Dashboard

This project involves creating an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes found in human navels. The dashboard includes visualizations such as bar charts, bubble charts, and demographic information panels, allowing users to interact with and analyze the data effectively.

### File structure

```
belly-button-challenge/
├── index.html                      # Main HTML file for the dashboard
├── samples.json                    # JSON file containing the dataset
├── static/
│   └── js/
│       └── app.js                  # JavaScript file for data processing and visualization
└── README.md                       # This README file
```

### What do you need?

- D3.js
- HTML/CSS
- JavaScript

### How to use the code?

1. Clone this repository to your local machine.
2. Navigate to the project directory and open the `index.html` file in a web browser to view the dashboard.

### Summary of Features

- Interactive Bar Chart:

  - Displays the top 10 OTUs found in an individual’s navel.
  - Hover over bars to see additional information.

- Bubble Chart:

  - Visualizes the distribution and relative abundance of OTUs for each sample.
  - Bubble size and color represent sample values and OTU IDs respectively.

- Demographic Info Panel:

  -Shows the metadata of the selected sample.
  -Updates dynamically based on user selection.

- Dropdown Menu:

  - Allows users to select different samples and updates all visualizations accordingly.

### Deployment

- Deployed the dashboard to GitHub Pages for easy access and sharing:
- `https://truptiradadiya.github.io/belly-button-challenge/`
