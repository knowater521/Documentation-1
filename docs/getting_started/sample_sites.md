# Sample ZeroNet sites

## ZeroHello

The homepage of ZeroNet

 - Lists all added sites: Title, Peer number, Modification date
 - Site actions: Update, Pause, Resume, Delete
 - If new version available update ZeroNet with one click

![ZeroHello](img/zerohello.png)

Address: [1EU1tbG9oC1A8jz2ouVwGZyQ5asrNsE4Vr](http://127.0.0.1:43110/1EU1tbG9oC1A8jz2ouVwGZyQ5asrNsE4Vr)

[Source code](https://github.com/HelloZeroNet/ZeroHello)

---

## ZeroBoard

Simple message board demo for dynamic content distribution

 - Dynamic avatars generated by user auth_key
 - Real time message updates

How does it works?

 - You send your message to site's private key owner bot
 - The bot modify the `message.json` file, signs it using the private key and publish to other peers
 - If the site modification reaches your client the message will appear to your browser

![ZeroBoard](img/zeroboard.png)

Address: [1Gfey7wVXXg1rxk751TBTxLJwhddDNfcdp](http://127.0.0.1:43110/1Gfey7wVXXg1rxk751TBTxLJwhddDNfcdp)

[Source code](https://github.com/HelloZeroNet/ZeroBoard)


---

## ZeroBlog

Self publishing blog demo

 - Inline content editor
 - Markdown syntax
 - Code syntax highlighting
 - Site signing & publishing using only the web interface

How does it works?

 - You can edit the `data.json` file using the web interface
 - By pressing `Sign & Publish new content` button it asks for the site private key (its displayed when you [creating a new site using zeronet.py siteCreate command](getting_started/create_new_site))
 - Your ZeroNet client signs the new, modified files and publish directly to other peers
 - You site will be accessible until at least 1 peer (visitor) computer is active

![ZeroBlog](img/zeroblog.png)

Address: [1BLogC9LN4oPDcruNz3qo1ysa133E9AGg8](http://127.0.0.1:43110/1BLogC9LN4oPDcruNz3qo1ysa133E9AGg8)

[Source code](https://github.com/HelloZeroNet/ZeroBlog)


---

## ZeroTalk

Decentralized, p2p forum demo

 - Topic and message create, modify, delete
 - Topic and message upvoting
 - Only have to contact the site owner once, when requesting modifications permissions to site
 - Commenting and content modifications pushed directly to other peers
 - Only you can sign and modify your own files
 - Real time display of new comments

How does it works?

 - To be able to comment you request an own personal from the site owner
 - After the registration is done you can publish your file's modifications directly to other peers without contacting the site owner again

![ZeroTalk](img/zerotalk.png)

Address: [1TaLk3zM7ZRskJvrh3ZNCDVGXvkJusPKQ](http://127.0.0.1:43110/1TaLk3zM7ZRskJvrh3ZNCDVGXvkJusPKQ)

[Source code](https://github.com/HelloZeroNet/ZeroTalk)