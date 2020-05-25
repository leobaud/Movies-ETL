# Movies-ETL

# Assumtions

1) Files are saves in a "Data" folder. "file_dir" is set to this folder. The resource files need to be saves into this "Data" folder so it can be loaded into the code. As long as the code is opened through the correct file path and saved into the "Data" folder, the files will be extract.

2) Script is set to read and extract json and csv files. Any other file extension will require an update in the script. 

3) The script is very well structured and simplified, any new additions or changes to the code would be really easy to include.

4) The script has been written to recognise the json and csv files with an specific name, as downloaded from the data sources. Any changes on the file names will require a little update in the script. Additional coding might be included so that the code accepts the files with any name given.

5) The code is set to transform columns with specific names. Any column name changes in the data source (json and csv) would require a change in the code as well. The code runs smoothly with the correct data, any changes to the data require a rescript of the code. 
