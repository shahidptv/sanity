# Next.js Application Using Sanity and Postgre SQL
Create a Website in Next JS using Headless CMS Sanity, TailwindCSS, TypeScript and Drizzle Postgre SQl

Before going to Create a Website in Next JS using Headless CMS Sanity and Drizzle Postgre SQl we must have our environment setup ready. If we are going to create Next Js application # first time then we must follow these steps:

✔ **Step-1**: Install Integrated Development Environment (IDE) Visual Studio Code (VS Code) using link:  https://code.visualstudio.com/


✔ **Step-2**: Install Node.js (Latest Version) from https://nodejs.org/en/download/current/ 

	Check your installed version by writing following comman in terminal
 
 		node -v

✔ **Step-3**: Install TypeScript following instructions given in link: https://www.npmjs.com/package/typescript

   We can also install by writing following commands in command prompt

                 npm install -g typescript

                 tsc -init

✔  **Step 4**: Create a new Next.JS app using following command in VS Code Terminal or Command Prompt (https://nextjs.org/docs/getting-started/installation)

		npx create-next-app
 

✔  **Step 5**: **Install Sanity Studio** write/paste this command in cmd/terminal

	npm create sanity@latest -- --template clean --create-project "Sanity Project" --dataset production


# What is Sanity?

           		https://www.sanity.io

Sanity is a headless Content Management System (CMS), It is a composable content cloud. Sanity is the most flexible, entirely composable solution for content — and meet our modern architecture ambitions.


You can rename Sanity Project in above comman with your project name.

During Installation Setup Process these Steps will be followed:

Create an account. Select a login provider from the list of options, and confirm with Enter. After creating an account in the browser, come back to the command line window.
It will ask you the following questions.
Would you like to add configuration files for a Sanity project in this Next.js folder? Yes
Would you like an embedded Sanity Studio? Yes
Would you like to use the Next.js app directory for routes? Yes
What route do you want to use for the Studio? /studio
Select project template to use Clean project with no predefined schemas
Would you like to add the project ID and dataset to your .env file? Yes
Wait a bit for the installation process to complete. When you get a Success! message, you're good to move on to the next step.


✔  **Step 6**: Run the Studio Locally by starting the NextJs project.

		npm run dev
 
  👉 When build will complete successfully then Run the project over browser using http://localhost:3000/studio It will ask you to add 
     the URL as a CORS origin. Click on Continue to open the Sanity management dashboard. From there, you need to add the CORS origin. 
     The server will automatically rebuild the studio and refresh the browser on saving code after modification.
    
 # To Learn about sanity more 

	https://www.sanity.io/docs/overview-introduction

	https://www.sanity.io/docs/create-a-schema-and-configure-sanity-studio

	https://github.com/sanity-io/next-sanity
