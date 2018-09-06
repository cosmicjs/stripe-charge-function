# Stripe Charge Function
<img src="https://cosmic-s3.imgix.net/124843d0-7c94-11e8-9e7b-6d53b7000e38-stripe.png?w=1000" width="300" />

Cosmic Function that enables you to charge a customer using [Stripe](https://stripe.com).

### Deploying the Function
1. [Login to Cosmic JS](https://cosmicjs.com) and go to Your Bucket > Settings > Functions > Example Functions
2. Install the Stripe Charge Function
3. Add your STRIPE_SECRET_KEY environment variable
4. Deploy the function and get your endpoint

### Testing the Endpoint
1. Download code
```
git clone https://github.com/cosmicjs/stripe-charge-function
```
2. Edit `test-checkout.html` to include the deployed Function endpoint and your Stripe public test key.
3. Open `test-checkout.html` in the browser and attempt a [test charge](https://stripe.com/docs/testing).

### Maintainence
That's it! No managing or maintaining a server, just code and deploy!
