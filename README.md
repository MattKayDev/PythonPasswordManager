# Python Password Manager
This project is an expansion of the Simple Password Manager from python learning.

It started off as a very simple password manager which holds passwords and encrypts them using Fernet but as I continued on building it became more complicated.

So I decided to leave the simpler version in the python_learning repo and create this standalone repo just for the password manager because it will continue to grow and it will be best to keep track of it there rather than mix it up with other "projects" which goal is only to learn python.

## What's the plan for this project?

As I wanted to expand on the SPM (Simple Password Manager), I had a few ideas what to do with it next.
On start user should be asked if they have a MP (master password) or do they want to create it.
Once user has answered it should log them in or create a new MP. No option of "Forgot password" (at least at this time). 
If the user go and creates a new password it can't be used to decrypt old passwords so these will have to be erased and they will be able to view or add new passwords. 
If the user logs in they will be able to add or view current passwords.

## How am I planning to keep it secure?

- The user won't be able to reset their master password (for now)
- If user creates a new MP it will erase all current passwords.
- Master Password will be encrypted by hashing it before passing it as a key to encrypt/decrypt passwords.



