An Overview of Non-Intrusive Load Monitoring: 
Approaches, Business Applications, and Challenges
Mengmeng Zhuang, Mohammad Shahidehpour, Fellow, IEEE and Zuyi Li, Senior Member, IEEE
--> 


A. General Framework of NILM  
 
 1 Data 
Acquisition&
Preprocessing 
  2 Event 
Detection
 3  Feature 
Extraction
 4 Load 
Identification


Identification of Load Signatures : 
window of margin and shifted sample methods -->


Window of margin:

Regularizes models to prevent overfitting
Restricts models to make predictions that are within a certain margin of the training data
Can be done by adding a penalty function to the loss function
Shifted sample:

Augments training data to improve model robustness
Creates new training data samples by shifting the existing samples by a small amount
Can be done by adding random noise to the features of the existing samples or by shifting the samples along the time axis
Use in non-intrusive load monitoring:

Window of margin methods can help to ensure that NILM models generalize well to unseen data.
Shifted sample methods can help NILM models to learn to be more robust to noise and other variations in the data.
Examples in NILM:

Window of margin loss functions: The "window with margin" method proposed by Azzini et al.
Shifted sample augmentation: The "shifted time series" method proposed by He et al.
