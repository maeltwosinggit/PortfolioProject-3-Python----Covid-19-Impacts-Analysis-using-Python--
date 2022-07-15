# PortfolioProject-3-Python----Covid-19-Impacts-Analysis-using-Python--

During this project, not only I have learned to analyze the economic impacts of Covid-19 throughout the countries accross the world,
but I have also learned on how to use additional Python libraries.

Key Learning Points - 
- I discovered that plotly.express has better and more interactive UI compared to when we use matplotlib. I am now considering to convert all my works to plotly.express
- I have applied the pandas function pd.to_csv by directly using original filepath from C: instead of having to upload my CSVs to Jupyter Notebook homepage every time.
  I only need to copy the original filepath and change "\" to "/"
- I have discovered the use of pandas.DataFrame(list(zip()) - it is to aggregate/combine multiple sets of lists easily with a single line of code!
- I have used plotly.graph_objects - do find the details on this link! https://plotly.com/python/graph-objects/ (when to use graph objects)
- From this point, however powerful px is, it still has its limitations but do note that it is under the graph_objects domain, so further customization can still
  be achieved by directly accessing graph_objects
- Incomplete data can be outsourced manually from the internet - for this project's case, we have to manually outsource the GDP per Capita for before and during Covid
- In px, this project has applied px.bar and px.pie which is a good starting point for a beginner like me
- for fun, i have also discovered how to play around with px color scales by using color_continuous_scale=px.colors.sequential.xxx https://plotly.com/python/builtin-colorscales/

All credit goes to Aman Kharwal for this fantastic project
Link: https://thecleverprogrammer.com/2022/04/19/covid-19-impacts-analysis-using-python/
