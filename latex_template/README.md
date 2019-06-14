# MolSSI Poster Latex Template

This template was contributed by Dominique Nocito.

# FONTS
To use the proper DIN fonts lualatex must be used
The style file is set up to look down one directory for the fonts directory,
so if you are changing the directory structure the style files path will need
to be updated

# Boarder
lualatex must be run twice for it to generate the poster boarder correctly.

# University Logo
The template requires a university logo. The user will need to set up the location for their logo in `beamerthemeMolSSI.sty`. The relevant line is currently line `31` (where "university_logo" is specified.)

`\graphicspath{{../figs/}{../logos/}{../logos/main_logo/}{../logos/university_logo/}}`

The name of the file will also need to be changed in `software_fellow_poster.tex` on line 18.
