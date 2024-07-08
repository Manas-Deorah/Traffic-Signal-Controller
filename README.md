# Traffic-Signal-Controller

Specifications:
1. The signal on the Highway gets the highest priority so it will be green by default. Occasionally, a car comes on the country road. Then the signal on the country road must 
   turn green just long enough for the cars to pass.
2. As soon as there are no cars on the country road, the signal turns yellow and then red and signal on highway turns green.
3. There is a sensor to detect cars on the country road. It sends input signal X to the controller.X=1 if cars are present otherwise X=0.
    
     State  HWY     CNTRY   
     
     S0    GREEN    RED
     S1    YELLOW   RED
     S2    RED      RED
     S3    RED      GREEN
     S4    RED      YELLOW
