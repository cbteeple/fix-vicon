# fix-vicon
Some helpful scripts for fixing vicon data

## Capabillities
1. Stitch together vicon marker streams when they blink (collapse columns)
2. Remove frames where data moves too fast (within some tolerance)
3. Remove frames where there are an icorrect number of markers

## Usage
1. Set the save path for the data you want to process
2. Set up your settings in the Jupyter notebook
3. Run through the notebook
4. Your resulting data is plotted so you can view whether you got something you expected.
5. You can choose to save the resulting data by pickeling it or saving a CSV.
