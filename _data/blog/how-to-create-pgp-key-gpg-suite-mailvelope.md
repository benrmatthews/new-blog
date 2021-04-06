---
title: 'How to create and use a PGP key with GPG Suite and Mailvelope'
date: '2017-10-12T17:32:59+00:00'
status: publish
permalink: /how-to-create-pgp-key-gpg-suite-mailvelope
author: 'Ben Matthews'
excerpt: 'Setting up and using a PGP key is not straightforward, but tools like GPG Suite and Mailvelope make it easier. Here''s how to create and use a PGP key with GPG Suite and Mailvelope.'
type: post
id: 1789
thumbnail: ../uploads/2017/10/How-to-create-and-use-a-PGP-key-wth-GPG-Suite-and-Mailvelope-150x150.jpg
category:
    - 'Tech For Good'
tag: []
post_format: []
rank_math_robots:
    - 'a:1:{i:0;s:0:"";}'
keyword_cache:
    - 'a:16:{s:20:"freelance statistics";a:8:{s:3:"url";s:21:"/freelance-statistics";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:19:"freelance portfolio";a:8:{s:3:"url";s:30:"/courses/freelance-portfolios/";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:19:"accounting software";a:8:{s:3:"url";s:33:"/best-online-accounting-software/";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:19:"freelance community";a:8:{s:3:"url";s:20:"/freelance-community";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:19:"freelance questions";a:8:{s:3:"url";s:20:"/freelance-community";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:18:"freelance expenses";a:8:{s:3:"url";s:19:"/freelance-expenses";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:18:"freelance training";a:8:{s:3:"url";s:8:"/courses";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:15:"freelance tools";a:8:{s:3:"url";s:21:"/best-freelance-tools";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:15:"freelance rates";a:8:{s:3:"url";s:16:"/freelance-rates";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:14:"freelance work";a:8:{s:3:"url";s:15:"/freelance-work";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:14:"freelance jobs";a:8:{s:3:"url";s:15:"/freelance-jobs";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:13:"balance sheet";a:8:{s:3:"url";s:46:"https://freetrain.co/balance-sheet-definition/";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:7:"courses";a:8:{s:3:"url";s:8:"/courses";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:5:"rates";a:8:{s:3:"url";s:16:"/freelance-rates";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:4:"ir35";a:8:{s:3:"url";s:5:"/ir35";s:5:"times";s:0:"";s:7:"between";s:0:"";s:6:"before";s:0:"";s:5:"after";s:0:"";s:4:"case";N;s:8:"nofollow";N;s:9:"newwindow";N;}s:13:"keywords_time";i:1565619634;}'
rank_math_internal_links_processed:
    - '1'
eael_transient_elements:
    - 'a:0:{}'
---
Setting up and using a PGP key is not straightforward, but tools like GPG Suite and Mailvelope make it easier. Here’s how to create and use a PGP key with GPG Suite and Mailvelope.

**1. Download GPG Suite**
-------------------------

The first step is to download and run [GPG Suite](https://gpgtools.org/#gpgsuite). When that is done, it’s time to setup your GPG key.

If you already have a GPG key, [add your address to an existing GPG key,](https://gpgtools.tenderapp.com/kb/how-to/first-steps-where-do-i-start-where-do-i-begin-setup-gpgtools-create-a-new-key-your-first-encrypted-mail#adduid) because in which case you don’t need to create any new key.

If you do not have a GPG key yet, follow up with the next section.

**2. Generate your own key through PGP Suite**
----------------------------------------------

GPG Keychain is the application you will use to manage your keys. It will let you create new keys, edit existing ones and search for your friend’s keys.

The first thing you’ll see in GPG Keychain is a wizard which will guide you through creating your first key.

![How to create and use a PGP key wth GPG Suite and Mailvelope](../uploads/2017/10/How-to-create-a-PGP-key-wth-GPG-Suite-and-Mailvelope.jpg "How to create and use a PGP key wth GPG Suite and Mailvelope")

### **2a. Email Address**

GPG Keychain fills the data from your OS X address book. But the fields are editable and you can change them at your will. Enter the email address you normally use when sending mail.

### **2b. Upload key after generation**

If you enable this checkbox, your public key will be uploaded to a key server once key creation is done. Generally this is a good thing, since it will make it much easier for others to start sending you encrypted messages by simply importing your key from a key server.

### **2c. Password**

Enter your password. As with every other password you use, it should be very strong and it’s best to use a very long password, a sentence you can remember, comprised of symbols and numbers.

Important: Should you forget your password, there’s no way to recover it. Make sure you will remember it or store it in a safe place (no, a text note on your desk is not a safe place).

### **2d. Hit “Generate key”**

After a short while, you’ll see a new entry in GPG Keychain with your email address showing sec/pub (secret/public) in the type column.

Every time you create a new key, a new key pair is created. It will consist of a secret key and a public key. The public key is to be shared with others, so they can send you encrypted messages.

![How to create and use a PGP key wth GPG Suite and Mailvelope](../uploads/2017/10/How-to-create-and-use-a-PGP-key-wth-GPG-Suite-and-Mailvelope.jpg)

**3. Start using your key**
---------------------------

Once done, you can then send your key and then add other peoples keys to your key database.

Depending on the app, you may have to choose who you are encrypting it for separately from the ‘To:’ recipients in your message.

You can share your key either by .asc file, copying and pasting the key text, or by linking to a server it’s uploaded to.

It’s also a good practice to upload your key to the MIT server (this is apparently the largest key database, so if someone searches for you here, they’ll be able to import your key). Once uploaded, you can link the web address of your key for sharing. Copy and paste your key’s text here: <https://pgp.mit.edu/>

**4. Setting up Mailvelope for in-browser encryption**
------------------------------------------------------

You might need to use Mailvelope with your browser and if you use Gmail, but much of the same applies for whichever you use. Mailvelope can just have extra steps for composing and encrypting files whereas the mail clients can do it automatically.

1. Add [Mailvelope](https://www.mailvelope.com/en/) to Firefox or Chrome to integrate pgp with your gmail: <https://www.mailvelope.com/en/>
2. In the Setup tab, generate a key for your email address.
3. In Display Keys, select your key.
4. In the Export tab, you can save your key as a file to send to someone  
  or share by copying/pasting the key text.
5. Import other people’s keys in Mailvelope. You can upload key files or search by their email addresses.

After you import other people’s keys, you can send emails which can only be opened by the intended recipients

**5. Writing encrypted emails with PGP**
----------------------------------------

Click on the new icon that appears when you open a new message. Write within that box. Select the recipients’ keys.

If you start writing a message in the regular Gmail body, the icon may disappear. You can re-enable by clicking on the browser icon then +Add current tab.

**6. Encrypting files with PGP**
--------------------------------

Some email clients like Thunderbird have integrations like Enigmail that automatically encrypt files. File encryption has to be done separately with Mailvelope.

Click on the Mailvelope browser icon then the File Encryption tab at the top. Select the recipients and encrypt! Attach that file to your message.

**Hopefully by following these instructions, you’ll have managed to create and start using a PGP key with GPG Suite and Mailvelope. Could this guide be improved? Let us know in the comments.**