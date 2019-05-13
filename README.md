# mi2csv
Output select mediainfo fields to CSV for import into spreadsheet or database

Requires mediainfo to be installed. sudo apt install mediainfo or whatever similar on your system.

Usage:

mi2csv "/path/to/media" "mycsvfile.csv"

Will scan provided media path for all video files and create the given CSV file with following layout, suitable for importing into your favorite spreadsheet application.

Sample output:

  filename, ext, size, duration, width, height, fps, aspect
  
  "/plex/movies/Catwoman/Catwoman.avi", avi, 1466207024, 01:39:57.680, 720, 304, 25, 2.35:1

Modifications to these fields should be fairly simple.
