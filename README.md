Next.js Portfolio Project
Welcome to the repository for my Next.js portfolio project!

Environment Variables
To run this project, you will need to add the following environment variables to your .env.local file:

makefile
Copy code
# Sanity CMS Configuration
NEXT_PUBLIC_SANITY_PROJECT_ID=
NEXT_PUBLIC_SANITY_DATASET=
NEXT_PUBLIC_SANITY_API_VERSION=2023-07-21
NEXT_PUBLIC_SANITY_ACCESS_TOKEN=
NEXT_PUBLIC_SANITY_HOOK_SECRET=

# GitHub Contribution Graph Details
NEXT_PUBLIC_GITHUB_USERNAME="your-github-username"
NEXT_PUBLIC_GITHUB_JOIN_YEAR="year-you-joined-github"
Setting up Environment Variables
Sanity CMS Configuration:

NEXT_PUBLIC_SANITY_PROJECT_ID: The project ID of your Sanity CMS project.
NEXT_PUBLIC_SANITY_DATASET: The dataset name within your Sanity project.
NEXT_PUBLIC_SANITY_API_VERSION: The version of the Sanity API you are using.
NEXT_PUBLIC_SANITY_ACCESS_TOKEN: Access token for authentication with Sanity API.
NEXT_PUBLIC_SANITY_HOOK_SECRET: Secret key for webhooks or other integrations with Sanity.
GitHub Contribution Graph Details:

NEXT_PUBLIC_GITHUB_USERNAME: Your GitHub username.
NEXT_PUBLIC_GITHUB_JOIN_YEAR: The year you joined GitHub.
Make sure to replace placeholders like "your-github-username" and "year-you-joined-github" with your actual GitHub username and join year.

Running the Project
After setting up your environment variables, you can run the project using:

bash
Copy code
npm install
npm run dev
Open http://localhost:3000 in your browser to see the application.

Feel free to expand this template with more details specific to your project or additional setup instructions as needed.
