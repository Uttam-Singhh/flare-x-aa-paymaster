# AA with Paymaster

Checkout transaction logs:
![img 2024-03-27 at 6 17 34 AM](https://github.com/Uttam-Singhh/flare-x-aa-paymaster/assets/63050765/ad2ecd9b-43ff-4b66-b971-f1a99fa4c2b1)

these lines of code are what enable a transaction to be sponsored

![photo_2024-03-27 06 54 28](https://github.com/Uttam-Singhh/flare-x-aa-paymaster/assets/63050765/591bef09-573d-40e1-9dfe-ea995f84ebfc)

**"arka_public_key"** is a testnet public key

There are two modes to choose from while using paymaster ([Check docs for more](https://etherspot.fyi/arka/intro))

1.) sponsor - used in this example (This works by having Arka pay for the transaction fee, you can add more options to it like validUntil / validAfter). (Typically a project will get their own paymaster api key, deposit into the address)


2.) erc20 - This works by having the gas fee paid with whatever token is specified.

To check run:

`npm i`

And then 

`npm start`

