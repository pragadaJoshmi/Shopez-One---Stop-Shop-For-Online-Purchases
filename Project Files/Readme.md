Project Executable Files :

How to Run ShopEZ in VS Code
1. Open the project in VS Code: Extract the ShopEZ_Upload.zip file, right-click the extracted folder, and select "Open with Code" (or open VS Code and drag the folder in).

2. Start the Backend Server: In VS Code, open a new terminal (Terminal -> New Terminal). In the terminal, type the following commands one by one and hit Enter after each:

bash
cd code/server
npm install
npm start
(Leave this terminal running!)

3. Start the Frontend Application: In VS Code, open a Second new terminal (click the + icon on the right side of the terminal window). In the new terminal, type the following commands one by one and hit Enter after each:

bash
cd code/client
npm install
npm run dev
4. Done! The frontend terminal will give you a local URL (like http://localhost:5173). Ctrl+Click the link to open ShopEZ in your web browser!

Important Note for your friend: They must have Node.js installed on their computer beforehand for these npm commands to work.

