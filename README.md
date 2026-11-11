# Behind the Screens

An interactive website showing how Asian American subgroups compare in education, employment and pay, with a focus on tech-related fields. Asian Americans are usually reported as one group. This site splits that number apart so visitors can see the differences and draw their own conclusions.

Created by Lawrence Novilla and Nimai Kasibatla for CSE 194 (Race, Gender and Computing) at UC San Diego, Fall 2026.

## Files

- `index.html` is the whole website (HTML, CSS and JavaScript in one file)
- `Behind_the_Screens_Data.xlsx` is the shared spreadsheet with every number on the site and its source

## Updating the data

When new yearly data comes out

1. Update the numbers in `Behind_the_Screens_Data.xlsx` (blue numbers come from sources, black numbers are formulas)
2. Open `index.html` and find the `DATA` section near the top of the `<script>` tag
3. Change the matching values in `METRICS` (each group has a `v` value)
4. Add any new sources to the Sources tab of the spreadsheet and the Sources section of the site
5. Commit and push, and GitHub Pages will update the live site within a few minutes

## Main sources

Pew Research Center fact sheets on Asian origin groups (2025), AAPI Data (2025), the Bureau of Labor Statistics, and Vinluan and Kraus (2026). The full list is in the spreadsheet and on the site.

## Contributing

Corrections and new data are welcome. Please include a link to the source for any number you add.
