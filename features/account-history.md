# Account History

SAGE allows you to save previously generated accounts in your browser's _local
storage_.

You can find it here:

[!ref Account history](https://sage.party/dash#accounts)

Account history is **disabled by default**. Malware that steals all your browser
data is quite common nowadays, so we do not feel comfortable to store your
account data by default.

Fear not, we have a solution for that: **Encryption**. You can encrypt your
Account history with a password!

Writing to your history does not need a password, but reading does (so you won't
need to enter your password everytime you create an account).

!!!danger Do NOT clear "Cookies and other site data"!

The _local storage_ where accounts are stored counts as **other site data**!
Clearing your Cookies / Browsing data will permanently delete all your accounts!

You have been warned.

!!!

## Features

- Encryption (AES-GCM/128, RSA-OAEP/4096, SHA2/256)
- Full Account data
  - Steam: Username, Password
  - Email: Address, Password
  - Steam ID
  - Original steam login cookie (for "Quick login", only works for a short time)
  - Creation time
- Export
  - username:passwords
  - raw JSON
