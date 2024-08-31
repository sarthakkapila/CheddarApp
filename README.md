# Cheddar 🧀



🚀 Dive into the ultimate Solana chat room! Connect with fellow degens, share the latest alpha, and plan your next big move. Whether you’re ready to ape into the hottest tokens or chill with the SOL squad, our platform is where the magic happens. 🔗 Sync your Phantom wallet, join the conversation, and be part of a global network where every chat could lead to your next moonshot. 🌟 Your crypto adventure starts here – where on-chain innovation meets community hustle. Let’s go!
## Project Components

### 1. Churro - Web Application (Next.js)
- *Live Link:* [https://cheddarchat.vercel.app/]
- *Repository:* [https://github.com/Cheddar-org/CheddarApp/tree/main/churro]
- *Key Features:*
    - Landing page
    - FAQs about the product 
    - Links to the beta
    - Leaderboard page for airdrops

### 2. Dumpling - Mobile Application (React Native)
NOTE : Dumpling is only working on IOS as of now

`Transactions are not yet supported on the Link though they're working on the local build as shown in the 
- *Live Link:* [https://expo.dev/preview/update?message=fix&updateRuntimeVersion=1.0.0&createdAt=2024-08-31T04%3A07%3A54.668Z&slug=exp&projectId=76caef8e-27a8-46a4-a727-e8752a403b4d&group=1954efcb-452c-488b-be3a-c7951e6e40a8]
- *Repository:* [https://github.com/Cheddar-org/CheddarApp/tree/main/dumpling]
- *Key Features:*
  - iOS and Android compatibility
  - Mobile-optimized interface to buy meme coins
  - Live chat
  - Secure mobile wallet integration
  - Optimised for Solana Actions

### 3. Baklava - Global chat server deployed on cloudflare workers ( Gatekeeping the code )
- *Key Features:*
  - Real-time messaging system backend
  - Chatroom management
  - Message history and retrieval
  - User presence tracking
  - Storage of users and messages

### 4. Sushi - Blinks Server for 
- *Key Features:*
  - High-frequency blink processing
  - Integration with chat and trading systems
  - Performance monitoring and optimization
  - Optimised coin swaps via various exchanges

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in the cheddarApp/dumpling

EXPO_PUBLIC_SUPABASE_URL

EXPO_PUBLIC_SUPABASE_ANON_KEY


# DEMO VIDEO
[**DEMO VIDEO**](https://youtu.be/oKR2wzRZCkE)




## Installation

Install my-project with npm

```bash
    git clone https://github.com/Cheddar-org/CheddarApp
    cd cheddarApp
```

Navigate to the Dumpling dir
```bash
    cd Dumpling
```
Install necessary dependencies
```bash
    bun install
    or
    npm install
```

Create a .env file in the root of the project and 

```bash
   bun start
   or
   npm start
```

- Expo opens start in development mode by default, press 'S' in the terminal to switch to Expo Go

- Install Expo Go on your device ( the app only works on IOS as of now ) 

- Scan the QR code and select Expo Go in the options

- Wait for it to finish building

- Start testing


contact: 
- sarthakkapila1@gmail.com
