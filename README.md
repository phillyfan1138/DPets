Prereq: download and install geth and add it to your path.  Add at least one account.  This process is described here:
https://github.com/ethereum/go-ethereum/wiki/geth.  Also requires nodejs https://nodejs.org/en/.  

In cmd/terminal, go to the directory containt index.js.  Type "npm install".  Wait for the downloads.  Then type "npm run dev".  Once green letters show up, type cntrl-d to shut down the terminal.  Then type "node index.js".  It will prompt for the password used in creating the account created for ethereum above.  Then it will start up the Geth server.  Once done, the browser for the dapp will open.  

To actually submit records, you have to pay ether (currently a ridiculous 1 ether.  This runs on morden testnet, so its not real).  To simply test whether this works, try "123" in "Pet ID" in the second or third forms.  A result saying "hello world" should display.  This does not require any ether.



