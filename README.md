# Python Matplotlib

Matplotlib functions that are useful in visualizing data in data analysis.

## Visualization

> Depends  on which apsect of our data we want to demonstrate:

*  `` Data Value ``

*  `` Data Distribution ``

*  `` Data Concentration``

*  `` Data Composition ``





### Data Value

- [x] 1.0_Plot


- [x] 1.1_Series Plot
        
        
        Suitable for high granularity. You can used it to evaluate patterns and behavior in data over time.
        
        Especially good for time-series data like stock-price.
        
- [x] 1.1_Bar Plot

        Suitable for low granularity. You can use it to compare the difference among observations and evaluate the pattern.
        
        Example will be company annual revenue



### Data Distribution

- [x] 2.0_Histogram
        
        Good for demonstrating frequencies of the values.
        
        A good example will be comparing of gender (male vs females) in the SAT exam.
        
        Another in when comparing number of customer chooses Product A, Product B, and Product C.
        
        
- [x] 2.1_Box Plot
        
        To show the overall distribution of the data. It's visualized descriptive staistic, you see the maximum, the 3rd quartile, the median, the 1st quartile, and the minimum.
        


### Data Concentration

- [x] 3.0_Scatter Plot
        
        Requires two axes, shows the distribution pattern of the data, but more often used to evaluate if the data is concentrating in a certain area.
        
        Suitable for small to medium size samples.
        
        
- [x] 3.1_Hexagon Binning Plot (Heat Map)
        
        Suitable for large samples.
        
        It is easier to read where is the data concentrated on. the deeper the color, the more the area is intensively concentrated.
        
        

### Data Composition

- [x] 4.0_Pie Plot
        
        For cross-sectional data (at a certain point of time). shows the proportion of different parts in a sum. 
        
        Example: Revenue composition (ads, sales, promotions, etc..)
        
        
- [x] 4.1_Area Plot
        
        For time-series data (with composition changing through time.)
        
        The X axis usually represents time, and the thickness of each color shows the value of that variable. 
        
        Example: how is the revenue composition changing (chair, tables, lamps, ets)
        