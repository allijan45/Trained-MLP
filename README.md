# Trained-MLP
# File contains zipped folder with 1 trained multi-layer perceptron model named 4.model that can be opened in Weka explorer

#User should import data from CSV/arff file from Weka Explorer in the 'Preprocess' tab.
#Files should include the following attributes: original_shape_Flatness, original_shape_Sphericity, oiginal_firstorder_RottMeanSquared, original_glcm_lmc2, original_glcm_InverseVariance, original_glcm_JointEnergy, original_glszm_ZoneEntropy, original_ngtdm_Busyness, Gender, Grade, SizeMeasure_mm, GTVp_mL, Local_Fail.y, DurationOfLocalControl, SUV, AgeAtDiagnosis
  #The original dataset contained radiomic features extracted with OnkoDICOM the Pyradiomic features
  #Gender was set as 0 for male, 1 for female
  #Size_Measure_mm was the longest axis in mm
  #GTVP_mL is the mL of the gross tumour volume
  #Local_Fail.y is set as 0 for no local failure, 1 for local failure
  #DurationOfLocalControl and AgeAtDiagnosis are in years
  
#All attributes should be of class "Numeric" except attributes 'Gender', 'Grade', and 'Local_Fail.y' which should be of the class "Nominal".

#File for trained MLP can be opened in Weka from the 'Classify' tab by right-clicking in the Results list
#New dataset can be run against trained MLP by selecting outcome "(Nom) Local_Fail.y" and running the classifier.
