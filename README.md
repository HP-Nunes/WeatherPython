https://hp-nunes.github.io/WeatherPython/

# UC Berkeley Extension : Unit 12 | Assignment - Web Visualization Dashboard (Lattitude)
## WeatherPy.github.io
HTML page for the WeatherPy assignment's outputs, learning bootstrap and css.

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

## Lattitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. 

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A [landing page](https://hp-nunes.github.io/WeatherPython/) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](https://hp-nunes.github.io/WeatherPython/WeatherPy_Temperature.html), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](https://hp-nunes.github.io/WeatherPython/WeatherPy_Comparison.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](https://hp-nunes.github.io/WeatherPython/WeatherPy_DataTable.html) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. You may use a csv-to-html table conversion tool, e.g. [ConvertCSV](http://www.convertcsv.com/csv-to-html.htm).

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to github pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the github repository.

### Prerequisites

Python/Anaconda version
* Python 3.6.1 (64-bit)
* conda 4.3.29

Libraries used
* matplotlib
* requests
* json
* pandas
* pprint
* seaborn
* plotly
* numpy
* sklearn
* citipy
* random

API used
* openweathermapy.core
