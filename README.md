![sugarbrix logo](https://res.cloudinary.com/adrienne/image/upload/c_scale,w_220/v1507178537/sugarbrix/sugarbrix_logo_darker.png)

#### Visualizing sugar in food

Why the name? °Bx (degrees Brix) represents the amount of sugar by weight in a liquid. 1°Bx = 1g sucrose / 100g solution

### Background

SugarBrix is a data visualization of sugar levels in common foods.

The goal is to bring greater awareness of sugar in everyday foods through interactive graphics.

### Features

+ Compare sugar levels among a database of 100+ popular food items
+ Benchmark sugar levels against teaspoons of sugar, Krispy Kreme doughnuts, or Hershey's Kisses
+ Filter by food categories: dessert, drinks, fast food, and fruit
+ Toggle unit size between 1 serving or 100 grams
+ Sort by net sugar weight or by percentage of weight

### Technologies

+ D3.js - data manipulation and dynamic rendering
+ Vanilla HTML and JavaScript - overall structure
+ D3.js and CSS - styling

---
## Dynamic Content Rendering with D3

By combining D3 `enter()` and `exit()` with Event Listeners, the chart updates dynamically based on user selection.

Users can filter by category, toggle the unit size, and sort by various sugar levels.

![filtering gif](https://res.cloudinary.com/adrienne/image/upload/v1507312290/sugarbrix/filtering.gif)

The unit of measurement selector allows users to compare against teaspoons, doughnuts, and chocolate kisses.

![benchmark gif](https://res.cloudinary.com/adrienne/image/upload/v1507312289/sugarbrix/changing_benchmark.gif)

## Responsive SVGs for Multi-Screen Compatibility

A responsive SVG scales all elements within the display chart while maintaining the same proportions.

![responsive gif](https://res.cloudinary.com/adrienne/image/upload/q_70/v1507312044/sugarbrix/responsive_svg.gif)

---
## Future Development
 + Search
    + Search by specific item names
 + Sugar calculator
    + Select items and calculate total sugar content
 + Expanded nutrition information and comparison
    + Expanded nutrition data on hover
    + Ability to select two items and compare
 + Sugar guideline calculator
    + Calculate recommended sugar intake based on AHA guidelines and user input
