# Geniuses, Visualized - D3.js Project

This project creates a visualization inspired by Giorgia Lupi's design, displaying the historical figures (geniuses) from Harold Bloom's book "Genius" arranged in a Kabbalistic Sephirot structure.

## Project Structure

```
.
├── css/
│   └── style.css        # Styling for the visualization
├── data/
│   └── geniuses_dataset.csv  # Dataset of geniuses
├── js/
│   └── script.js        # D3.js visualization code
├── index.html           # Main HTML page
└── README.md            # This file
```

## Features

- Interactive visualization of 100 historical geniuses
- Data structured according to Kabbalistic Sephirot organization
- Visual encoding of multiple data dimensions:
  - Field of contribution (color)
  - Wikipedia page views (size)
  - Time period (positioning)
  - Lustre level (numbered indicators)
- Tooltips with detailed information
- Responsive design

## Data

The visualization uses a dataset of historical figures from Harold Bloom's "Genius" with the following attributes:
- Name
- Country of Origin
- Time Period
- Field of Contribution
- Assigned Sephirot
- Lustre
- Wikipedia Page Views
- Field Color

## Usage

Simply open the `index.html` file in a modern web browser to view the visualization.

## Technologies

- HTML5
- CSS3
- JavaScript
- D3.js v7

## Credits

- Design inspiration: Giorgia Lupi
- Original data source: Harold Bloom's "Genius" and Wikipedia
