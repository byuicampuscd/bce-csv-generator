#Bulk Course Export CSV Generator
This program generates the csv file needed to bulk export courses in d2l

##Setup
Go to options.json and fill the "orgUnits" array with the org units you would like to export.
```javascript
{
    "orgUnits":[/* Place Org IDs Here */]
}
```

##Execution

Open you command prompt and run the following command:
```
node compile
```
The program will then prompt you for you Brightspace login credentials.
Type in you username and password then click "Login".

Once the code has finished running, the csv will be in the "export" folder. 