## Introduction

- I have made this as a submission for Richpanel interview round.
- I had to create a POC (Proof of Concept) app. This app will allow clients to connect their fb accounts, listen to their comments or messenger messages and reply to them within the application.
- This repo is for frontend only.
- Backend can be found here: https://github.com/Agrim77/rp-backend
- Deployement can be seen at: https://rp-frontend.vercel.app

<hr />

## Getting Started

First, run the development server:

`npm run dev`

and then open [http://localhost:3000](http://localhost:3000) to see the result.

<hr />

After successful login, chat page will look this:

![1](https://user-images.githubusercontent.com/47441501/130314297-fb42aa73-6d9a-47ac-aa3c-c9a4550f9aad.png)


## Key Features

* Login using Facebook login id and password
* Real time chat update with auto refreshing
* Time stamp to segeregate the messages

<hr />

## Technologies Used:
1. NextJS, NextAuth
2. Recoil JS - For global State management
3. NodeJS - for backend serving (https://github.com/Agrim77/rp-backend)
4. MongoDB - to store user data, messages
5. Socket.io - For continuous hooking of messages from server to client
without refresh
6. Graph API Facebook - For data transactions between facebook page
7. Facebook Webhooks - For continuous updates on pages
8. Messenger API - to receive Messages on profile using Webhooks

<hr />

## Challenges Faced:
1. I was not able to integrate Comments API and webhook because
manage_posts and pages_manage_posts permissions/ feature requires business verification. I could have just shown all the comments on post using API endpoint - me?fields=posts{comments} but that doesnot make sense to display all post and its comments


