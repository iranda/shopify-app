## Run application

1. Start an [ngrok](https://ngrok.com/download) tunnel on port 3000

        ./ngrok http 3000

2. Use `https` address to setup App URL and Whitelisted redirection URL(s) in shopify store

3. Put API key (`SHOPIFY_API_KEY`), API secret key (`SHOPIFY_API_SECRET`), store url (`SHOPIFY_STORE_URL`) in .env

4. Run app `{your ngrok forwarding address}/shopify?shop=your-development-shop.myshopify.com`
