# Installing and running the app:

It is also possible to run the website privately in your local machine for development purposes. To install the product simply clone with HTTPS the master branch into pycharm. The required modules and dependencies will be automatically installed using our requirements.txt file, if prompted to install the required dependencies then simply click install requriements.  Also the bash command: pip install -r requirements.txt can be used on the terminal to install all requirements as well.

To run the application navigate to the main.py file and run the python file. After a couple seconds a link will appear on the python console indicating that the web app can be run on a specific link (ex. * Running on http://127.0.0.1:5000/). Simply click this link to launch the web application on your browser preferably on google chrome. 

# How to use the app:

When the product launches you will be redirected to the home page which has all the features of the app. Before using any of the features make sure to sign up or login to an account with a valid email address and password. If redirected to the payment page simply click on the logo to be redirected to the home page. Now you are ready to run any of the analysis methods.

To run fundamental analysis simply click on the Fundamental tab on the navigation bar. Input the ticker symbol of your stock and select the default data source to yahoo then click analyze. If the ticker symbol is invalid then a warning stating “Invalid ticker. Please try again.” will be flashed and you will be able to retry entering a ticker again. When a valid ticker symbol is entered the metrics relating to fundamentals will be displayed along with the latest company news relating to the stock ticker. The export button can be clicked to download a csv file containing the Fundamental information displayed for further analysis if needed.

The same procedure will be used to run Technical Analysis. Simply click the Technical tab and input the stock ticker along and select the data source to the default yahoo finance. Once analysis is clicked the technical metrics will be displayed along with a summary and interpretation of the results. A live interactive chart from Tradingview will also be displayed on the page allowing the user to select various technical indicators as well. Similar to the fundamental page the export button will download a csv file containing the technical analysis metrics.

Similarly for the Valuation page simply provide the stock ticker, expiration date, option type, style, default data source,and the ITM/ATM/OTM values. Then when analize is clicked various financial models compute fair values for the specified option and the metrics are displayed to the user to be interepereted

The profile icon at the top right of the page can be used to access the users account and make any modifications. The hyperlink at the top stating “delete Account Log Out” on the top left can be used to delete the users account. The payment system and subscription services are not currently implemented.

The contact page can be used if there are any questions regarding the software. To use simply enter your email along with the subject and message and we will get back to you as soon as possible.

