# AstroPi Data Visualization

This project tries to graph the data collected from the AstroPi competition.

Here's an example:

![Graph example image](graph_example.png)

To mark a point, just left-click it.
To delete a single marker, just right-click it.
To delete all marker, hit backspace or delete.

It is a web page.

It uses [p5.js](https://p5js.org) to create the graph & load the data.

To use your own data, add your csv, with column headers (the first row has the column names, like in the csv file already in the repo) and look at index.js from `Custom START` to `Custom END` to see mpre instructions on how to use your data.



To view it, use any kind of http server, not open directly index.html.

For example, I'm using python3's `http.server` module (the command to use it is `python3 -m http.server `)
