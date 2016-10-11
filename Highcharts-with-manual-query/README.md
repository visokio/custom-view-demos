Embeds [Highcharts](http://www.highcharts.com/), configurable as a Bar, Line, Pie, Graph or Pyramid chart.

Instead of using auto query (where the data has already been queried before the view renders), this view performs a manual query.
It creates its own query of split (grouping) and measure, sorts by highest measure, then drops anything but the first (top) 20 elements, 
as an example of one way of dealing with potentially millions of elements.

Clicking elements has been implemented to select them in Omniscope, such that if other views are present, they will 'brush' to show the impact
of that selection.

Corresponds to the current public demo "Bond prices with Highcharts, manual query, limit to 20 bars, selection enabled".
