Slides for a workshop entitled: 
"Reproducible Research in Environmental Epidemiology: Concepts and Tools"

To print the reveal.js slides to PDF using the program [decktape](https://github.com/astefanutti/decktape) (you may have to install [Node.js](https://nodejs.org/en/download/) before installing `decktape`) run:
```
decktape -s 2100x1400 reveal reproducible_research_workshop.html?fragments=false reproducible_research_workshop.pdf
```
This requires oversizing the viewport to work around a [known bug](https://github.com/astefanutti/decktape/issues/151) and also tells reveal.js to show all the incremental content ("fragments") in the resulting PDF.