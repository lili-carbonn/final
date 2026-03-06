# S&P 500 Interactive Dashboard

## Project Description

This is an interactive dashboard that helps you explore and understand S&P 500 stock market data.

## Contents

### Main Files
- **index.html**
- **SP500.csv**
- **README.md**

### Other Important Files
### External Dependencies
- **D3.js v4** - JavaScript library for creating SVG-based visualizations
- **GitHub Repository** - [https://github.com/lili-carbonn/final](https://github.com/lili-carbonn/final)

## Dashboard Features

### Four Interconnected Visualizations

1. **Price Analysis Chart**
   - Displays S&P 500 price movements over time
   - Interactive brush tool for zooming into specific time periods
   - Moving averages (50-day and 200-day) for trend analysis
   - Professional legend in top-left corner

2. **Returns Analysis Chart**
   - Shows daily percentage changes
   - Zero line separates positive from negative returns
   - Reveals market sentiment and emotional responses to events

3. **Volatility Analysis Chart**
   - Displays 30-day rolling volatility
   - Measures market uncertainty and risk levels
   - Spikes during market stress periods

4. **Drawdown Analysis Chart**
   - Shows percentage decline from previous market peaks
   - Essential for understanding potential investment risk
   - Blue shaded area represents magnitude of corrections

### Interactive Features
- **Brush and Zoom**: Drag on the price chart to examine specific time periods
- **Coordinated Updates**: All charts update together when selecting time ranges
- **Enhanced Tooltips**: Hover over any data point for detailed information
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Reset Function**: Return to full time range view

## Technical Implementation

### Libraries Used
- **D3.js v4** - Primary visualization library for SVG-based charts
- **Pure HTML/CSS/JavaScript** - No frameworks required for instant loading

### Key Features
- **Performance Optimized**: Efficient rendering for 2,500+ data points
- **Accessibility**: Screen reader friendly with ARIA labels
- **Professional Tooltips**: Enhanced information display on data points
- **Data Processing**: Comprehensive metrics calculation including moving averages, volatility, and drawdown analysis

## Project Website

**Live Dashboard**: [https://lili-carbonn.github.io/final/](https://lili-carbonn.github.io/final/)

The dashboard is hosted on GitHub Pages and provides immediate access to the interactive visualizations.

## Screen-Cast Video

**Project Video**: [https://youtu.be/LJ89qpB46FU](https://youtu.be/LJ89qpB46FU)

A 2-minute screen-cast demonstrating the dashboard's features and explaining the project's key insights and contributions.

## Non-Obvious Interface Features

### 1. Coordinated Chart Updates
When you select a time range on the price chart using the brush tool, all other charts automatically update to show the same time period. This allows for comprehensive analysis of specific market events across all metrics simultaneously.

### 2. Moving Average Toggle
The "Moving avgs" checkbox controls the display of 50-day and 200-day moving averages on the price chart. These smoothed trend lines help identify longer-term market direction and potential support/resistance levels.

### 3. Professional Legend Positioning
The legend is positioned in the top-left corner of the price chart, providing clear identification of chart elements without interfering with data visualization.

### 4. Responsive Design
The dashboard automatically adapts to different screen sizes, ensuring optimal viewing experience across devices without requiring separate mobile versions.

### 5. Data Processing
The dashboard calculates multiple financial metrics in real-time:
- Daily returns from price data
- 30-day rolling volatility using standard deviation
- Drawdown analysis showing peak-to-trough declines
- Moving averages for trend identification
