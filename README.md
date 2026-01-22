# n8n-google-lead-generation
I made this workflow today only and have been working on this from 3 days, like in this workflow, lead generation from Google Maps and getting all the details of the lead, like mail and website and we will provide the company summary and drafted mail also so you can approach them directly from those leads.

## Tools used in this

-Webhook trigger for getting data from Lovable. I make lead form on lovable for more good-looking and versatile

-code node for pagination

- Serp API for getting google maps

-firecrawl API for scraping the website and getting markdown

-AI agent (summary agent) to analyze the markdown and give the proper summary of that markdown

- AI agent 2 (drafted mail) to draft the mail based on the summary given by previous agent and draft the mail like that they can approach them directly for their offers

- Google Sheets to collect all the data from these nodes

-google drive to copy the data and make a file

- Google Drive again for downloading the data and make it into a PDF and excel sheet and then download it

- Gmail node to send that pdf data to users who fill out the form with all the data they requested

-Google Sheets: Delete node to delete the rows after sending the previous data from PDF.

- Google Drive: Delete node to delete the copied file so they can't store it in my drive
