# ICITTextAnalysis
Indus script ICITcorpus Analysis

Presented at : Emerging Perspectives on the Harappan civilization. Colloquium Feb 10-12, 2023 at IIT Gandhinagar- https://asc.iitgn.ac.in/assets/events/training_workshop/Book_of_Abstracts_com.pdf. Page 80
Paper: Journal of Emerging Investigators, Accepted
Poster: IEEE, ISEC Conference -https://www.ieee-isec.info/day/1

-------------------------------------------------------------------------------
Dataset was created as a csv file from ICIT web site from raw html files for each for the Text Data labels were changes and a linearized copy of the original text was added. n-gram model was build from this corpus and various Tests run to decipher unclear characters
 
 This is how you use this project:
 
 Download All Jupyter Notebooks
 - Get the csv input files with Indus text data (not in GitHub). Contact Varun Venkatesh for this.
 Needed:
   icit_sign_corpus.csv
   icit_text_text_corpus.csv
 
 - Get the ICIT Sign image files from ICIT website (not in GitHub) for images to render correctly in the Jupyter notebook. Contact Varun Venkatesh for this.
 
 1) Run ICITTextAnalysis-InputDataProcessing-All
 This reads the csv, cleans up and pickles the cleaned up data
 
 2) Run ICITTextAnalysis-Textual Analysis
  This uses pickled csv, and runs Textual Analysis on the Indus texts
  
 3) Run ICITTextAnalysis- Distribution Analysis
 This uses pickled csv, and runs Distribution Analysis on the Indus texts
 
 4) Run ICITTextAnalysis-Language Models
 This uses pickled csv and runs language models and then pickles language model output
 
 5) Run ICITTextAnalysis- Helpers and Tests -
 This uses picked csv and pickled language models and runs analysis on the Indus texts for Sign Fill-in models.
 
 6) Run ICITTextAnalysis- Anomalous Text Analysis
 This is used to identify Anomalous texts in the Indus corpus from West Asia using Perplexity measures. Uses pickled csv and pickled language models.
 
 Note: ICIT sign images don't render in github in these notbooks, as they are not uploaded to github. When you run these notebooks locally, you will need to have the image files locally.
 
 ![Visitor Count](https://profile-counter.glitch.me/varundataquest/count.svg)
