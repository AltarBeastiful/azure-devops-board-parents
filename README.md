# azure-devops-board-parents
![logo](icons/icon128.png)
Fetch and display the parent of each item in Azure Devops Boards

## Pre-requisites
 - In your board display settings, choose to display the ID of the work item on the card
 - Use the new azure devops url pattern (eg. https://dev.azure.com/org/....)

## How to use
 - I have a problem with CRX exe file so for now please do that
   - Clone/Download the repository
   - Go to your chrome extensions page
   - Activate developer mode
   - Click load unpacked extension
   - Select the folder of the project you've cloned
 - Go to the settings of the extension (right click -> options on the extension icon) and fill-in the 2 required fields.
   - Your email address
   - Your token (link to generate it is provided) that needs just read access to work items
 - Refresh the board page and click on the extension icon
 - If anything goes wrong at any time or it doesn't work, please just refresh the page and re-click on the extension icon

## Contributing
 - It is not all perfect, especially the way I retrigger rendering when devops rerender elements (which is ALL THE TIME ..) so if you see some issues and want to help, feel free to send pull requests
 - Please feel free to also raise any issues and i'll try my best to fix them
 - As much as possible if adding new feature, please create new background/inject scripts and include them in manifest

# Enjoy
