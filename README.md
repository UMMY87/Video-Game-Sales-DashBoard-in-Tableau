# Video Game Sales DashBoard in Tableau
Creating a graph and dashboard using Tableau involves several steps. Here's a step-by-step guide to help you build graph:

### Step-by-Step Procedure
#### 1. Connect to Your Data
1. Open Tableau.
2. Click on "Connect" and select the type of file or database where your data is stored (e.g., Excel, CSV, SQL Server, etc.).
3. Here I selected “Text file”.
4. Select and Load your data into Tableau.

#### 3. Create a New Worksheet
1. Click on the "Sheet 1" tab at the bottom to create a new worksheet and name it `Line Graph`.

#### 4. Create Line Graph
1.	Drag the `Year` field to the Columns shelf.
2.	Drag the `Global Sales` field to the Rows shelf.
3.	Drag the `Platform` field to the Filters shelf to enable filtering by platform.
4.	Drag the `Genre` field to the Marks shelf to enable filtering by genre.
5.	Drag the `Genre` field to the Color shelf under Marks to color code the lines by platform.
6.	Drag the `Global Sales` field to the Label shelf under Mark to label code the lines by platforms.
7.	Ensure the `Marks` type is set to "Line".
8.	Optionally, drag the `Genre` field to the Color shelf or another shelf if you want to differentiate lines further or create more detailed filtering options.
9.	Add Filters to the View
 
    i.	Right-click on the `Platform` field in the Filters shelf and select "Show Filter".
  
    ii.	Right-click on the `Genre` field in the Filters shelf and select "Show Filter".
  
    iii.	The filters will now appear on the right side of the worksheet, allowing you to interactively filter the data by platform and genre.

11.	Customize the Graph
  
      i.	**Labels**: Click on the Label button on the Marks card to add labels to the lines. You can choose to label specific data points or the entire line.
  
      ii.	**Tooltips**: Click on Tooltip to customize the information displayed when you hover over a data point.
  
      iii.	**Axes**: Double-click on the axes to customize the labels, ranges, and formatting.
  
      iv.	**Title**: Double-click on the title to rename it (e.g., "Global Video Game Sales by Platform and Genre").

12.	Format the Graph
  
      i.	Right-click on the background of the graph to format the borders, grid lines, and shading.
    
      ii.	Adjust the color palette to ensure the lines are distinct and visually appealing.

### Explanation of the Line Graph

This line graph displays the global sales of video games over time, from 1992 to 2019. Here are some key points and features of the graph:

1. **Axes**:
   - **X-Axis (Year)**: Represents the timeline from 1992 to 2019.
   - **Y -Axis (Global Sales)**: Represents the global sales of video games in millions of units.

2. **Lines**:
   - Each line represents a different video game platform (e.g., PS PS2, PS3, PS4).
   - The sales data is plotted over the years, showing trends and changes in sales for each platform.

3. **Data Points**:
   - Significant data points are highlighted with sales figures.
   - For instance, in 2010, the PS3 platform had a peak in sales of 58.74 million units.

4. **Legend**:
   - On the right side, the legend lists the platforms and genres of video games.
   - Platforms include various gaming consoles like PS2, PS3, PS4, Wii, X360, etc.
   - Genres include Action, Adventure, Fighting, Misc, Platform, Puzzle, Racing, Role-Playing, Shooter, Simulation, Sports, Strategy.

### Explanation of the Filters

1. **Platform Filter**:
   - Located on the right side of the graph, this filter allows the user to select and deselect different gaming platforms.
   - For example, the graph currently displays data for PS2, PS3, and PS4 platforms.
   - Users can check or uncheck the boxes to view sales data for specific platforms only.

2. **Genre Filter**:
   - Also located on the right side, below the platform filter.
   - This filter allows the user to select and deselect different video game genres.
   - The genres are color-coded in the graph for easy identification.

### Interpretation

- **Trends**:
  - The graph shows peaks and declines in sales over the years.
  - Certain platforms like PS2 and PS3 have noticeable peaks during their respective periods, indicating their popularity and high sales during those years.
  
- **Sales Patterns**:
  - The fluctuating lines suggest varying sales performances for different platforms over time.
  - The rise and fall in sales can be correlated with the release of new consoles, games, and market trends.

- **Market Insights**:
  - By analyzing this graph, one can identify which platforms were most successful during specific time periods.
  - It also provides insight into how different game genres perform over time across various platforms.

