# Autoresponder Demo<
Combine Bandwidth and Google Sheet's APIs to create an autoresponder with custom keywords, opt out management, and message logging.

### Step 1: Set up your Bandwidth account
Create a Messaging Application with an associated Location. Your credentials as well as the id of this application will be requested in the code.

### Step 2: Set up your Google account
Follow the instructions [here](https://developers.google.com/sheets/api/quickstart/ruby) to generate a `credentials.json` file: . Make sure to save that file in the same directory as your `autoresponder.rb`.

### Step 3: Make a copy of the Google Sheet
The spreadsheet can be found [here](https://docs.google.com/spreadsheets/d/1hQeHCh35xMTLCKuHQJp95RnrTHuQbaEAdbT-CO1Edh0/edit?usp=sharing). Make a copy and add the `spreadsheetId` to the code. The `spreadsheetId` is the value between the "/d/" and the "/edit" in the URL of your spreadsheet.

### Step 4: Blast off!
Run `ruby autoresponder.rb` and you can begin sending texts to one of the phone numbers tied to a location associated with the messaging application you created in Step 1.
