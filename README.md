<p align="center">
  <img width="400" height="225" alt="Image" src="https://github.com/user-attachments/assets/d71bd0a0-a48f-4aa2-be92-222b7753daa9" />
</p>

<div align="center">

# Automated-Research-Paper-Crawler

### Have Claude Automatically Fetch the Up-To-Date Research Papers 

A Comprehensive Guide to Building Your Own Research Journal Library with the Latest Research Papers (Includes Summaries) 

</div>

___

## Features In Each Paper

- A summary of the paper
- Algorithms/Pseudocode Section. (If there is no dedicated source code or repository, Claude generates one for you based from the paper)

## Requirements

1. Claude
2. Notion

___

## Instructions

1. Click the chat/message icon in Claude (Not the code).
2. Click 'New' and the '+' in the chat
3. Click 'Connectors' and add 'Notion' and 'alphaXiv' (alphaXiv retrieves papers from arXiv, so I recommend this one if you're from CS)
4. Copy and Paste the "Notion_DB_Prompt.txt" into Claude to build your Notion Database page in Claude Chat (Not Claude Code). You can check whether your database has been generated properly. 
5. Move into Claude "Code" and enter "Routines" -> "New Routine". 
6. "cloud" -> Name the Routine however you like.
7. At the bottom right corner of the "instructions" -> click the cloud symbol -> "Add Cloud Environment" -> Name it however you like -> "Add environment"
8. Make sure the name of your new cloud environment appears at the bottom right of the instructions window. 
9. Copy and Paste the routines_prompt.txt into the instructions window.
10. At the "Schedule" - I set it to 6AM so that Claude fetches new papers at 6AM, and so that when I wake up, I have a fresh new paper added.
11. Add the connectors (Notion, alphaXiv)
12. Click "create" at the bottom right corner of the routines page.
13. For testing, you can hit "Run Now" and see if the papers get added. 


