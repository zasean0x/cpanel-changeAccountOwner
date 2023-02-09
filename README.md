# You must be root for this to work

# cpanel-changeAccountOwner

Slapped together - Nothing I am proud of lives in this script

# What it does

Uses the cpanel whm api to gather all accounts and change the ownership to the new owner specified in the script.

It has a rollback feature which will only survive one run - If you run the account owner change again, the rollback will contain the previous values (root)

# How to use

Edit the script and put the desired new owner where the comment tells you to.

Add exec perms

Run it


If you need to rollback the previous changes, run the script with rollback

./changeAccountOwner.sh rollback