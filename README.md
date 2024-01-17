# Michigan_housing

## How to run the visualization code

### Step 1. Download the code

### Step 2. Install needed packages.

You can run the following line in your (local) terminal:

```
pip install shiny
pip install shinywidgets
pip install ipyleaflet
pip install uvicorn
```

### Step 3. Set up shiny app server

Change line 9 of app.py

Launch your terminal in the folder that contains app.py, then run the following code in your terminal

```
uvicorn app:app --host 0.0.0.0 --port 54321
```

You can change the port number to the one you like

### Step 4: Check the visualization in your browser

In your browser url tab, type http://localhost:54321/

The visualization should appear.

## How to update data file

### To update LARA file

Please update the Longitude and Latitude column for every new entry. These coordinates can be found via Google search. Only entries with coordinates will be visualized.