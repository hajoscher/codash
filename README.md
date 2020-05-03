# codash

A simple Covid19 dashboard with dc.js.
- Shows active cases and new confirmed/deaths/recovered
- Compare countries by clicking on the map or the rowchart

## Data source

[https://github.com/CSSEGISandData/COVID-19.git](https://github.com/CSSEGISandData/COVID-19.git)

## Comments

- It felt like [dc.js](https://github.com/dc-js) is the ideal framework for this kind of thing, however so far this is not exploiting its full power, e.g. no selection by date.

- I had to disable having no filter at all, since showing more than 180 plots is too much.

- The `remove_empty_bins` function should be improved, there must be an easier way to remove by country instead of country/date.

- Synchronizing the rowchart and the worldmap has been quite tricky, and probably is a bit buggy, but it seems to work.

 - Something is wrong with the data for Canada.
 - Some country names still have to be mapped between the worldmap and the rowchart.

Pull requests welcome.
