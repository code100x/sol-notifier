# sol-notifier
A simple frontend that let's users connect their wallets to notification sources like TG/WA/Native notifications on browser

## Stack
Create a monorepo which has 

1. Core web2 service
Next.js
Typescript
Authentication via gmail/wallet is required. See next-auth with mm over here - https://github.com/DakaiGroup/nextjs-nextauth-metamask

2. Web3 indexer
Needs to index all the wallets and find the 
1. Tokens the user has and it's amount
2. NFTs the user has and it's amount (maybe only blue chips from a list)

3. Price indexer
1. Needs to poll coingecko and get back prices for tokens
2. Needs to poll ME/Tensor for floor price of NFT (floor - royalty is the final proce)

## What needs to be done
A simple UI where a user can 
1. Add their `public key + blockchain` on the left
2. Add notifiers on the right (connect a discord channel/slack/whatsapp/push notifications in the browser)
3. A portfolio header that shows the user their net worth


