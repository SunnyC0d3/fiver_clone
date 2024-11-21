# Fiver Clone Project

A simpler clone based off the Fiverr app. It uses React, NodeJS and PostgreSQL as the tech stack.

![Alt text](/screenshots/readme-img-1.png?raw=true "Screenshot 1")
![Alt text](/screenshots/readme-img-2.png?raw=true "Screenshot 2")
![Alt text](/screenshots/readme-img-3.png?raw=true "Screenshot 3")
![Alt text](/screenshots/readme-img-4.png?raw=true "Screenshot 4")

## Installation

1. Go into each directory and make sure to run the `npm install` command.
2. If you haven't already, make sure to visit the `.env` and require the correct keys, make sure to use `.env.local` for testing.
3. When working with the database, have a working environment ready. For this project, we used PostgreSQL. The Prisma commands are within the `./server/package.json` for migrating.
4. Once everything is configured, run `npm run dev` in the `./client` folder. Run `npm run start` in the `./server` folder.

## Issues

Current issue is that the API Keys might currently be exposed to the browser but this is only for testing purposes, for future improvements a backend system or a serverless system can be considered in order for better protection against exposure to sensitive information.

There are also issues with the UI, this application was built purely for testing hence there will be issues such as e.g. responsiveness not working. It was in no way designed to have the full functionality of fiverr. In future improvements, these aspects can be considered. 