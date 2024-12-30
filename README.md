### Set-Up on your system

1. Clone the repository to your local machine:

```terminal
git clone https://gitlab.com/malik_benji_marv/music-programmingfinal
```
2. Change into the project directory:

```terminal
cd Full-Stack-Spotify-Clone-Next-13.4-React-Stripe-Supabase-Tailwind
```
3. Install the project dependencies:

```terminal
npm install
```

### Configuration

1. Create a `.env.local` file in the project root and configure the following environment variables:

```js
 Create keys to access our supabase database.
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

 Create keys to access our Stripe online product using Stripes CLI.
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Usage

1. Start the development server:

```shell
npm run dev
```
2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the application.