This graph is a useful tool for understanding the historical sales performance of video game platforms and genres, aiding in market analysis and strategic planning.
#### 5. Create a New Worksheet
1. Click on the "Sheet 2" tab at the bottom to create a new worksheet and name it `Bar Graph`.

#### 6. Create Bar Graph
1.	Drag the `Genre` field to the Columns shelf.
2.	Drag the Global Sales field to the Rows shelf.
3.	Drag the `Genre` field to the Color shelf under Marks to differentiate the bars by platform.
4.	Click on the dropdown in the Marks card and select "Bar" to change the mark type to bar.
5.	Optionally, you can drag the `Platform` field to the Color shelf under Marks to differentiate the bars by genre instead of `Genre`.
6.	Customize the Graph

  i.	**Labels**: Click on the Label button on the Marks card to add labels to the bars. You can choose to label specific data points or the entire bar.

  ii.	**Tooltips**: Click on Tooltip to customize the information displayed when you hover over a bar.

  iii.	**Axes**: Double-click on the axes to customize the labels, ranges, and formatting.
  
  iv.	**Title**: Double-click on the title to rename it (e.g., "Global Video Game Sales by Genre").

7. Format the Graph

  i.	Right-click on the background of the graph to format the borders, grid lines, and shading.
  
  ii.	Adjust the color palette to ensure the bars are distinct and visually appealing.

### Explanation of the Bar Graph

This Bar graph displays the global sales of video games over Genre. Here are some key points and features of the graph:

1. **Axes**:
   - **X-Axis (Year)**: Represents the Genre, having some features.
   - **Y -Axis (Sum(Global Sales))**: Represents the global sales of video games in millions of units.

2. **Lines**:
   - Each bar present the each Genre.
   - The sales data is plotted over the Genre, showing  bars and changes in Sum of sales for each Genre.

3. **Data Points**:
   - Significant data points are highlighted with sales figures.
   - For instance, in Action Genre, having peak in sum of sales of 1751 million units.

### Explanation of the Filters

 **Genre Filter**:
   - Also located on the right side, below the platform filter.
   - This filter allows the user to select and deselect different video game genres.
   - The genres are color-coded in the graph for easy identification.

### Interpretation

- **Bars**:
  - The graph shows peaks and declines in sales over the Genre.
  - Certain Genre like Action have noticeable peaks during their respective periods, indicating their popularity and high sales during this Genre.

- **Market Insights**:
  - By analyzing this graph, one can identify which Genre were most successful during specific time periods.

This graph is a useful tool for understanding the sales performance of video game genres, aiding in market analysis and strategic planning.

#### 7. Create a New Dashboard
1. Click on the "Dashboard 1" tab at the bottom to create a new worksheet and name it `Dashboard`.


#### 8. Create Dash Board
1.	Drag the Sheet `Line Graph` and `Bar Graph` and then set both sheets
2.	Here I take `Line Graph` Sheet upper side and `Bar Graph` Sheet down side.
3.	Give dashboard the title `Video Game Sales Dashboard`

#### 9. Create a New Worksheet
1. Click on the "Sheet 3" tab at the bottom to create a new worksheet and name it `Graph with bins`.

#### 10. Create Bar Graph with bins and calculation
1.	Right Click on Global Sales > Go to Create > Go to Calculated Field
2.	Name it `Global Sales – EU Sales` and write in section `[Global Sales] – [EU Sales]` then Apply.
3.	Right Click on Year > Go to Create > Go to Bins
4.	Name it `Year (bin)` and set size of bin `5`
5.	Drag the `Year (bin)` field to the Columns shelf.
6.	Drag the `Global Sales` field to the Rows shelf.
7.	Drag the `Global Sales – EU Sales` field to the Rows shelf.
8.	Drag the `Genre` field to the Color shelf under Marks to differentiate the bars by platform.
9.	Drag the `Genre` field to the Color shelf under Marks to differentiate the bars by platform and Year (bin).
10.	Drag the `Global Sales` field to the Label shelf under Marks to differentiate the bars by platform and Year (bin).
11.	Click on the dropdown in the Marks card and select "Bar" to change the mark type to bar.
12.	Optionally, you can drag the `Platform` field to the Color shelf under Marks to differentiate the bars by genre instead of `Genre`.
13.	Drag `Platform` and `Year (bin)` in filters and just select `PS, PS2, PS3, PS4` from Platform and exclude `Null` from Year (bin).
14.	Customize the Graph

  i.	Labels: Click on the Label button on the Marks card to add labels to the bars. You can choose to label specific data points or the entire bar.

  ii.	Tooltips: Click on Tooltip to customize the information displayed when you hover over a bar.

  iii.	Axes: Double-click on the axes to customize the labels, ranges, and formatting.

  iv.	Title: Double-click on the title to rename it (e.g., "Global and EU Video Game Sales by Genre and Platform").
