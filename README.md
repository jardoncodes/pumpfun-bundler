## License Key is I5A-8R6TL0
## License Key is I5A-8R6TL0
## License Key is I5A-8R6TL0



## Replace the values in user.json with your values

LICENSE_KEY = Your Infinity Bundler  License Key

SIGNER_PRIVATE_KEY = PRIVATE KEY OF DEV WALLET 
(BASE58 FORMAT -> Phantom Export Format)

DEV_ADDRESS = WALLET ADDRESS OF DEV WALLET 
(PUBLIC KEY) 

FUNDER_PRIVATE_KEY = PRIVATE KEY OF FUNDER WALLET 
(WALLET THAT WILL FUND THE SUB WALLETS) 
(BASE58 FORMAT -> Phantom Export Format)

SELLER_PRIVATE_KEY = PRIVATE KEY OF SELLER WALLET 
(THIS IS FOR TRANSFER SELL MODE ONLY, KEEP 0.1 SOL IN THIS WALET TO PAY ANY FEE) 
(BASE58 FORMAT -> Phantom Export Format)

BLOCKENGINEURL = JITO BLOCKENGINE URL 
(see list below) 

JITO_TIP = JITO TIP AMOUNT 
(SOL) 

SELL_TIP = SELL TIP AMOUNT 
(SOL) 

DEVBUY = AMOUNT OF SOL TO BUY ON DEV WALLET

LUT_Address = LOOKUP TABLE ADDRESS 
(DO NOT EDIT THIS, THE BOT WILL CREATE & UPDATE THIS)

COMPUTE_LIMIT_PRICE = COMPUTE LIMIT PRICE 
(LAMPORTS) 
(LEAVE DEFAULT UNLESS YOU KNOW WHAT YOU'RE DOING)

COMPUTE_UNIT = COMPUTE UNIT PRICE
(LAMPORTS) 
(LEAVE DEFAULT UNLESS YOU KNOW WHAT YOU'RE DOING)

CUSTOM_OCP = UNLESS YOU PURCHASED A PRIVATE OCP FROM US, LEAVE THIS VALUE EMPTY.

CAP_SOLVER_API_KEY = https://www.capsolver.com/

BLOCKCHYPER_API_KEY = https://www.blockcypher.com/apis.html


# Hosting:

1. Sign up and create a Python Repl on Replit.com

2. Install libraries in the terminal/shell:

Bash
```
pip install colorama cryptography PyNaCl base58 
```

3. Upload all the files in the replit repository.

4. Run the script:

Click the "Run" button.

Or run in the terminal: python main.py


# Metadata.json

(METADATA SETUP)

name: Token Name

symbol: Ticker (max 10 char)

description: Token Description (Max 30 char)

image: LEAVE BLANK

showName: DON'T EDIT

twitter: Twitter link

telegram: Telegram channel link

website: website URL

NOTES:

ANY / ALL SOCIALS CAN BE LEFT BLANK IF YOU PREFER NOT TO USE THEM.

MAKE SURE TO LEAVE IMAGE VALUE BLANK

YOU MUST PUT THE TOKEN IMAGE IN THE /img DIRECTORY

IF YOU WANT TO USE A VIDEO, PUT IT INSIDE THE /IMG FOLDER ALONG WITH THE DESIRED THUMBNAIL IMAGE

TICKER / SYMBOL MAX 10 CHARACTERS

ONE IMAGE IN DIRECTORY ONLY (FILE NAME + EXTENTION DON'T MATTER)
