# Demo Video - [Watch Here](https://youtu.be/WNsV_IZjbcw)
## Before Automation
This task takes approximately 2 minutes. Note that it will take longer if there’s a longer list.

## With Automation
After filling in the form, it only took approximately 37 seconds to receive and open the email with the recommended artist list. This is only a quarter of the time compared to before automation as it eliminates the human manual work needed to compile information and send out an email. Additionally, receiving and opening the WhatsApp notification only took 30 seconds. The process with an added-on notification is still at least 40% faster than the process above. 

# Problems
## Event Agencies:
1. Agencies are always looking for artists to perform for their client’s events. They tend to not know what artists are available that is within their budget.
2. They struggle to do up quotes as they need to wait for music labels to respond.

## Music Labels:
1. They receive many messages and inquiries about what artists they have.
2. The account servicing person will have to compile artists’ information and reply to the inquiry manually.

# Solution
Create an automated workflow whereby:
- When someone fills in a form for artist booking 
- The form will have mandatory fields to fill in the music genre desired and budget
- The genre and budget will be used to search up artist details from a master Artist List database
- The artist details will then be fed back to the responder via email 
- Music label will receive a WhatsApp notification with responder’s details
- At the end, the account servicing person from the music label can refer to the responses and choose whether to reach out. The event agency on the other hand will be able to do up a quotation while waiting for the full details.

# Applications
- Zapier
- Google Form
- Google Sheets
- Google Drive
- Gmail
- JoyForm

# Thought Process Drafting the Automation Workflow
![image](https://github.com/Kfkyyian1/automate_recommending_artists/assets/146427900/15dd8517-560b-480e-bcfb-97f1a8f41c02) <br>
To create the automated workflow as shown above, 3 components were kept in mind, which are human, data and systems. 
## Human: 
Event agencies and music label

## Data: 
1.	Event agencies to provide event information and request for artist information.
2.	Music label to respond by providing artist information.

## Systems (Zapier):
1.	Google Form: Collect event information from event agencies.
2.	Google Sheet:
   - Compare budget and music genre against master database.
   - Create new spreadsheet with filtered list.
3. Google Drive: Store Google Sheets
4. Gmail: Attach sheet with artist information to email before sending out.
5. JoyForm: Music label to receive new WhatsApp notification regarding new requests. 




