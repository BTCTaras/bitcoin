Version 0.1.5 is now available.  It includes the fix for the problem
Nicholas had, checking for disk full and changes to try to improve
things that were confusing.

Special thanks to Nicholas and Dustin for all their help and feedback!

Download link:
http://sourceforge.net/project/showfiles.php?group_id=244765&package_id=298441

Changes:
- disk full warning
- fixed a bug that could occur if dns lookup failed
- prevent entering your own address in the address book,
    which confusingly changed the label for your own address
- moved change address button to menu under options
- tweaks to make it get connected faster
- close sockets on exit
- created minimum fee for transactions less than 1 cent
- hid the transaction-type selection box that only had one choice
- cleaned up ParseMoney a little
- slightly cleaner reformatting of message text
- changed the font in transaction details dialog
- added some explanation text to transaction details for generated coins
- reworded the description for transactions received with bitcoin address
