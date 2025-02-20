## Companion AI - Chat with the Greats

### Key Features:

- 🎨 Tailwind design & animations  
- 📱 Fully responsive UI  
- 🔐 Clerk authentication  
- ✅ Form validation with react-hook-form  
- ⚠️ Server error handling via react-toast  
- 🖼️ AI-powered image generation (OpenAI)  
- 🎥 AI-powered video generation (Replicate AI)  
- 💬 AI-powered conversation tool (OpenAI)  
- 🎵 AI-powered music generation (Replicate AI)  
- ⏳ Smooth page loading states  
- 💳 Stripe monthly subscription  
- 🆓 Free tier with API limits  
- 🔄 REST API: POST, DELETE, GET in route handlers  
- 🚀 Server-side data fetching without APIs  
- 🔗 Managing parent-child component relations  
- ♻️ Reusable layouts  
- 📂 Optimized folder structure in Next.js 13  


### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/HarshalHarle/companion-ai.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

NEXT_PUBLIC_APP_URL=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

OPENAI_API_KEY=
REPLICATE_API_TOKEN=

PINECONE_API_KEY=
PINECONE_ENVIRONMENT=
PINECONE_INDEX=

UPSTASH_REDIS_REST_URL=
UPSTASH_REDIS_REST_TOKEN=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
```

### Setup Prisma

Add Database

```shell
npx prisma generate
npx prisma db push
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
