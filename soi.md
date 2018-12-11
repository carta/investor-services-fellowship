# Schedule of Investments

The most important feature of the Carta Investor Services product is the Schedule of Investments.

The Schedule of Investments is the definitive list of all investments made by a fund.

A simplified excel version looks like this:

![image](https://user-images.githubusercontent.com/7346422/49432108-cabce480-f763-11e8-88e2-5bae0667d4ac.png)

Create a frontend using the framework of your choice (React, Angular, JQuery, etc) that displays this data in a table form.

Include the following features:
1. Make an API call to this URL for the data: https://gist.githubusercontent.com/cranium/d8b83184bf0750f2c834760b7c9203dc/raw/a73a70716951f77b90e84b8848ff1fee46938dd1/soi.json
2. Include a date picker to choose a date from which date to pull data (append ?date=YYYY-MM-DD to the API URL to simulate pulling data for a different day). If a new date is selected the table should reload.
3. Ability to expand/collapse the assets underneath an investment.

Bonus:
Include the ability to expand/collapse all of the investments at once.
