My first Codebook
========
Here we have the variables containing in the data.tidy

 [1] "activity"                                                   
 [2] "subject"                                                    
 [3] "TimeDomain_BodyAccelerometer_Mean_X"                        
 [4] "TimeDomain_BodyAccelerometer_Mean_Y"                        
 [5] "TimeDomain_BodyAccelerometer_Mean_Z"                        
 [6] "TimeDomain_BodyAccelerometer_StandardDeviation_X"           
 [7] "TimeDomain_BodyAccelerometer_StandardDeviation_Y"           
 [8] "TimeDomain_BodyAccelerometer_StandardDeviation_Z"           
 [9] "TimeDomain_GravityAccelerometer_Mean_X"                     
[10] "TimeDomain_GravityAccelerometer_Mean_Y"                     
[11] "TimeDomain_GravityAccelerometer_Mean_Z"                     
[12] "TimeDomain_GravityAccelerometer_StandardDeviation_X"        
[13] "TimeDomain_GravityAccelerometer_StandardDeviation_Y"        
[14] "TimeDomain_GravityAccelerometer_StandardDeviation_Z"        
[15] "TimeDomain_BodyAccelerometerJerk_Mean_X"                    
[16] "TimeDomain_BodyAccelerometerJerk_Mean_Y"                    
[17] "TimeDomain_BodyAccelerometerJerk_Mean_Z"                    
[18] "TimeDomain_BodyAccelerometerJerk_StandardDeviation_X"       
[19] "TimeDomain_BodyAccelerometerJerk_StandardDeviation_Y"       
[20] "TimeDomain_BodyAccelerometerJerk_StandardDeviation_Z"       
[21] "TimeDomain_BodyGyroscope_Mean_X"                            
[22] "TimeDomain_BodyGyroscope_Mean_Y"                            
[23] "TimeDomain_BodyGyroscope_Mean_Z"                            
[24] "TimeDomain_BodyGyroscope_StandardDeviation_X"               
[25] "TimeDomain_BodyGyroscope_StandardDeviation_Y"               
[26] "TimeDomain_BodyGyroscope_StandardDeviation_Z"               
[27] "TimeDomain_BodyGyroscopeJerk_Mean_X"                        
[28] "TimeDomain_BodyGyroscopeJerk_Mean_Y"                        
[29] "TimeDomain_BodyGyroscopeJerk_Mean_Z"                        
[30] "TimeDomain_BodyGyroscopeJerk_StandardDeviation_X"           
[31] "TimeDomain_BodyGyroscopeJerk_StandardDeviation_Y"           
[32] "TimeDomain_BodyGyroscopeJerk_StandardDeviation_Z"           
[33] "TimeDomain_BodyAccelerometerMagnitude_mean"                 
[34] "TimeDomain_BodyAccelerometerMagnitude_std"                  
[35] "TimeDomain_GravityAccelerometerMagnitude_mean"              
[36] "TimeDomain_GravityAccelerometerMagnitude_std"               
[37] "TimeDomain_BodyAccelerometerJerkMagnitude_mean"             
[38] "TimeDomain_BodyAccelerometerJerkMagnitude_std"              
[39] "TimeDomain_BodyGyroscopeMagnitude_mean"                     
[40] "TimeDomain_BodyGyroscopeMagnitude_std"                      
[41] "TimeDomain_BodyGyroscopeJerkMagnitude_mean"                 
[42] "TimeDomain_BodyGyroscopeJerkMagnitude_std"                  
[43] "FrequencyDomain_BodyAccelerometer_Mean_X"                   
[44] "FrequencyDomain_BodyAccelerometer_Mean_Y"                   
[45] "FrequencyDomain_BodyAccelerometer_Mean_Z"                   
[46] "FrequencyDomain_BodyAccelerometer_StandardDeviation_X"      
[47] "FrequencyDomain_BodyAccelerometer_StandardDeviation_Y"      
[48] "FrequencyDomain_BodyAccelerometer_StandardDeviation_Z"      
[49] "FrequencyDomain_BodyAccelerometer_meanFreq_X"               
[50] "FrequencyDomain_BodyAccelerometer_meanFreq_Y"               
[51] "FrequencyDomain_BodyAccelerometer_meanFreq_Z"               
[52] "FrequencyDomain_BodyAccelerometerJerk_Mean_X"               
[53] "FrequencyDomain_BodyAccelerometerJerk_Mean_Y"               
[54] "FrequencyDomain_BodyAccelerometerJerk_Mean_Z"               
[55] "FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_X"  
[56] "FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Y"  
[57] "FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Z"  
[58] "FrequencyDomain_BodyAccelerometerJerk_meanFreq_X"           
[59] "FrequencyDomain_BodyAccelerometerJerk_meanFreq_Y"           
[60] "FrequencyDomain_BodyAccelerometerJerk_meanFreq_Z"           
[61] "FrequencyDomain_BodyGyroscope_Mean_X"                       
[62] "FrequencyDomain_BodyGyroscope_Mean_Y"                       
[63] "FrequencyDomain_BodyGyroscope_Mean_Z"                       
[64] "FrequencyDomain_BodyGyroscope_StandardDeviation_X"          
[65] "FrequencyDomain_BodyGyroscope_StandardDeviation_Y"          
[66] "FrequencyDomain_BodyGyroscope_StandardDeviation_Z"          
[67] "FrequencyDomain_BodyGyroscope_meanFreq_X"                   
[68] "FrequencyDomain_BodyGyroscope_meanFreq_Y"                   
[69] "FrequencyDomain_BodyGyroscope_meanFreq_Z"                   
[70] "FrequencyDomain_BodyAccelerometerMagnitude_mean"            
[71] "FrequencyDomain_BodyAccelerometerMagnitude_std"             
[72] "FrequencyDomain_BodyAccelerometerMagnitude_meanFreq"        
[73] "FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_mean"    
[74] "FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_std"     
[75] "FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_meanFreq"
[76] "FrequencyDomain_BodyBodyGyroscopeMagnitude_mean"            
[77] "FrequencyDomain_BodyBodyGyroscopeMagnitude_std"             
[78] "FrequencyDomain_BodyBodyGyroscopeMagnitude_meanFreq"        
[79] "FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_mean"        
[80] "FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_std"         
[81] "FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_meanFreq"    


For to obtain all these variables:
1. We obtain the data from: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

2. We select the subject, activity and features from the data and it is reshaped in differents datasets: test and train.

3. Dataset activity variable was included and renamed using regular expressions

4. We include activity variable to the previus dataframe created

5. Create the data.tidy


For more information about the original data consult:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

