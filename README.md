

## Installation

Fresh installtion

  $pip install nsepy

Upgrade

  $pip install nsepy --upgrade
 
 ## Usage
 
 get_history(symbol="stock name", 
            start=("date from which you want data(In date format)") 
            end = ("date from which you want data(In date format)")
            
Function __get_history__ fetches the price history of stocks/indices/derivatives and returns a pandas dataframe

## Result

You can get data in below format.


           Symbol Series  Prev Close   Open    High     Low   Last   Close  \
Date                                                                         
2021-03-22   SBIN     EQ      371.15  372.0  372.80  363.50  367.6  367.00   
2021-03-23   SBIN     EQ      367.00  368.7  377.95  367.05  372.3  372.70   
2021-03-24   SBIN     EQ      372.70  368.5  369.05  358.65  360.1  359.85   
2021-03-25   SBIN     EQ      359.85  360.0  360.85  345.20  356.3  355.20   

              VWAP    Volume      Turnover  Trades  Deliverable Volume  \
Date                                                                     
2021-03-22  367.73  28461974  1.046619e+15  242100             6057167   
2021-03-23  372.08  41032380  1.526720e+15  304725             9512982   
2021-03-24  363.63  42318999  1.538857e+15  385721            12800434   
2021-03-25  353.03  57495003  2.029720e+15  438853            15832997   

            %Deliverble  
Date                     
2021-03-22       0.2128  
2021-03-23       0.2318  
2021-03-24       0.3025  
2021-03-25       0.2754  
