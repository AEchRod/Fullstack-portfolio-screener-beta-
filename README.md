# Fullstack-portfolio-screener (beta)

## Description 

A fullstack app which allows the users to select stocks which they want to track and select the period and interval they want to track and then be
shown the data once the form has been submitted.
Using YFinance to retrieve the stock data as a Pandas dataframe.

#### Installation/requirements

WTForms, YFinance

#### Current errors

It currently fails to show data once the form has been submitted, there seems to be an error in passing input data from the form as a value/variable for
the data we want to retrieve for the stocks?
i.e. interval=none (EVEN THOUGH INTERVAL HAS BEEN SELECTED IN FORM)
