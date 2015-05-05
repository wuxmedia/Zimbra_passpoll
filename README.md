# Zimbra_passpoll
Zimbra password expiry email notification script. 
* Requires ionice (or get rid of the reference) and Zimbra, obviously.
 
Will get a list of users, from zmprov, which seems to ignore all the weird zimbra specific ones, so that's handy.

Then mails them personally at user defined intervals to change the pass. 
Once the main script has ran, it prints a list of accounts with expired passwords, and the last login date. 
Then mails someone about them.

Tells you how long it took, in case it needs to fit into a lot of cronjobs

in the cron jobs - redirect all the output to a file for a log of sorts.
