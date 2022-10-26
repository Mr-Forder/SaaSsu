![sassy](https://user-images.githubusercontent.com/66869833/197805521-c686a93a-841f-4e8a-85e7-226f62a13a80.jpg)


# SaaSsy is a Patreon-style subscription based SaaS template work in progress featuring Supabase auth and db and full Stripe integration. 



SaaSsy will allow users to create a subscription based system (similar to that used on Patreon) that allows gated content via a Supabase backend,
with customisable payment options handled via the Stripe API.

You'll need the following environment variables:

```
NEXT_PUBLIC_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_KEY
NEXT_PUBLIC_STRIPE_KEY
STRIPE_SECRET_KEY
API_ROUTE_SECRET
STRIPE_SIGNING_SECRET
SUPABASE_SERVICE_KEY
```


## To get Started

```
npm install

npm run dev
```
