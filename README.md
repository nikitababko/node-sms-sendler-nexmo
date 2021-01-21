# Node SMS Text App

Node.js app that uses [Nexmo](https://dashboard.nexmo.com/sign-in) to send SMS text messages

## Install

`npm install` или `yarn install`

## Receiving SMS using Nexmo

1. Registration to [Nexmo](https://dashboard.nexmo.com/)
2. Enter to your account on this service.
3. Choise SMS -> Getting started.
4. Get your information about your apiKey and apiSecret.
   ![](https://image.prntscr.com/image/ZQYiv9OFTt_EWGossNIi0w.png)
5. Create .env file and replace values with yours:

```
PORT=3000
NEXMO_API_KEY=********
NEXMO_API_SECRET=****************
```

6. Specify in the `NEXMO_API_KEY` and `NEXMO_API_SECRET` the data that gave you Nexmo.
7. Run the command `npm start` or `yarn start`.

## Built With

-   NodeJs / Express
-   EJS
-   Nexmo
-   Socket.io
