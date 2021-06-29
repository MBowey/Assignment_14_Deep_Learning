# Model Results & Answers


## Overall Performance of Each Model

    * Which model has a lower loss?

        The Closing Price model had the the lower evaluated loss ratio across all window sizes. 

    * Which model tracks the actual values better over time?

        The Closing Price model tracked the actual values better over time. The Fear & Gread model overestimated in the first month and then underestimated from May to June. The predictions where fairly flat across all window sizes. The Closing Model trended upwards month-to-month, which was more in-line with the actual values. 

    * Which window size works best for the model?

        A Window Size of 1 worked best for the Closing Model, as it had the lowest loss ratio. It also tracked the volatility of the actual values much more closely. 

        A Window Size of 1 for the Fear & Greed Model was also better; however, the model overall was quite poor at predicting the actual values across all Window Sizes. 


### Fear & Greed Model 
    * Window Size 10
        * Observable Loss Ratio Range:       0.0225 and 0.0260      
        * Evaluated Model Loss Ratio:        0.1219    
        
        
    * Window Size 5
        * Observable Loss Ratio Range:       0.0221 and 0.0272   
        * Evaluated Model Loss Ratio:        0.1211
        

    * Window Size 1
        * Observable Loss Ratio Range:       0.0516 and 0.0259
        * Evaluated Model Loss Ratio:        0.1117
        


### Closing Price Model 
    * Window Size 10:
        * Observable Loss Ratio Range:       0.0218 and 0.0136
        * Evaluated Model Loss Ratio:        0.0616
        
        
    * Window Size 5:
        * Observable Loss Ratio Range:       0.0237 and 0.0092  
        * Evaluated Model Loss Ratio:        0.0490


    * Window Size 1:
        * Observable Loss Ratio Range:       0.0508 and 0.0032            
        * Evaluated Model Loss Ratio:        0.0267