15. Format the Graph

  i.	Right-click on the background of the graph to format the borders, grid lines, and shading.

  ii.	Adjust the color palette to ensure the bars are distinct and visually appealing.

#### Explanation of the Bar graph with bins

This graph is a stacked bar chart displaying global sales of video games, segmented by genre and binned by year. There are two stacked bar charts presented vertically, each representing a different measure of sales:

1. **Top Bar Chart: Global Sales**
2. **Bottom Bar Chart: Global Sales minus EU Sales**

### Key Elements of the Graph:

1. **X-Axis (Year bin)**: 
   - The years are grouped into bins, though the specific binning interval (e.g., 5-year bins) is not explicitly labeled.
   - Each bin represents a range of years.

2. **Y-Axis (Top Chart: Global Sales)**:
   - Represents the total global sales of video games for each year bin.
   - The scale starts from 0 and increases in increments (e.g., 200, 400, 600, 800).

3. **Y-Axis (Bottom Chart: Global Sales - EU Sales)**:
   - Represents global sales minus EU sales for each year bin.
   - This scale is similar to the top chart but shows the difference after subtracting EU sales.

4. **Color Legend (Right Side)**:
   - Indicates the genre of video games, with each color representing a different genre (e.g., Action, Adventure, Fighting, etc.).

5. **Stacked Bars**:
   - Each bar is a stack of different colors, representing the contribution of each genre to the total sales.
   - The height of each color segment within a bar represents the sales volume for that genre in that year bin.

### Interpretation:

- **Global Sales (Top Chart)**:
  - The total height of each bar represents the total global sales for that bin.
  - The color segments within each bar show how different genres contribute to the total sales.
  - Over time, you can see the changes in sales volume and how the popularity of different genres has varied.

- **Global Sales minus EU Sales (Bottom Chart)**:
  - This chart gives an idea of how significant EU sales are compared to the rest of the world.
  - The difference between the top and bottom charts for the same year bin indicates the proportion of sales that comes from the EU.
  - If the bars in the bottom chart are significantly shorter, it implies a large portion of sales comes from the EU.

### Insights:

- The most prominent genres (e.g., Action, Sports) can be identified by their consistent presence and significant height in the stacked bars.
- Trends over time (e.g., increasing or decreasing popularity of certain genres) can be observed.
- The contribution of the EU market to global sales can be inferred by comparing the top and bottom charts.

#### 9. Create a New Worksheet
1. Click on the "Sheet 4" tab at the bottom to create a new worksheet and name it `Tree Map Chart`.

#### 10. Create Tree Map Chart
1.	Drag the `Global Sales` field to the Size shelf under Marks and set to automatic.
2.	Drag the `Na Sales` field to the Color shelf under Marks.
3.	Drag the `Genre` field to the Label shelf under Marks to show labels.
4.	Drag the `Global Sales` field to the Label shelf under Marks to show labels.
5.	Customize the Graph

  i.	Labels: Click on the Label button on the Marks card to add labels to the bars. You can choose to label specific data points or the entire bar.

  ii.	Tooltips: Click on Tooltip to customize the information displayed when you hover over a bar.

  iii.	Title: Double-click on the title to rename it (e.g., "Tree Map Chart").

#### Explanation of the Tree Map Chart

This graph is a tree map chart that displays the total sales of video games by genre. Each rectangle represents a different genre, and the size of each rectangle is proportional to the total sales for that genre.

### Key Elements of the Graph:

1. **Rectangles**:
   - Each rectangle represents a specific genre of video games.
   - The size of the rectangle is proportional to the total sales for that genre. Larger rectangles indicate higher sales.
   - The color intensity within each rectangle varies, representing the sales range within the genre.

2. **Labels**:
   - Each rectangle is labeled with the genre name and its corresponding total sales value.
   - For example, "Action 1,751" means that the Action genre has total sales of 1,751 units (or millions, depending on the unit of measure).

3. **Tooltip**:
   - When hovering over a rectangle, additional details are displayed in a tooltip. In this case, the tooltip shows:
     - Genre: The name of the genre.
     - Global Sales: The total global sales for the genre.
     - NA Sales: The total sales for the genre in North America.
   - For example, hovering over the Simulation genre shows: "Genre: Simulation, Global Sales: 392, NA Sales: 183.3".

