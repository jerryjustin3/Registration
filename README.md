# Registration

To begin, download the ZIP for this repository and then extract the file.
Inside the folder, run the terminal and initialize the node.js packages download using command: **npm init -y**

After initializing the packages, install the express package using command: **npm install express**

After setting all up, run the backend server using: **node server.js** and leave it running in background.

To access the frontend, open **http://localhost/2345/register.html** in browser and try to input some value.
Each input field will validate whether they are empty or are already stored inside the temporary storage running in background. Moreover, username field will verify if the character inputted is above 3 characters, email field will verify the input to be in email format, and phone will verify the field to only accept 10 digits only and must be in numbers.

After successful registration, the page will moved to the next page to show the success message. From there, the user can click on the back button to go back to the registration page.

For automation script, it can be run by openning another terminal in the directory and run **node testingScript.js** (Mind the capital letter).
The script will automatically input the fields and register 10 times. In case of existing record in the storage, it will stop the script process and close in 5 seconds. Otherwise, the inputted records is successfully stored and the script will end.

To check on the storage, go back to the first terminal that is running the server to check on the content. Then, to terminate the server, go to the terminal and press **Ctrl + C**.
