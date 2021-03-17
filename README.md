# invoice_email_generator
Push your email to send invoice to your customers

### Logic behind this:
1. Order file that contains all the order details (oms -REPO.xlsx)
2. BP file that contains all the business partner information (sap.xlsx)
3. Invoice header template in excel -> export to pdf and name as header subsequently
4. A folder created in the source you determine (generated invoice will be placed here, so there is a track record)
5. Edit the trigger_date in script <- can be set up to trigger daily
6. this script will send email from the email you input to the recipient email in the BP file

