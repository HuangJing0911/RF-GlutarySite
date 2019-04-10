https://github.com/HussamAlbarakati/RF-GlutarySite

This is the ReadMe file. This GitHub repository contains all the materials for paper titled "RF-GlutarySite: Random Forest based predictor for Glutatrylation Sites",
Albarakati H., Saigo H, Newman RH and KC DB, Molecular Omics.

1. Directory WINDOWS_SEQ_23 contains the following four files:

'pos-train-windo-23.txt' Training data for positive sequences.  It has 400 positive data.
'neg-train-windo-23.txt' Training data for negative sequences.  It has 1703 negative data.
'pos-test-windo-23.txt'  Test data for positive sequences.   It has 44 positive data.
'neg-test-windo-23.txt'  Test data for negative sequences.   It has 203 negative data.



2. Directory FEATURES contains the features for positive and negative windows for AAindex, Afactor, Bin (Binary Encoding), Combined-Features, FEPS (All the features from FEPS Server). This director has following sub-directories AAindex, AFactor, Bin, compressed-combine-Train-Test.zip and compressed-FEBS-Train-Test.zip. The files in these subdirectories are:


'bin-train-440.csv' which has binary code (BE) of protein sequences for train file. The feature length is 440
'bin-test-440.csv’ which has binary code (BE) of protein sequences  for test file. The feature length is 440

'output_Train_AAindex-88.csv' which has 4 physiochemical properties (AAindex) of protein sequences for train file. The feature length is 88 
'output_test_AAindex-88.csv' which has 4 physiochemical properties (AAindex) of protein sequences for test file. The feature length is 88.


'output_Train_AFactor-110.csv' which has 5 physiochemical properties (Afactor) of protein sequences for train file. The feature length is 280  'output_test_AFactor-110.csv' which has 5 physiochemical properties (Afactor) of protein sequences for test file. The feature length is 280.


'FEPS-train-12249.csv’  which has group of different features used Feature Extraction from Protein Sequence(s)Server(FEPS) for train file. The feature length is 12249 
'FEPS-test-12249.csv’ which has group of different features used Feature Extraction from Protein Sequence(s)Server(FEPS) for test file. The feature length is 12249



compressed folder named "Combined-features" has file named 'combine-train-All-12887.csv’ we used with RF to develop our method named'RF-GlutarySite'which combined binary code(BE), 4 physiochemical properties(AAindex), 5 physiochemical properties(Afactor), and group of different features used Feature Extraction(FEPS) of protein sequences for train file. The feature length is 12887

compressed folder named "Combined-features" has file named 'combine-test-All-12887.csv’ we used with RF to develop our method named'RF-GlutarySite'which combined binary code(BE), 4 physiochemical properties(AAindex), 5 physiochemical properties(Afactor), and group of different features used Feature Extraction(FEPS) of protein sequences for test file. The feature length is 12887

