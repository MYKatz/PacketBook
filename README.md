# PacketBook is still in early Beta.  Please use at your own risk

# PacketBook

PacketBook is an "internet-less" Stellar wallet, using on text messaging.  This is mostly a proof-of-concept for how Stellar can be used to further financial inclusion in places with high cell phone ownership but low smartphone penetration, such as Kenya.  Inspired by MPesa.


# Commands
Just text any one of these commands to +16197225894

- Register
  - This will generate a new address for you.  In order to use PacketBook, you'll need to activate this account with 0.5XLM.  You must be registered (and activated) to use any of the following commands.
  - You will receive a pin.  Remember this, you will need it to send your Lumens anywhere.
- Balance
  - Returns your balance.  Returns 0 is account is not activated
- Deposit
  - Returns a deposit address.  Send lumens here to fund your account
- Send [phone number] [amount] [PIN]
  - [phone number] must be in area code + raw number format, ex: +19876543211
  - Sends [amount] to the address associated with the given phone number, if said address exists.
- Withdraw [stellar address] [amount] [pin]
  - Sends [amount] to the given stellar address

# Inquiries

Contact: matt@bounti.tech

