## Getting Started

First, run the development server:

npm run dev

and then open [http://localhost:3000](http://localhost:3000) to see the result.

Technologies Used:
1. NextJS, NextAuth
2. Recoil JS - For global State management
3. NodeJS - for backend serving
4. MongoDB - to store user data, messages
5. Socket.io - For continuous hooking of messages from server to client
without refresh
6. ngrok - For temporary server hosting
7. Graph API Facebook - For data transactions between facebook page
8. Facebook Webhooks - For continuous updates on pages
9. Messenger API - to receive Messages on profile using Webhooks


Challenges Faced:
1. I was not able to integrate Comments API and webhook because
manage_posts and pages_manage_posts permissions/ feature requires business verification. I could have just shown all the comments on post using API endpoint - me?fields=posts{comments} but that doesnot make sense to display all post and its comments


