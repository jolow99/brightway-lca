# Installation Instructions
1. Clone the respoitory, create a new conda environment and install the required dependencies using the following command
`conda create -n ab -c conda-forge -c cmutel -c bsteubing activity-browser python=3.9 jupyterlab bw2io=0.8.7`

2. Activate the virtual environment you have just created.
`conda activate ab`

3. Open the Activity Browser. An interface should pop up. 
`activity-browser`

4. In the activity browser, follow the prompts on-screen to install default Biopshere database. After it is done, click File > Update Biosphere. There should be 4433 records in the Biosphere3 database.

5. In the activity browser, import `EcoInvent 3.7 (General)/ecoinvent 3.7.1_consequential_ecoSpold02.7z`

6. You have now setup everything we need to begin our LCA! 

# Usage Instructions 
1. Get a Jupyter notebook up and running by using the command `jupyter lab`. (Remember to activate your virtual environment!)
2. Run things in the main notebook. You can use the activity browser to more easily find relevant data. 

# brightway-lca
