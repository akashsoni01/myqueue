# My Queue App

### My Queue
Listen to your content!  I'm constantly bookmarking articles and reading them on the train home from work, with My Queue, I can now save them to My Queue and listen to them playlist style on the way home.

### Svelte Hackathon
Hey friends.  This is the main app for [My Queue](https://www.myqueue.so/), it's written with the big help of SvelteKit.  I was just learning Svelte when I started this project, and I think I've made plenty of mistakes.  If anyone has any pointers on how to handle my stores or auth gating, let me know!  I really ended up enjoying Svelte, so thanks for putting together this Hackathon and giving me some inspiration.

## App Features:
   - 📰 Scrape any article!  Our scrapper is a work in progress, but we're quite happy with the results we've been able to achieve in a limited time.  Give it a try.  Let us know if it doesn't perform to expectation.
   - 🎧 Listen to any article.  Currently we're using Google Text-To-Speech to translate your articles into any language supported by google.
   - 🐱‍👓 Read any article.  We've started work on our custom reader, we're continuing to improve looks and functionality.
   - 🔒 Google Auth, and Email password auth.  Still have to set up remaining user features.
   
 
 
 ### Architecture
A lot of moving parts are involved in this project.  We've got
 - Svelte App
    - Vercel
    - Sveltekit
    - TypeScript
    - Vite
    - Tailwind
    - Supabase JS library
    - date-fns
    - felte
  - Supabase
    - Auth
    - Postgres
    - Storage
  - Marketing site
    - Webflow
  - Sanitizing and parsing microservice
    - railway
    - node 
    - express
  - Parsing microservice
    - railway
    - python
    - fastapi
  - Chrome extension
    - react
    - tailwind
