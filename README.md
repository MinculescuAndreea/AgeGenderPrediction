01/07
* Convert txt file to csv: split txt into lines and split each line at "\t", put in a pandas dataframe and drop 
irrelevant columns
* Get path of an image given index in dataframe. Convert image to numpy array. Visualize results
* PROBLEM: images with same path name

05/07
* Fixed path problem: used face_id
* Cleaned dataset
  * Removed entries with missing values
  * Removed gender "u"
  * Defined new non-overlapping age intervals
  * Framed all ages in intervals
* Investigates age and gender distribution
* PROBLEM: imbalanced age distribution