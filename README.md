# Senzing Demo

## <a id=preconditions></a> 1. Preconditions for Using this demo

If you have not done so already, you must do these steps before proceeding with the Senzing demo:

1. Download and install the Senzing app.
2. 1. Clone this git repository:

```bash
cd ~   # or wherever you want
git clone git@github.com:jiportilla/senzing-demo.git
cd ~/senzing-demo/
```
## <a id=preconditions></a> 2. Loading and Exploring Las Vegas PPP Data

1. Download and install the free Senzing App [here](http://www.senzing.com/). (No private data flows to Senzing)

2. Launch the Senzing App.

3. Create a Project

- Select “Projects” (left toolbar, icon with the hammer).
- Select “Add Project.”
- Name the project whatever you like e.g., “PPP Las Vegas.”
- Select “Create.”

4. Load the PPP file into Senzing.
- Download the “PPP_Loans_Over_$150k_LasVegas.csv” that we have prepared [here](http://bit.ly/2Yg2G1d).
- Select “Data” (left toolbar, icon with the cylinder).
- Drag and drop the “PPP_Loans_Over_$150k_LasVegas.csv” file onto the canvas.
- Click the “Load” icon.

5. Review the results.

- Once loading is complete, Click “Review.”
- Explore the Duplicates — records Senzing thinks belong to the same organization.
- On the far right click the little “expand” icon (looks like a small blue clock) that appears as you hover over the “Other Data” column.
- Once finished exploring “Duplicates,” click on “Possibly Related.” The match key column explains why they are related.
- Click on any “Entity ID” (left column in chart) to see the entity’s resume.

## Highlights:

- Notice in the top blue bubble there are 40 duplicates.
- Looking over these duplicates you will notice some are probably false positives e.g., these three entities “NG WASHINGTON“, “NG WASHINGTON II“ and “NG WASHINGTON III“ are probably different legal entities — each eligible for a PPP loan.
- You may notice other duplicates that look like identical legal entities — these being examples where further human analysis is required.
- Select “Search” (left toolbar, icon with a magnifying glass) and search for this address: “3130 S Durango Dr STE 400 Las Vegas.” Click any of the possibly related entities you will see something like this:
