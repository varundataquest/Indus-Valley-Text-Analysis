# ICITTextAnalysis
Indus script ICITcorpus Analysis
Dataset was created as a csv file from ICIT web site from raw html files for each for the Text Data labels were changes and a linearized copy of the original text was added. n-gram model was build from database and various Tests run to decipher unclear characters
 
 This is how you use this project:
 
 Download All Jupyter Notebooks
 - Get the csv input files with Indus text data (not in GitHub). Contact Varun Venkatesh for this.
 - Get the ICIT Sign image files from ICIT website (not in GitHub)
 
 1) Run ICITTextAnalysis-InputDataProcessing-All
 This reads the csv, cleans up and pickles cleaned up data
 
 2) Run ICITTextAnalysis-Textual Analysis
  This uses pickled csv, and runs Textual Analysis on Indus texts
  
 3) Run ICITTextAnalysis- Distribution Analysis
 This uses pickled csv, and runs Distribution Analysis on Indus texts
 
 4) Run ICITTextAnalysis-Language Models
 This uses pickled csv, and runs language models and pickles language model output
 
 5) Run ICITTextAnalysis- Helpers and Tests -
 This uses picked csv,  and pickled language models and runs analysis Indus texts for Sign Fill-in. Contact Varun Venkatesh for this.
 
 6) Run ICITTextAnalysis- Anomalous Text Analysis
 This is used to identify Anomalous texts in the Indus corpus from West Asia using Perplexity measures. Used Pickled csv and language models
 
 ![Visitor Count](https://profile-counter.glitch.me/{YOUR USER}/count.svg)
