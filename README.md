# Identifying Student loans

Our project is centered around the rate at which college students default on federal loans. This repository will hold all relevant information required to perform our analysis.

### notebooks

The notebooks directory contains all IPython notebooks used to process, clean, visualize, and model our datasets.

### data.zip

One of our datasets, `delta_public_00_12.csv` is around 255 MB, which is well above GitHub's supported 100 MB. We zip the entire `data` directory in order to squeeze everything down to 68 MB. This zipfile **must stay as a zip file**. 

### Do not commit the raw data to your branch/repository or else you're gonna have a bad time.

Instead, run:

	unzip data.zip
	
This will sometimes create a directory called `__MACOSX` — feel free to delete it with

	rm -rf __MACOSX
	
When you're done working on the data and made a significant change to the CSV files, re-zip the directory

	zip data
	
then add it, commit it, push it, etc. Thanks!