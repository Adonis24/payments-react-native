# Hello!

This is the sample code for Stripe's React Native module. This is a companion to [this Glitch server](https://glitch.com/edit/#!/expo-stripe-server-example), 
which you can connect to by installing [Expo Go](expo.io/expo-go) on your device and running this example!

## How do I use this?

You can play around with this example and see all the UI, but if you'd like to connect it to your own Stripe account, you'll need to replace the following values in the Glitch project's `server.js`:
- `stripePublishableKey`
- `stripeSecretKey`
- `stripeWebhookSecret` 

Or, you can replace the environment variables those values currently rely on:
- `STRIPE_PUBLISHABLE_KEY` 
- `STRIPE_SECRET_KEY` 
- `STRIPE_WEBHOOK_SECRET` 

And you'll also need to replace the server URL in the Snack, in the `Config.ts` file.