<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# Geniuses Visualization Project

This project is a D3.js visualization inspired by Giorgia Lupi's design, displaying historical figures arranged according to a Kabbalistic Sephirot structure.

## Project Context

The visualization shows the 100 geniuses of language identified in Harold Bloom's book "Genius", arranged in a Sephirot structure with various visual attributes representing:

- Field of contribution (colors)
- Wikipedia page views (node size)
- Time period (positioning)
- Lustre level (numbered indicators)

## Code Style Preferences

- Use ES6+ JavaScript syntax
- Maintain the existing D3.js approach for consistency
- Preserve the visual style inspired by Giorgia Lupi's design
- Document complex visualization calculations

## Implementation Notes

- The Sephirot structure is a hierarchical diagram used in Kabbalah, with 10 nodes representing different aspects
- Genius nodes are positioned in arcs around their assigned Sephirot
- The CSV data should be processed to ensure proper sorting by time period
- Use consistent formatting for tooltips and interactions
