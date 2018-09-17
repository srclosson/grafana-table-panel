# Table Panel -  Native Plugin

The Table Panel is **included** with Grafana.

*Update*
I have modified this panel to allow the headers to scroll along with the content of the body. When headers requires scrolling previously, they were locked in place.
I have also locked the first column (hard coded currently) as for my use case, the first column is the time index, and will always be the time index and the data associated with that time index can be scrolled with the time column locked. This could be configurable in the future.

The table panel is very flexible, supporting both multiple modes for time series as well as for table, annotation and raw JSON data. It also provides date formatting and value formatting and coloring options.

Check out the [Table Panel Showcase in the Grafana Playground](http://play.grafana.org/dashboard/db/table-panel-showcase) or read more about it here:

[http://docs.grafana.org/reference/table_panel/](http://docs.grafana.org/reference/table_panel/)
