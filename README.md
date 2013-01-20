LIVES Restaurant Inspection Score Feed Generator

The "gen-lives-feed" script processes restaurant
inspection scores published by the City of Austin,
and generates an archive that conforms to the
LIVES data standard.

For more information on LIVES, see:

http://www.yelp.com/healthscores

When run with no command line arguments, data is retrieved from:

	https://data.austintexas.gov/api/views/ecmv-9xxi/rows.json

and saved in LIVES format to:

	lives.ci.austin.tx.us.zip

The "gen-lives-feed" script is written in Ruby. It has been tested with
Ruby 1.9.3 and uses only standard library modules.

The script requires an external program named "zip" to produce
the resulting archive.

Copyright 2013, Chip Rosenthal <chip@unicom.com>

This package is released as open source, under the license
published here: http://www.unicom.com/sw/license

