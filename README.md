# LGCM_power

To run the code, please do take the following steps:
1. Download the Zipfile to your computer (or fork the repository if that is preferred)
2. Unpack the Zipfile and open the project file in RStudio (LGCM_power.Rproj)
3. From the RStudio interface go to the files tab
4. From the files pane in RStudio, open the file: LGCM_poweranalysis.qmd
5. Run the first codeblock to load the dependencies (needed packages) using renv.
  renv will now be downloaded and all packages in the versions that are in the lockfile will be listed.
6. You will be asked if you want to proceed, type "Y" in the console and run it.
   The packages needed will now be downloaded and loaded into your environment.
7. You can now execute the rest of the code in the file as needed.

## Using a Quarto file
The script is written in a Quarto format. This allows for the integration of text and code in one document. It is advicable to first run the renv codeblock at the top of the script, and then run the following blocks one by one. The script will take approximately 20 minutes to run (depending on the operating system). If needed, runtime can be lowered by lowering the number of replications in the script. However, the precision of the outcomes will be impacted.
