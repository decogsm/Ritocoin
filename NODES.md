# Public Ritocoin node

The old DNS seeds (s1, s2, s3.ritocoin.org) no longer work and aikapool.com went down, 
so wallets cannot find peers and cannot sync.

I am running a public, fully synced node and I have kept mining the chain since then.

To connect, add this line to rito.conf and restart your wallet/node:

    addnode=tamaseduard.com:7342

Check with "getpeerinfo" and "getblockcount".

More info and instructions: https://ricoin.tamaseduard.com
