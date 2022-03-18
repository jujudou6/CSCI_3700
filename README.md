# CSCI_3700
ECU Database Systems
Group #6

Julie Douangdara & Nicholas Johnson

This project shows how we can connect PostgreSQL with flask and show results in a HTML link.

When a user accesses the Flask server with 127.0.0.1:5000/api/update_basket_a, a new row is inserted into basket_a. 
On the browser, it should either show "Success!" Or error message from PostgreSQL.

When a user accesses the Flask server with 127.0.0.1:5000/api/unique, unique fruits in basket_a and unique fruits in basket_b will show in an HTML table. If there are any errors from PostgreSQL, the error message will show on the browser.

Once both of the zip files have been properly downloaded:
Ensure you have Python 3 virtual environment installed with: 
    sudo apt-get install python3-venv
With the terminal open, cd into the proper folder for each question/attempt.
Then create a virtual environment:
    python3 -m venv python_venv
Activate the environment:
    source python_venv/bin/activate
Fulfill the requirements:
    pip3 install -r requirements.txt
Start the server:
    python3 main.py

If ran correctly, the environment will output the flask server. 
It will look like "Running on http://127.0.0.1:5000/"
Copy and paste that link on a web browser and make sure to include either "api/update_basket_a" or "api/unique" after the given url to access the server. 



