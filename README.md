# Party-Logs

In this project, we worked with an existing project that displays a list of parties on a webpage. The goal was to fix issues and add functionality to the project. Here's a summary of what we did:

Cloned the repository: We started by cloning/copy the project from repository provided to our local computer. This allowed us to work with the project files.

Opened the project in VSCode: We navigated to the project folder and opened it in Visual Studio Code (VSCode) or any other code editor of our choice. This allowed us to view and modify the project files.

Launched the webpage with Live Server: We used the Live Server extension in VSCode to launch the index.html file. This allowed us to see the webpage in our browser and identify any rendering issues.

Found missing functions: Upon observing that the page was not rendering properly, we inspected the console in the browser's developer tools to identify any error messages. Based on the error messages, we located the missing functions that were causing the issues.

Fixed the details button: We wrote code in the script.js file to fix the details button functionality. This involved modifying the event listener for the details button to ensure it called the renderSinglePartyById function with the correct party ID. This change allowed the details of the selected party to be displayed on the webpage.

Debugged undefined values: After fixing the details button, we noticed that some values in the party details were returning undefined. We investigated the code that fetched the party details from the API and checked the API response. By identifying any missing or undefined values, we made adjustments to the code to handle those cases and ensure the party details were displayed correctly.

Enabled the delete button: We located the event listener for the delete button in the script.js file and updated it to enable the delete functionality. This involved calling the deleteParty function with the correct party ID to delete the party from the API. After deleting a party, we updated the UI to reflect the changes by re-rendering the updated list of parties.

Added CSS styles: Lastly, we applied CSS styles to the elements in the project to enhance their appearance. We modified the existing CSS styles in the style.css file and added new styles as needed. This allowed us to customize the color, size, shape, and position of the elements to achieve the desired visual presentation.

Overall, the assignment involved fixing issues related to missing functions, improving the details button functionality, debugging undefined values in the party details, enabling the delete button, and applying CSS styles to enhance the visual appearance of the project.




