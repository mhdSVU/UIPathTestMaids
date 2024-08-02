# Important Notes:

1. **VPN-related Activities Skipped**: All requested VPN-related activities were skipped because the website is inaccessible due to VPN being illegal in the UAE.

2. **Email Configuration**: The bot will use the default email account below (to change it, please configure `config.csv`):
    - **Email Name**: mohammedsawwas.rpa4.maids.cc@gmail.com
    - **Email Password**: srjndeptjnakllhe

3. **Processing Time**: It takes 2-3 minutes to process each transaction. However, the workflow might take an additional 4 minutes for one of the transactions. Please be patient and do not interrupt the workflow!

4. **Monitor the Workflow**: During execution, you don't need to close the message boxes that might appear while the workflow is running, as they have all been configured to close automatically after a few seconds.

# Run Steps:

**Before running the workflow, ensure there is at least one email in the inbox with the following properties**:
- **Unread**
- **Subject**: maids.cc RPA test (Configurable using `config.csv`)
- **Attachment**: test.xlsx containing the records to be processed (Configurable using `config.csv`)

1. **Download the Package**: Download the `MohammedYouserSawwas_RPA.1.0.1.nupkg` file.

2. **Create a Batch File**: Include the following command in a text file, customizing the path values inside square brackets to the corresponding values on your machine:
   ```sh
   [C:\.....\UiRobot.exe] execute --file [C:\...\MohammedYouserSawwas_RPA.1.0.1.nupkg]

3. **Run the Batch File**: Save the text file with a .bat extension and double-click on it. The workflow will start working!

