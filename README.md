Hello, and welcome to Binned!
This is a personal finance app that I developed for myself.
It is in alpha at the moment and will be updated very frequently with new features

To get set up, open the app using the link:
https://coloughl.github.io/Binned/

Next, click on the "Settings" tab and find the Supabase Cloud Sync Section. Enter the following information into the provided fields to connect to the Binned Supabase:

Supabase project URL:
https://xkcxikafpnwrtrwwmqbq.supabase.co

Supabase Publishable / Anon Key:
sb_publishable__2wZ2u4EjpJ0R5dtvqvRhA_T6rTDZxy

Personal Ledger Passphrase
For the Personal Ledger Passphrase, come up with a unique (but secret) passphrase. This will become your unique account identifier and how you will be able to sync to your computer and phone.

Click "Save & Sync"

If you would like to link your bank account to receive a live feed of transaction history and start to *bin*, then follow the following instructions

1. Create an account on SimpleFIN:
   https://beta-bridge.simplefin.org/

   It costs $1.50/month for this service and is used by many other people interested in personal financing apps.

2. Once your account is created, find the "Financial Institutions" section on the Home page. Underneath this, it should say "New Connection" in a black button. Click that and find your financial institution and log into your account.

3. Once your account is linked, scroll down to the "Apps" section and select the "New App Connection" button.
   Under Name, enter "Binned" (or whatever you would like to call it). This will give you a one-time-use "Claim One-Time Setup Token". Copy that token number.

4. Navigate back to Binned and paste the token into the field labeled "Paste SimpleFIN Setup Token..." which is found under the SimpleFIN Bank Feed Section.

5. Click the Claim button. This should accept the token and generate a SimpleFIN Access URL, which you should copy and paste into a document that you can access in case you need it again (you will need it if you want to sync a second device).

6. Finally, click "Sync Bank Now" and watch the transactions roll in!

For security concerns: 
**Binned** is a client-side personal ledger designed with a "bring-your-own-backend" architecture—meaning there is no central Binned server collecting, selling, or viewing your financial data. By default, all transactions, budgets, and credentials stay strictly inside your browser's local storage. If you choose to enable cross-device sync or bank feeds, your data is stored exclusively in your own private Supabase database and fetched directly through your own read-only SimpleFIN Bridge connection. **Important Security Disclaimer:** Because Binned runs entirely in the browser without a traditional login server, your Supabase credentials, SimpleFIN Access URL, and Ledger Passphrase are stored locally on your device. You should only use this app on trusted personal devices, choose a strong, unique Ledger Passphrase, and regularly export local JSON backups of your ledger. This software is provided as-is for personal budgeting purposes and is not a substitute for professional financial advice.

This should be all the setup necessary to start binning! If there are issues, please contact connoroloughlin@rocketmail.com for troubleshooting



