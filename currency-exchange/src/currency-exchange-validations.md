   
Validation errors
=================

When request is not constructed properly and no standard status code describes situation, Currency Exchange API will return status code `400` with one of the following validation errors in the payload. To learn more see general guidance on [error handling]()

     Literal                              |  Code | Description                                                                           
     ------------------------------------ | -----:| --------------------------------------------------------------------------------------                              
     negative-amount                      | 51202 | Entered amount must be positive.                                                       
