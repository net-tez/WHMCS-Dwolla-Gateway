#WHMCS Dwolla Gateway
Dwolla is the next coolest and hottest payment method on the market. Cheaper and easier than the alternate gorilla in the room, what's not to love?

We were suprised to find out that no good, open source gateway existed in WHMCS yet for Dwolla. So here's our take on it, a module developed for our own systems. Feel free to use. It's Creative Commons. Share and share alike, just please keep this readme (or a mention of us) with it at all times. That's not too much to ask for saving you thousands of dollars in fees, is it?

##Installation
1. Upload the gateways/dwolla.php file to whmcs/modules/gateways/
2. Upload the callback/dwolla.php file in the callback folder to modules/gateways/callback/
3. Log into the WHMCS admin area, and activate the Dwolla gateway
4. Set the Callback URL in the Dwolla web interface to
  https://example.com/whmcs/modules/gateways/callback/dwolla.php
5. Profit?

##Notice and Stuff
This code was written by [Connor Peet](http://connorpeet.com) and is copyright 2013 by Ferrous Networks Ltd. It is distributed under the terms found in the LICENSE file, the CC-BY-SA 3.0 license ([summary here](http://creativecommons.org/licenses/by-sa/3.0/deed.en_US)).