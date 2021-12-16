# budget-tracker

Track your expenses one at a time by inputting your itemized expenses and deposits. Keep track of your finances with this handy little tool.

Simply input the transaction name and dollar amount. You can then click on either the "Add funds" or "subtract funds" to update your total balance. After inputting your entries, the table automatically populates with the latest transactions and balance, and the chart will update to display the latest transactions.

Functionality is fully available in offline mode, so you can keep using it while on the go or outside of reception area. As soon as you return to connectivity, all logged expenses/deposits get automatically updated to your history. Transactions are cached to IndexedDb to ensure there is no lost user input.

![image](https://user-images.githubusercontent.com/85508030/146408149-a09fe10c-0a14-491e-8ebe-229e5bdb3c1a.png)

## Usage

Clone the repository onto your local device.

Run 

```
npm init -y
npm install
```

Ensure all npm dependancies are installed correctly.

Then in your terminal, run
```
npm start
```

You should see a success message in the terminal, indicating that the application is running on port 3001. Open [http://localhost:3001/](http://localhost:3001/) in your browser to begin using.

## Technologies

This is a progressive web application, that can be downloaded onto your device.
<ul>
  <li>Express</li>
  <li>MongoDB</li>
  <li>IndexedDB</li>
  <li>Manifest.json</li>
</ul>

## Deployment

This application is deployed on Heroku and can be accessed at the following [link](https://protected-crag-30220.herokuapp.com/).

Git Hub Repository is located [here](https://github.com/jasongrossman/budget-tracker).

Developed by: Jason Grossman
