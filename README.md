# genshin-pyMone

## About
**Create your own statistics Card based on the HoYoLab Battle Chronicles**  
pyMone using the genshin.py library for collect player data, and creates an .png file that contains all the collected data  

Nickname, AR, UID enter manualy by user

## Used libraries
+ genshin.py
+ asyncio
+ termcolor
+ PIL
+ os
## Code structure
+ Collecting LTOKEN, LTUID, UID, AR, Nickname
+ Collecting User Statistic from Battle Chronicles by genshin.py
+ Add text to template and create a card by PIL
## How to get ltuid and ltoken ?
- Go to HoYoLab and log in
- Open Developers tools (F12)
- Go to [Application] ---> [Cookies] and find *ltuid* and *ltoken*
- Copy     
***Do not show this data to anyone. The pyMone doesnt save them***

Full information how it is works: https://thesadru.github.io/genshin.py/authentication/  
genshin.py GitHub: https://github.com/thesadru/genshin.py  

## Example card


![player_card](https://user-images.githubusercontent.com/108213301/176425247-7198de94-e08d-48ad-832c-7dc452933383.png)  



