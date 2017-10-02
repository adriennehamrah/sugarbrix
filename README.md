## SugarBrix - Visualizing sugar in food

*°Bx (degrees Brix) represents the amount of sugar by weight in a liquid. 1°Bx = 1g sucrose / 100g solution*

### Background

SugarBrix is a data visualization of sugar levels in common foods.

The goal is to bring greater awareness of sugar in everyday foods through interactive graphics.

### MVPs
+ Database of 100+ food items and sugar content
+ Animated transitions of sugar levels
+ Filter by categories - fruits, drinks, breakfast items, desserts, etc.
+ Search by specific food names
+ Infographic of AHA recommended sugar levels

### Wireframes
SugarBrix is a single page app with interactive graphics. 
Content regenerates depending on the following user actions: 
+ filter by category
+ sort (percentage of weight, total grams, highest-lowest, lowest-highest)
+ select unit of measurement (teaspoons, doughnuts, hershey's kisses)
+ search by specific food names

![sugarbrix wireframe](https://github.com/adriennehamrah/sugarbrix/blob/master/media/sugarbrix_wireframe.png)

### Technologies
+ Vanilla JavaScript for overall structure
+ D3 for DOM manipulation and rendering
+ CSS for styling
+ Webpack to bundle scripts

### Structure
+ `food.csv` -  store all sugar data and image except for units of measurement
+ `benchmarks.csv` - store sugar data and image urls for the three units of measurement
+ `index.html` - all HTMl and D3 logic
+ `sugarbrix.css` - all CSS


### Implementation Timeline
#### Over the weekend:
- [x] Complete [Maptime d3 Tutorial](http://maptimeboston.github.io/d3-maptime/#/)
- [x] Start collecting food data and images

#### Day 1: Setup and seeds
- [ ] Set up Node and Webpack
- [ ] Learn more about D3
- [ ] Determine food categories and add data for 100 food items (image and sugar content)

#### Day 2: D3
- [ ] Bind food objects to data using D3
- [ ] Add all logic for search, filter, sort

#### Day 3: CSS
- [ ] Add CSS styling
- [ ] Add transitions

#### Day 4: CSS and README
- [ ] Create infographic of AHA sugar levels
- [ ] Complete styling
- [ ] Create production README.md
