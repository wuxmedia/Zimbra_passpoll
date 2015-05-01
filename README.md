# Zimbra_passpoll
Zimbra password expiry email notification script. 
* Requires ionice (or get rid of the reference) and Zimbra, obviously.
 
Will get a list of users, from zmprov which seems to ignore all the zimbra specific ones, that's handy.
mails them at intervals to change the pass. 
at the end it prints a list of accounts with expired passwords, and the last login date. 
Then mails someone about them.

Tells you how long it took, in case it needs to fit into a lot of crons.
redirect output to a file for a log of sorts.
