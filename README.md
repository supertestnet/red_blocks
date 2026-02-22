# Red blocks
Track the activation status of BIP110

# What is this?
This is a website for tracking the activation status of BIP110, inspired by https://taproot.watch/

# How can I try it?
Just click here: https://supertestnet.github.io/red_blocks/

# How does it work?
When you load the site, your browser connects to a semi-randomly selected electrum server, from which it downloads the latest bitcoin block headers for the current BIP110 signaling window. Then it checks that data to see how many blocks in this window signaled for BIP110, and displays green and red blocks indicating the BIP's activation progress. If 1109 blocks signal "for" BIP110 during any signaling window, BIP110 will activate a short while after that.
