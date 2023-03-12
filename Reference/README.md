# Tutorials and Resources for Coding via GitHub and Python
* [GitHub tutorial: Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
   * headings, bold/italic/underline, quoting, colors (brief), web links, relative links, images, lists, task lists, mentions (@), emoji 🍭 [(cheat sheet)](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md), footnotes.
* [GitHub tutorial: Advanced formatting](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting) (tables, syntax highlighting, diagrams, math equations, etc.)
* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) Headers, Emphasis, Lists, Links, Images, Code and Syntax Highlighting, Footnotes, Tables, Blockquotes, Inline HTML, Horizontal Rule, Line Breaks, YouTube Videos
* [GitHub tutorial: Attaching files](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/attaching-files)
* [Tutorial: How to create a folder in GitHub repos](https://www.alpharithms.com/how-to-create-a-folder-in-github-repos-463022/)
* Really basic shit
   * [Yoh resource: Selecting good variable names](https://github.com/yohman/23W-UP221/blob/main/Weeks/Week01%20Intro/extras/gcp-1-variable-naming.ipynb)
   * [Yoh resource: Describing your code](https://github.com/yohman/23W-UP221/blob/main/Weeks/Week01%20Intro/extras/gcp-2-describing-code.ipynb)
   * [Yoh resource: Commit and push](https://github.com/yohman/23W-UP221/blob/main/Git%20related/Commit%20and%20push.md)
* Week 1   
   * [Navigating JupyterLab - from week 1 class](https://github.com/yohman/23W-UP221/blob/main/Weeks/Week01%20Intro/W102-NavigatingTheNotebook.ipynb)
   * [Reference sheet: GIS and coding troubleshooting](https://docs.google.com/document/d/14fz3iSSb76PDiyqY8ZGDpao3umKMgvvR5NtvQwOsJao/edit)
   * [Yoh resource: Clone repo to hub](https://github.com/yohman/23W-UP221/blob/main/Git%20related/Clone%20repo%20to%20hub.md)
   * [Yoh resource: Uploading and updating your repo](https://github.com/yohman/23W-UP221/blob/main/Git%20related/Clone%20repo%20to%20hub.md)
   * [Python Multiply List by Scalar](https://linuxhint.com/multiply-list-scalar-python/)
* Useful keyboard shortcuts

key | action
--- | ---
shift-enter | execute a cell and go to the next cell
alt-enter | execute a cell and stay on the same cell
A | add a cell above
B | add a cell below
DD | delete a cell
ctrl+shift+dash | split a cell at the cursor
x | cut a cell
c | copy a cell
v | paste a cell
shift+l | show line numbers in a code cell

* Week 2
    * [Reading and writing files in Geopandas](https://geopandas.org/en/latest/docs/user_guide/io.htmlhttps://geopandas.org/en/latest/docs/user_guide/io.html)
    * [Creating plots in Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/04_plotting.html#min-tut-04-plotting)
    * [About Pandas .loc](https://www.w3resource.com/pandas/dataframe/dataframe-loc.php)
    * [About Folium](https://python-visualization.github.io/folium/quickstart.html)
* Week 3
    * https://www.socialexplorer.com Census and other data
       * [How to download data from Social Explorer](https://github.com/yohman/up206a/blob/master/guides/social_explorer.md)
    * [Rename columns](https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas)
    * [Histograms](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.hist.html)
    * [Box Plot](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.boxplot.html)
    * [Scatter Plot](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.scatter.html)
    * CSV lat/long to GPD: new_gdf= gpd.GeoDataFrame(df, geometry=gpd.points_from_xy(df.Longitude, df.Latitude))
        * [online tutorial](https://stackoverflow.com/questions/61122875/geopandas-how-to-read-a-csv-and-convert-to-a-geopandas-dataframe-with-polygons)
* Week 4
    * [matplotlib markers](https://matplotlib.org/stable/api/markers_api.html)
    * [Exporting from matplotlib to open in Adobe Illustrator](https://jonathansoma.com/lede/data-studio/matplotlib/exporting-from-matplotlib-to-open-in-adobe-illustrator/)
    * [LA Times neighborhood boundaries](https://geohub.lacity.org/datasets/lahub::la-times-neighborhood-boundaries/about)
    * [Scatter plots on mapbox in Python](https://plotly.com/python/scattermapbox/)
    * [Bar charts in Python](https://plotly.com/python/bar-charts/)
    * [Sodapy API (I think)](https://github.com/xmunoz/sodapy)
    * [Socrata API](https://dev.socrata.com/docs/endpoints.html)
* Week 5!
    * Open Street Maps
       * [OSMNX examples](https://github.com/gboeing/osmnx-examples)
       * [OSMNX GitHub home](https://github.com/gboeing/osmnx)
       * [About OSMNX](https://osmnx.readthedocs.io/en/stable/)
    * [Plotly templates](https://plotly.com/python/bar-charts/)
    * [Library of geopandas commands](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoSeries.total_bounds.html)
    * [How to put legend outside the plot in GPD](https://stackoverflow.com/questions/4700614/how-to-put-the-legend-outside-the-plot/43439132#43439132)
    * [Colormap reference Matplotlib](https://matplotlib.org/3.1.1/gallery/color/colormap_reference.html)
    * [Mapbox Choropleth Maps in Plotly](https://plotly.com/python/mapbox-county-choropleth/)
    * [Fetching green areas from OSM](https://towardsdatascience.com/fetching-green-areas-from-osm-data-a6ff835c40dc)
    * [Tags in OSM](https://wiki.openstreetmap.org/wiki/Tags)
* Week 6
    * [Folium layer control tutorial](https://snyk.io/advisor/python/folium/functions/folium.LayerControl)
* Week 7
    * [Zipping and Unzipping Iterables in Python](https://towardsdatascience.com/zip-function-in-python-da91c248385d)
    * [Aggregation with dissolve](https://geopandas.org/en/stable/docs/user_guide/aggregation_with_dissolve.html)
* Week 8
    * [Leaflet providers preview...Open Street Map](https://leaflet-extras.github.io/leaflet-providers/preview/)
    * [Geopandas mapping and plotting tools](https://geopandas.org/en/stable/docs/user_guide/mapping.html)
    * [Creating a GeoDataFrame from a DataFrame with coordinates](https://geopandas.org/en/stable/gallery/create_geopandas_from_pandas.html)
    * [LAPD Arrest Data since 2020 on Socrata](https://dev.socrata.com/foundry/data.lacity.org/amvf-fr72)
    * [LA Open Data Portal Arrest Data since 2020](https://data.lacity.org/Public-Safety/Arrest-Data-from-2020-to-Present/amvf-fr72)
    * [Census Reporter](https://censusreporter.org/data/table/?table=B01003&geo_ids=16000US0644000,150%7C16000US0644000&primary_geo_id=16000US0644000)
    * [SPLOT library info](https://github.com/pysal/splot)
    * [ESDA library info](https://pysal.org/esda/)
    * [Creating a GeoDataFrame from a DataFrame with coordinates](https://geopandas.org/en/stable/gallery/create_geopandas_from_pandas.html)
    * [Merging Data](https://geopandas.org/en/stable/docs/user_guide/mergingdata.html)
    * [geopandas.GeoDataFrame.explore](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoDataFrame.explore.html)
    * [Leaflet Provider Demo](https://leaflet-extras.github.io/leaflet-providers/preview/)
    * [Creating multiple subplots using plt.subplots](https://matplotlib.org/3.3.0/gallery/subplots_axes_and_figures/subplots_demo.html)
* Week 9
    * [Yoh's tutorial: from Jupyter to Story Maps](https://storymaps.arcgis.com/stories/df1a75fac03b4815a2dccc1ebe622441)
    * [Quick Start for GitHub Pages](https://docs.github.com/en/pages/quickstart)
    * [ESRI Story Maps](https://www.esri.com/arcgis-blog/products/story-maps/constituent-engagement/optimize-group-settings-to-share-stories-like-never-before/)
