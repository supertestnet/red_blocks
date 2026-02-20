# Red blocks
Track the activation status of BIP110

# What is this?
This is a website for tracking the activation status of BIP110, inspired by https://taproot.watch/

# How can I try it?
Just click here: https://supertestnet.github.io/red_blocks/

# How does it work?
When you load the site, it downloads the latest bitcoin block headers for the current BIP110 signaling window, and checks how many of those blocks signaled for BIP110. Then it displays green and red blocks indicating the BIP's activation progress. If 1109 blocks signal "for" BIP110 during any signaling window, BIP110 will activate a short while after that.
