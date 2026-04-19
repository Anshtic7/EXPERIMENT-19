**NAME: ANSH PRATAP SINGH**

**PRN: 25070123143**

**AIM: To study and implement various real-world and interactive data visualization techniques using Python libraries such as Matplotlib, Plotly, and SciPy, including treemap, dendrogram, Venn diagram, Sankey diagram, 3D scatter plot, and radar chart for effective data analysis and representation.**

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**THEORY**

Data visualization is the graphical representation of data and information using visual elements such as charts, graphs, and plots. It helps in understanding complex data, identifying patterns, trends, and relationships, and making data-driven decisions effectively. In modern data analysis, visualization plays a crucial role in interpreting large datasets in a simplified manner.

Python provides several powerful libraries for data visualization, among which Matplotlib, Plotly, and SciPy are widely used.

1. Matplotlib

Matplotlib is a fundamental plotting library in Python used to create static, animated, and interactive visualizations. It provides full control over graphs and supports various types of plots such as line plots, bar charts, scatter plots, histograms, and 3D plots.

i. It is highly customizable.

ii. It is suitable for basic to advanced visualizations.

iii. It integrates well with NumPy and Pandas.

2. Plotly

Plotly is an advanced visualization library used for creating interactive and web-based graphs. It allows users to zoom, hover, and interact with data.

i. Supports complex visualizations like Sankey diagrams and radar charts.

ii. Provides better user interaction compared to Matplotlib.

iii. Widely used in dashboards and web applications.

3. SciPy

SciPy is mainly used for scientific and technical computing. In visualization, it helps in creating structures like dendrograms using hierarchical clustering.

i. Used for advanced mathematical computations.

ii. Helps in analyzing relationships between datasets.

**--->** Types of Visualizations Used in the Experiment:

1. Treemap

A treemap displays hierarchical data using nested rectangles. Each rectangle represents a category, and its size corresponds to its value.

i. Useful for showing proportions.

ii. Helps in comparing different categories visually.

2. Dendrogram

A dendrogram is a tree-like diagram used to represent hierarchical relationships between data points.

i. Commonly used in clustering analysis.

ii. Helps in identifying similarities between data groups.

3. Venn Diagram

A Venn diagram shows relationships between different sets.

i. Uses overlapping circles to represent common and unique elements.

ii. Useful in set theory and probability.

4. Sankey Diagram

A Sankey diagram represents the flow of data or resources from one point to another.

i. The width of the arrows represents the magnitude of flow.

ii. Commonly used in energy flow, finance, and process analysis.

5. 3D Scatter Plot

A 3D scatter plot is used to represent data points in three dimensions (x, y, z).

i. Useful for visualizing multi-variable data.

ii. Helps in identifying clusters and patterns in 3D space.

6. Radar Chart

A radar chart (or spider chart) is used to display multivariate data in a circular form.

i. Each axis represents a variable.

ii. Useful for comparing multiple attributes of different entities.

**-->** Advantages of Data Visualization:

i. Simplifies complex data.

ii. Helps in better decision-making.

iii. Identifies trends and patterns easily.

iv. Improves communication of information.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**FUNCTIONS USED:**

1. Matplotlib Functions

**.** plt.plot() – Used to create line plots.

**.** plt.scatter() – Used to create scatter plots.

**.** plt.bar() – Used to create bar charts.

**.** plt.figure() – Creates a new figure for plotting.

**.** plt.show() – Displays the graph.

**.** plt.title() – Sets the title of the graph.

**.** plt.xlabel() / plt.ylabel() – Labels the axes.

**.** Axes3D() – Used for creating 3D plots.

**.** ax.scatter() – Plots points in a 3D scatter plot.

2. Plotly Functions

**.** plotly.graph_objects.Figure() – Creates a figure object.

**.** go.Sankey() – Used to create Sankey diagrams.

**.** go.Scatterpolar() – Used for radar (spider) charts.

**.** fig.show() – Displays the interactive plot.

3. SciPy Functions

**.** scipy.cluster.hierarchy.linkage() – Performs hierarchical clustering.

**.** scipy.cluster.hierarchy.dendrogram() – Creates a dendrogram diagram.

4. Squarify (Treemap) Functions

**.** squarify.plot() – Used to create treemap visualizations.

5. Matplotlib Venn Diagram Functions

**.** venn2() – Creates a Venn diagram for two sets.

**.** venn3() – Creates a Venn diagram for three sets.

6. NumPy Functions (if used)

**.** numpy.array() – Creates arrays for numerical data.

**.** numpy.random.rand() – Generates random values for plotting.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CONCLUSION**

In this experiment, various data visualization techniques were successfully implemented using Python libraries such as Matplotlib, Plotly, SciPy, and Squarify. Different types of visualizations including treemap, dendrogram, Venn diagram, Sankey diagram, 3D scatter plot, and radar chart were created and analyzed.

These visualizations helped in understanding complex data in a clear and meaningful way by highlighting patterns, relationships, and distributions. The experiment demonstrated that graphical representation of data is more effective than raw data for analysis and decision-making.

Thus, it can be concluded that Python provides powerful and flexible tools for data visualization, making it an essential part of data analysis and scientific computing.