4. **Color Legend (Right Side)**:
   - The color legend shows the range of sales values, with lighter colors representing lower sales and darker colors representing higher sales.
   - The sales range on the color legend goes from 68.7 to 877.8, indicating the minimum and maximum sales values in the dataset.

### Insights:

1. **Top Genres by Sales**:
   - The largest rectangles indicate the genres with the highest total sales. In this chart, the top genres are:
     - Action: 1,751
     - Sports: 1,331
     - Shooter: 1,037

2. **Moderate Sales Genres**:
   - Genres with moderate sales include:
     - Role-Playing: 927
     - Misc: 810
     - Platform: 831

3. **Lower Sales Genres**:
   - Genres with lower sales are represented by smaller rectangles, such as:
     - Fighting: 449
     - Puzzle: 245
     - Adventure: 239

4. **Comparative Analysis**:
   - The treemap allows for quick visual comparison of the sales performance of different genres.
   - It is easy to see which genres dominate the market and which ones have relatively lower sales.

### Summary:

- The Action genre has the highest total sales, followed by Sports and Shooter.
- The tree map visually emphasizes the proportionate sales of each genre, making it easy to identify the most and least popular genres in terms of sales.
- The color intensity provides an additional layer of insight, indicating the range of sales within each genre.

#### 11. Create a New Worksheet
1. Click on the "Sheet 5" tab at the bottom to create a new worksheet and name it `Bubble Chart`.

#### 12. Create Bubble Chart
1.	Drag the `Global Sales` field to the Size shelf under Marks and set to Circle.
2.	Drag the `Genre` field to the Label shelf under Marks to show labels.
3.	Drag the `Na Sales` field to the Color shelf under Marks.
4.	Drag the `Global Sales` field to the Label shelf under Marks to show labels.
5.	Customize the Graph

  i.	Labels: Click on the Label button on the Marks card to add labels to the bars. You can choose to label specific data points or the entire bar.

  ii.	Tooltips: Click on Tooltip to customize the information displayed when you hover over a bar.

  iii.	Title: Double-click on the title to rename it (e.g., "Bubble Chart").

#### Explanation of the Bubble Chart

This graph is a bubble chart representing the sales of video games by genre. Each circle represents a different genre, and the size of each circle is proportional to the total sales for that genre.

### Key Elements of the Graph:

1. **Circles**:
   - Each circle represents a specific genre of video games.
   - The size of the circle is proportional to the total sales for that genre. Larger circles indicate higher sales.

2. **Labels**:
   - Each circle is labeled with the genre name and its corresponding total sales value.
   - For example, "Action 1,751" means that the Action genre has total sales of 1,751 units (or millions, depending on the unit of measure).

3. **Color Legend (Right Side)**:
   - The color legend shows the range of sales values, with lighter colors representing lower sales and darker colors representing higher sales.
   - The sales range on the color legend goes from 68.7 to 877.8, indicating the minimum and maximum sales values in the dataset.

### Insights:

1. **Top Genres by Sales**:
   - The largest circles indicate the genres with the highest total sales. In this chart, the top genres are:
     - Action: 1,751
     - Sports: 1,331
     - Shooter: 1,037

2. **Moderate Sales Genres**:
   - Genres with moderate sales include:
     - Role-Playing: 927
     - Platform: 831
     - Misc: 810

3. **Lower Sales Genres**:
   - Genres with lower sales are represented by smaller circles, such as:
     - Fighting: 449
     - Puzzle: 245
     - Adventure: 239
     - Strategy: 175

### Comparative Analysis:

- The bubble chart allows for quick visual comparison of the sales performance of different genres.
- It is easy to see which genres dominate the market and which ones have relatively lower sales.
- The color intensity provides an additional layer of insight, indicating the range of sales within each genre.

### Summary:

- The Action genre has the highest total sales, followed by Sports and Shooter.
- The bubble chart visually emphasizes the proportionate sales of each genre, making it easy to identify the most and least popular genres in terms of sales.

#### 9. Save and Share
1. Save your Tableau workbook by clicking "File" > "Save As".
2. If you need to share the workbook, you can publish it to Tableau Server or Tableau Public.


------

You can make more graphs by folowing this procedure. and make more attractive Dashboards. like this
![Screenshot 2024-06-28 190153](https://github.com/UMMY87/Video-Game-Sales-DashBoard-in-Tableau/assets/117314436/26e15d1b-37de-4a04-8220-6aad1fddb341)
