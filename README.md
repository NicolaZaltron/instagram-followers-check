# instagram-followers-check

##Get started
Download your own list of connections directly from instagram by selecting the following options:
1. Access here: https://accountscenter.instagram.com/info_and_permissions/dyi/
2. Download or transfer information
3. Instagram
4. Either All or Some of your information, depending if you already ran the script recently
5. Followers and Following
6. Download to device
7. Select data range, **JSON format**
8. Create files

After some time, you'll get a mail notifying that the download is available. Download the file and extract the files *followers_1.json* and *following.json* in the same folder of the notebook instagram-followers-check.ipynb

Update *whitelist.txt* by adding links to accounts that you want to whitelist. For simplicity you can do this after the first run and use part of the output as whitelist directly. 

Run all cells and get as output a list of clickable links, containing all followed accounts that are not following you (except whiteliested ones).
