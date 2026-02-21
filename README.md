# Accept a payment #

By default, Stripe enables cards and other common payment methods. You can turn individual payment methods on or off in the ***Stripe Dashboard***. In Checkout, Stripe evaluates the currency and any restrictions, then dynamically presents the supported payment methods to the customer

**Testing**

1. Click your checkout button.
2. Fill out the payment details with the test card information:
   
    a. Enter 4242 4242 4242 4242 as the card number.

    b. Enter any future date for card expiry.

    c. Enter any 3-digit number for CVC.

    d. Enter any billing postal code.

3.  Click Pay.
4.  You’re redirected to your new success page.
   
   
   

** Image **

[click to open](https://www.google.com/search?q=gmail&rlz=1C1RXQR_enIN1060IN1060&oq=&gs_lcrp=EgZjaHJvbWUqCQgAEEUYOxjCAzIJCAAQRRg7GMIDMgkIARBFGDsYwgMyCQgCEEUYOxjCAzIJCAMQRRg7GMIDMgkIBBBFGDsYwgMyCQgFEEUYOxjCAzIJCAYQRRg7GMIDMgkIBxBFGDsYwgPSAQsyMDE3MTQyajBqN6gCCLACAfEFszTfF3wL3Z4&sourceid=chrome&ie=UTF-8)

![]()



    ** code **

```

{
    "status":"OK",
    "data":
        {
            "message": "Welcome, world!"
        }
}

```
















































