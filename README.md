# Musig playground
A playground for creating and redeeming musig outputs

https://supertestnet.github.io/musig-playground/

Right now this app is extremely basic. It just does a single musig transaction in your browser console and leaves the actual screen blank. Open up your browser console (ctrl+shift+i, then click console) to see the magic. Eventually I want to make options so you can construct a custom musig spend on testnet, but right now this repo basically serves as a proof for myself that you can really do musig in the browser.

BTW this is all based on Guggero's excellent javascript schnorr implementation: https://github.com/guggero/bip-schnorr
