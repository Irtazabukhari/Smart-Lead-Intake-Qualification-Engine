Tools & Nodes Used
Webhook Node – Listens for incoming POST requests from external forms and lead sources.

Edit Fields Node – Cleans and maps incoming data into a standardized JSON format.

Code in JavaScript Node – Executes custom logic for data enrichment or complex lead scoring.

If Node – Conditional gatekeeper that routes leads based on qualification criteria (Qualified vs. Unqualified).

Gmail Node – Delivers instant email notifications to the team for high-priority "True" leads.

No Operation Node – A placeholder that manages "False" path leads to ensure clean execution.

Google Sheets Node – Appends every lead entry into a master spreadsheet for CRM logging.

Respond to Webhook Node – Sends a confirmation handshake back to the source to close the connection.
