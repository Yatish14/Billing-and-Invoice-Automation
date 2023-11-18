# Billing-and-Invoice-Automation
1. Front End
-> Users can login using Google Authentication and then decode the token generate using jtw-decode to obtains user infoormation and send to back end
-> User can view their usage details,billing details and invoice details and they can send invoices to their mail for respective plans
2. Back End
-> By using Zapier Webhooks user gets an invoice email according to the usage details,plan and billing details
3. Data
-> Used sample json file for storing data and then sending data to front end from back end
4. Zapier
-> Created web hooks which trigger on post some data and set up action as sending invoice mail to user
