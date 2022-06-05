Run the followings at https://replit.com/ in "Shell"

ပထမဆုံး သင့် https://console.cloud.google.com/ မှ credentials file ကို ယခု repo ရှိ credentials ထဲသို့ကူးပါ

## 💠ပြုလုပ်ရန်အဆင့်များ
၁
```
pip3 install -r requirements.txt
```
*pip update မလုပ်လဲရ*

၂
```
python3 gen_sa_accounts.py --enable-services saproject  (saproject မှာ သင် ့ project name ထဲ့ပါ)
```
https:// လင့်ခ်ကို browser တွင် accept ပေးပါ။ console တွင်ဝင်ခဲ့သာ gmailဖစ်ရမည်

၃
```
python3 gen_sa_accounts.py --create-sas သင့်project name
```
https:// လင့်ခ်ကို browser တွင် accept ပေးပါ။ console တွင်ဝင်ခဲ့သာ gmailဖစ်ရမည်

၄
```
python3 gen_sa_accounts.py --download-keys သင့်project name
```


**** ရလာတဲ့  account folders ထဲမှာ json ဖိုင်တွေရှိပါတယ်။ အဲ့ဒါကို emails ထုတ်ဖို့က 

```
cd accounts/
```




```
python3 emails.py
```


## ⚠ SA သုံးရင် token.pickle မလိုပါ။ SA မသုံးသူများ token.pickle သတ်သတ်ထုတ်လိုရင် no 1 pip install -r requirements.txt ပီးလျင်

```
python3 generate_drive_token.py
```
ရိုက်ပီး browser တွင် accept နှိပ်ပါ။ token.pickle ဖိုင် တခုထဲ ရပါမယ်။


## 📙 ပြီးလျှင် repo တခုလုံးကို Download ပါ။ 

    ✅မိမိကွန်ပျူတာ သို့မဟုတ် ဖုန်း ထဲရောက်မှ zip ဖြည်ပြီး သိမ်းပါ✅
    
# ဆက်သွယ်ရန်
[Bot Tutorials Channel](https://t.me/BotTutorialsMM)

[ContactMe](https://t.me/Dr007bot)
