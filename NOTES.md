# Map decluttering

For google maps decluttering, see:

    https://github.com/jawj/OverlappingMarkerSpiderfier

# Aggregate locations

Write an RSpec parser to extract location data and use the most prevalent
location as the aggregate's location.

Should this data be added to the service registry so we don't need to
ferret it out each time? Yes.

But we can provide it in a JSON data file for now, until lat/lng is added
to the service registry table(s).

# Marker colors

Match the marker colors with the icons on the aggregate status page.

* What should we do for aggregates that do not report status to GENI
  Monitoring? Gray?
