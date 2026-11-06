> # SUMMARY
> - This is a desktop html file for performing different versions of Logistic Regression on a CSV file.
> - Currently this only works when downloaded and run with the included CSV file
> - The aim is to later implement this into a simple tool for quickly performing simple machine learning through the browser

> INSTRUCTIONS:
> 1. Double click the html file to run the program, or open it in a code editor to view the code
> 2. Load the included csv document from the zip
> 3. each button corresponds to a different model:
> > 2. a. runs logistic regression with the chosen x-axis against the chosen y-axis
> > 3. a. runs logistic regression with the the first 12 collumns against the y-axis
> > 3. b. runs logistic regression choosing best 5 collumns based on recall score
> > 4. a. i. runs logistic regression with regularization
> > 4. a. ii.runs logistic regression with scaling
> > 4. b. runs logistic regression with Mean Square Error as the cost function
> 5. BE SURE TO SET FLU TO Y AXIS BEFORE RUNNING! This uses logistic regression meaning the Y axis must only contain 1s and 0s
	
NOTE:
first logistic regression formula uses selected xaxis value. 
Other formulas only use it for the display.

you can check the console (right click) to get the function's weights.
Please enjoy!
