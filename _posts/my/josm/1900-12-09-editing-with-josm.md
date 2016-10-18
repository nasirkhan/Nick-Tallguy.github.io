---
layout: doc
title: မြေပြင်အချက်အလက်များတွင် ပြင်ဆင်တည်းဖြတ်ခြင်း
permalink: /my/josm/editing-with-josm/
lang: my
category: josm
---

မြေပြင်အချက်အလက်များတွင်ပြင်ဆင်တည်းဖြတ်ခြင်း
==================

> ဤလမ်းညွှန်ချက်ကို [josm_editing-with-josm_my.odt](/files/josm_editing-with-josm_my.odt) (သို့မဟုတ်) [josm_editing-with-josm_my.pdf](/files/josm_editing-with-josm_my.pdf) တွင် download ပြုလုပ်၍ရယူနိုင်ပါသည်။  
> Reviewed 2015-07-13  

OpenStreetMap တွင်မြေပုံရေးဆွဲရန်အတွက် လိုအပ်သည်များကို လေ့လာခဲ့ပြီးဖြစ်သည်။ 
[လက်ကိုင်ဖုန်း(သို့) GPS (သို့) စာရွက်ဖြင့် မြေပုံဆွဲခြင်း] (/my/mobile-mapping/) သင်ခန်းစာတွင် ယင်းကိရိယာများဖြင့် မြေပြင်တိုင်းတာစစ်ဆေးပုံအကြောင်းကို သိရှိပြီးဖြစ်၏။   

ယခုသင်ခန်းစာ၌ JOSM ဆော့လ်ဖ်ဝဲလ်ရှိ သဘောတရားအသစ်များကို 
ဆက်လက်လေ့လာမည်ဖြစ်သည်။

JOSM ဆော့လ်ဖ်ဝဲလ်ရှိ အလွှာများ
-----------
JOSM ဆော့လ်ဖ်ဝဲလ်ဖြင့်မြေပုံရေးဆွဲရာတွင် အမျိုးအစားမတူသောအရာများကို ပေါင်းထည့်နိုင်ကြောင်း သိရှိပြီးဖြစ်မည်။ 
ဆော့လ်ဖ်ဝဲလ်၏ မြေပုံမျက်နှာပြင်တွင် OSM ဒေတာများ၊ Bing ဂြိုဟ်တုပုံရိပ်၊
GPS လမ်းကြောင်းများနှင့် ကွင်းဆင်းမြေပုံ
စသည်တို့ကို မြင်တွေ့အသုံးပြုနိုင်သည်။

အသစ်ပေါင်းထည့်သောအရာများကို ဆော့လ်ဖ်ဝဲလ်မျက်နှာပြင်၏ ညာဘက်ရှိ
Layers ဟုခေါ်သော အကွက်တွင် ပေါင်းထည့်ဖော်ပြမည်ဖြစ်သည်။ သင်ထည့်သွင်းလိုက်သည့်အမျိုးအစားပေါ်မူတည်၍ 
Layers အကွက်တွင် အောက်ပါအတိုင်းမြင်တွေ့နိုင်သည်။

![Layers panel][]

မြေပုံမျက်နှာပြင်တွင် သင်ဖွင့်လိုက်သောအမျိုးအစားပေါ်မူတည်လျက် 
မတူညီသောအချက်အလက်အရင်းအမြစ်စာရင်းကို မြင်တွေ့ရမည်ဖြစ်သည်။ ဤနမူနာပုံတွင် 
သင်ပြင်ဆင်တည်းဖြတ်နေသော မြေပုံ OpenStreetMap ဒေတာသည် “Data Layer 1” ဖြစ်ပြီး 
JOSM ဆော့လ်ဖ်ဝဲလ်အတွင်းသို့ထည့်သွင်းလိုက်သော ကွင်းဆင်းမြေပုံကို "Field Papers" အမည်ဖြင့်အလွှာတစ်ခုတည်ဆောက်ဖော်ပြထားသည်။ 

Bing ဂြိုဟ်တုမှရိုက်ယူထားသောပုံရိပ်ကိုထည့်သွင်းပါက Layers အကွက်တွင် "Bing Sat" အမည်ဖြင့်အလွှာတစ်ခုမြင်တွေ့ရမည်ဖြစ်၏။

အလွှာများသည် မကြာခဏ နားလည်ရခက်စေနိုင်၏။ ဖောက်မြင်လွယ်သောစက္ကူပါးများ  
တစ်ခုပေါ်တစ်ခုစီထပ်ထားသည်ဟု မှန်းဆကြည့်နိုင်သည်။ ယင်းစက္ကူပါးအလွှာတစ်ခုစီတွင်
သီးသန့် သတင်းအချက်အလက်များပါရှိပြီး အလွှာများကို 
မိမိနှစ်သက်ရာ ပြန်လည်စီစဉ်နိုင်သည်။

ရည်ညွှန်းကိုးကားရာအဖြစ်အသုံးပြုသည့်ဂြိုဟ်တုပုံရိပ်၊ GPS လမ်းကြောင်းများနှင့် 
ကွင်းဆင်းမြေပုံတို့ကဲ့သို့သောအလွှာများကို "အခြေခံအလွှာများ"(base layers) ဟုခေါ်သည်။ အမှန်တကယ်အသုံးပြုလုပ်ကိုင်မည့်အလွှာမှာ OSM ဒေတာအလွှာဖြစ်သည်။

- အလွှာတစ်ခုကိုပြောင်းရွှေ့စီရန်အတွက် Layers အကွက်တွင်ပြောင်းရွှေ့လိုသောအလွှာကိုရွေးပါ။ 
    ထို့နောက် အပေါ်ဘက် သို့မဟုတ် အောက်ဘက်ပြသထားသော မြားသဏ္ဍာန်ခလုတ်များကို အသုံးပြုရွှေ့ပြောင်းပါ။

![Layers up down][]

- အလွှာတစ်ခုကိုဖျောက်ထားရန်အတွက် 
    Show/Hide ခလုတ်ကို နှိပ်ပါ။

![Layers show hide][]

- အလွှာတစ်ခုကိုရွေးထားပြီး Show/Hide ခလုတ်ကို နှိပ်ပါက မြင်ကွင်းမှပျောက်သွားမည်ဖြစ်ပြီး 
    နောက်တစ်ကြိမ်ထပ်နှိပ်ပါက မြင်ကွင်းတွင်ပေါ်လာမည်ဖြစ်သည်။
- အလွှာတစ်ခုကိုဖယ်ထုတ်ရန်အတွက် ယင်းအလွှာကိုရွေးချယ်ပြီး အောက်ပါပုံအတိုင်းမြင်တွေ့ရသော Delete 
    ခလုတ်ကိုနှိပ်ပါ။

![Layers delete][]

နောက်ဆုံးအချက်အဖြစ် အရေးတကြီးသိထားရန်မှာ JOSM ဆော့လ်ဖ်ဝဲလ်မှအသုံးပြုရန်အသင့်ဖြစ်ကြောင်း သတ်မှတ်ထားသည့် အလွှာ၌သာ
    ပြုပြင်တည်းဖြတ်မှုပြုလုပ်နိုင်မည်ဖြစ်သည်။ မြေပုံမျက်နှာပြင်တွင် မြေပုံကိုပြုပြင်မှုမပြုနိုင်ပါက သင့်လျော်သောမြေပုံအလွှာကို 
    ရွေးချယ်သတ်မှတ်ထားခြင်းမရှိသည်လည်းဖြစ်နိုင်ပါသည်။
    နေရာညွှန်ပြသော GPSအမှတ်များ၊ ကွင်းဆင်းမြေပုံများနှင့် 
    ဂြိုဟ်တုပုံရိပ်တို့ကဲ့သို့ အလွှာအများစုကို ပြုပြင်တည်းဖြတ်မှုပြုနိုင်မည်မဟုတ်ချေ။ 
    OpenStreetMap မှမြေပုံအချက်အလက်များကိုသာ ပြုပြင်တည်းဖြတ်မှုပြုနိုင်သောအလွှာများအဖြစ် အသုံးပြုနိုင်သည်။ 
    ၎င်းတို့ကို “Data Layer 1” ဟုခေါ်ဝေါ်သုံးစွဲသည်။
- အလွှာတစ်ခုကို အသင့်အသုံးပြုနိုင်သောအခြေအနေဖြစ်စေရန်အတွက် Layers အကွက်တွင် မိမိအသုံးပြုလိုသောအလွှာကိုရွေးချယ်ပါ။
    ထို့နောက်အောက်ပါပုံအတိုင်းမြင်တွေ့ရသော Activate ခလုတ်ကိုနှိပ်ပါ။

![Layers activate][]


နေရာညွှန်မှတ်ပြ GPS အချက်အလက်များနှင့် ကွင်းဆင်းမြေပုံများအားအသုံးပြုခြင်း
-------------------------------
 [လက်ကိုင်ဖုန်း(သို့) GPS (သို့) စာရွက်ဖြင့် မြေပုံဆွဲခြင်းသင်ခန်းစာ] (/my/mobile-mapping/) တွင် ယင်းကိရိယာများအသုံးပြုလျက် အချက်အလက်စုဆောင်းခြင်းနှင့် 
JOSM ဆော့လ်ဖ်ဝဲလ်တွင် အလွှာအဖြစ်ထည့်သွင်းအသုံးပြုခြင်းတို့ကို တွေ့မြင်ခဲ့ပြီးဖြစ်သည်။

ယင်းကဲ့သို့အသုံးပြုကောက်ယူပါက သင်ရရှိသောသတင်းအချက်အလက်များကို OpenStreetMap ၏ဒေတာအချက်အလက်များသို့ 
ပေါင်းထည့်ရန်အတွက် ကွန်ပျူတာနည်းပညာကိုအသုံးပြုရန်လိုအပ်သည်။

ရှေ့သင်ခန်းစာများတွင်လေ့လာခဲ့သော - **download ပြုလုပ်ရယူ၊ ပြင်ဆင်တည်းဖြတ်၊ သိမ်းဆည်း ဖြစ်စဉ်များ**အတိုင်း 
သင်ရရှိထားသောအချက်အလက်များကို ပေါင်းထည့်ပေးနိုင်သည်။ ဂြိုဟ်တုပုံရိပ်ကို အခြေခံအလွှာအဖြစ်အသုံးပြုခြင်းအစား 
GPS ဒေတာများ၊ ကွင်းဆင်းမြေပုံများ၊ မှတ်စုများ သို့မဟုတ် ယင်းအချက်အလက်အစုအပေါင်းများကို 
အသုံးပြုခြင်းဟူ၍သာကွဲပြားသွားမည်ဖြစ်သည်။

- ဥပမာ။ JOSM ဆော့လ်ဖ်ဝဲလ်တွင် နောက်ခံအလွှာအဖြစ်အသုံးပြုရန် GPS အမှတ်တစ်ခုရှိထားပြီဆိုပါစို့။
    ယင်းအမှတ်ကို ၀၃၀ ဟုအမည်ပေးပြီး 
    ကျောင်းတစ်ကျောင်းအဖြစ် သင့်မှတ်စုစာအုပ်တွင်ရေးမှတ်ထားပါ။
    ထိုအမှတ်ကို OpenStreetMap အချက်အလက်များသို့ထည့်သွင်းရန်အတွက် JOSM ဆော့လ်ဖ်ဝဲလ်မှ ပုံဆွဲကိရိယာကိုရွေးချယ်ပြီး 
    မြေပုံပေါ်ရှိယင်းအမှတ် ၀၃၀ ပေါ်တွင်ကွန်ပျူတာ mouse ဖြင့်နှစ်ချက်နှိပ်ပါ။ 
    မြေပုံပေါ်တွင်အမှတ်တစ်ခုမှတ်သားဖော်ပြပေးမည်ဖြစ်သည်။ ထို့နောက်ကျောင်းအတွက်ကြိုတင်သတ်မှတ်ချက်များပြုလုပ်ရန် menu ဘားတန်းရှိ  Presets ကိုရွေးပါ။ ယင်းအထဲမှ ကျောင်းအမှတ်အသားကိုရှာပါ။
    ပေါ်လာသော အကွက်တွင် ကျောင်းအမည်ကိုဖြည့်သွင်းပြီး “Apply Preset” ကိုနှိပ်ပါ။ 
    မျဉ်းကြောင်းများနှင့် ပုံသဏ္ဍာန်များထည့်သွင်းရန်ကိုလည်း အထက်ပါအတိုင်းဆောင်ရွက်နိုင်သည်။

![GPS in JOSM][]

ညွှန်းဆိုမှုများ
----
အမှတ်၊ မျဉ်းကြောင်းနှင့်ပုံသဏ္ဍာန်တို့ကိုရေးဆွဲလျှင် ယင်းတို့၏တည်နေရာဖော်ပြချက်သာပါရှိပြီး 
မည်သည့်အရာဖြစ်ကြောင်း အသိပေးဖော်ပြချက်များပါရှိမည်မဟုတ်ချေ။ တစ်နည်းဆိုသော် **တည်နေရာ**သာသိရှိပြီး 
**ဘယ်အရာ**ဖြစ်ကြောင်းမသိနိုင်ပေ။ ထိုသို့ခွဲခြားဖော်ပြရန်အတွက် 
menu ဘားတန်းရှိ Presets ကိုအသုံးပြုကြောင်းအထက်တွင်ဖော်ပြပြီးဖြစ်၏။ 
OpenStreetMap တွင် **မည်သည့်အရာ**ဖြစ်ကြောင်းဖော်ပြရန်အတွက် **ညွှန်းဆိုမှုများ**ကိုထည့်သွင်းအသုံးပြုကြသည်။

အညွှန်းတစ်ခုသည် အမည်စာတန်းတစ်ခုကဲ့သို့ပင် သင်ဖြည့်စွက်လိုသည်များကိုရေးထည့်နိုင်သည်။ ဥပမာ ...
ထောင့်မှန်စတုဂံတစ်ခုရေးဆွဲလိုက်ပါက ယင်းသည်ထောင့်မှန်စတုဂံပုံအတိုင်းသာမြင်တွေ့ရမည်။ ထို့နောက် ထောင့်မှန်စတုဂံပုံတွင် သက်ဆိုင်သောရုပ်လက္ခဏာဖော်ပြချက်များ ထည့်သွင်းပါက
ထိုအရာသည် “Menara Thamrin” ဟုအမည်ရသော အဆောက်အဦတစ်ခုဖြစ်ပြီး 
၁၆ ထပ်အမြင့်ရှိသည် စသည်ဖြင့်ဖော်ညွှန်းပေးနိုင်၏။

အရာဝတ္ထုတစ်ခုတွင် မိမိနှစ်သက်သလောက် အညွန်းများထည့်သွင်းဖော်ပြနိုင်သည်။ အညွှန်းများကို
 **keys** နှင့် **values** ဟူ၍စာသားအစုံလိုက်ဖြင့် သိမ်းဆည်းသွားမည်ဖြစ်သည်။ 
အထက်ဥပမာကို OpenStreetMap တွင်အညွှန်းဖော်ပြမှတ်သားပါက အောက်ပါအတိုင်းဆောင်ရွက်နိုင်သည်။

- building(အဆောက်အဦ) = yes(မှန်)
- name(အမည်) = Menara Thamrin
- building:levels(အဆောက်အဦအမြင့်) = 16

JOSM ဆော့လ်ဖ်ဝဲလ်တွင် အရာဝတ္ထုတစ်ခုကိုရွေးချယ်လိုက်ပါက ယင်းနှင့်သက်ဆိုင်သောအညွှန်းများကို 
ဆော့လ်ဖ်ဝဲလ်မျက်နှာပြင်၏ ညာဘက်တွင်ရှိသော Properties အကွက်တွင်မြင်တွေ့နိုင်သည်။

![Properties panel][]

### အညွန်းများကို ပြင်ဆင်တည်းဖြတ်ခြင်း
Properties အကွက်တွင် အညွှန်းများကိုထည့်သွင်းခြင်း၊ ပြင်ဆင်တည်းဖြတ်ခြင်းနှင့် ဖယ်ထုတ်ခြင်းတို့ကို ပြုလုပ်နိုင်သည်။ အညွှန်းများကို 
အင်္ဂလိပ်ဘာသာစကားဖြင့်ဖော်ပြလေ့ရှိပြီး တစ်ခါတစ်ရံတွင်နားလည်ရရှုပ်ထွေးစေနိုင်သည်။
ထို့ကြောင့် menu ဘားတန်းရှိ Presets ကိုအသုံးပြုခြင်းက ပိုမိုလွယ်ကူစေနိုင်၏။ အညွှန်းများကို ဖြည့်သွင်း သို့မဟုတ် ပြောင်းလဲပါက အရာဝတ္ထု၏ဖော်ပြချက်လက္ခဏာရပ်တို့လည်း
ပြောင်းလဲသွားမည်ဖြစ်သည်။

- ဦးဆုံးအနေဖြင့် ပြုပြင်တည်းဖြတ်လိုသောအညွှန်းကိုရွေးချယ်ပါ။
- အောက်ဖော်ပြပါအချက်နှစ်ချက်အနက်မှ မိမိနှစ်သက်ရာတစ်ခုအတိုင်းပြင်ဆင်တည်းဖြတ်နိုင်ပါသည်။ (၁) menu ဘားတန်းရှိ Presets ကိုအသုံးပြုခြင်း
    သို့မဟုတ်(၂) ဆော့လ်ဖ်ဝဲလ်မျက်နှာပြင်၏ ညာဘက်တွင်ရှိသော Properties အကွက်တွင် ပြင်ဆင်တည်းဖြတ်ခြင်းတို့ဖြစ်သည်။ 

### မှားလေ့ရှိသောအမှား ။ ။ မျဉ်းကြောင်းများ သို့မဟုတ် ပုံသဏ္ဍာန်များကိုအညွှန်းတပ်စဉ် ယင်းတို့အပေါ်ရှိအမှတ်ငယ်များတွင် မှားယွင်းညွှန်းဆိုမိခြင်း
အရာဝတ္ထု၏ဖော်ပြချက်လက္ခဏာရပ်တို့ကို ပြုပြင်တည်းဖြတ်ရာတွင် ယင်းအမှတ်တို့ကိုဦးစွာရွေးချယ်ပြီးနောက် 
menu ဘားတန်းရှိ Presets ကိုအသုံးပြု၍သော်လည်းကောင်း သို့မဟုတ်
Properties အကွက်တွင် တိုက်ရိုက်သွားရောက်၍သော်လည်းကောင်း အညွှန်းများထည့်သွင်းနိုင်သည်။ မျဉ်းကြောင်းများ သို့မဟုတ် ပုံသဏ္ဍာန်များကိုအညွှန်းတပ်စဉ်တွင် မှားယွင်းလေ့ရှိသောအရာတစ်ခုရှိ၏။ 
အရာဝတ္ထုကိုရွေးချယ်ရာတွင် ယင်း၏မျဉ်းသားပေါ်သို့ရွေးရမည်ဖြစ်ပြီး 
မျဉ်းကိုဆက်ပေးထားသော အမှတ်ငယ်များပေါ် မရွေးချယ်မိရန်အရေးကြီးလှသည်။

အရာဝတ္ထုကိုရွေးချယ်ရန်အတွက် JOSM ဆော့လ်ဖ်ဝဲလ်ရှိ ရွေးချယ်ကိရိယာကိုအသုံးပြုရခြင်းကြောင့် 
မျဉ်းကြောင်း**နှင့်တကွ**အမှတ်ငယ်များပါ ခြုံငုံရွေးချယ်မိတတ်ပြီး 
အညွှန်းတပ်ရာတွင် အားလုံးအပေါ်ခြုံငုံသက်ရောက်စေနိုင်သည်။ 
ထို့ကြောင့်မျဉ်းများအတွက်အညွှန်းတပ်ရာတွင် **မျဉ်းသားပေါ်တွင်သာ**သေချာစွာရွေးချယ်ပေးရန်
လိုအပ်လှသည်။

![Nodes mistake][]

OSM ဖိုင်များကိုသိမ်းဆည်းခြင်း
----------------
JOSM ဆော့လ်ဖ်ဝဲလ်၌ မြေပုံပြင်ဆင်တည်းဖြတ်မှုပြုလုပ်ရာတွင်မြေပုံ download ပြုလုပ်၍ရယူခြင်း၊ ပြင်ဆင်တည်းဖြတ်ခြင်းနှင့် 
ပြင်ဆင်ပြီးသောမြေပုံကို ပြန်လည်သိမ်းဆည်းထားရှိခြင်းတို့ကို သင့်တော်သောအချိန်တိုအတွင်းပြုလုပ်ရန်မှာ စိတ်ကူးကောင်းတစ်ခုပင်ဖြစ်သည်။
မြေပုံရယူခြင်းနှင့် တည်းဖြတ်ထားသောမြေပုံကိုပြန်လည်သိမ်းဆည်းဖော်ပြခြင်းတို့ ကြားကာလကို ရက်ရွှေ့ဆိုင်းကာ မပြုလုပ်သင့်ပေ။
အကြောင်းမှာ အခြားသူတစ်ဦးဦးမှ သင်နှင့်တည်နေရာတူတစ်ခုအား တစ်ချိန်တည်းပြင်ဆင်တည်းဖြတ်ခဲ့ပါက ကွဲလွဲမှုများနှင့် အမှားအယွင်းများ ဖြစ်ပေါ်နိုင်သောကြောင့်ဖြစ်သည်။

သင်ပြင်ဆင်တည်းဖြတ်ထားသည်များကို မကြာခဏပြန်လည်သိမ်းဆည်းဖော်ပြရန် မစိုးရွံ့ပါနှင့်။ 
ထိုသို့ပြုလုပ်ခြင်းက OpenStreetMap အချက်အလက်သိုမှီးမှုတွင် သင်၏ပြင်ဆင်တည်းဖြတ်မှု အပိုင်းကိုသွားရောက်သိမ်းဆည်းပေးနိုင်ပြီး သင်ကိုယ်တိုင်ကြိုးစားခဲ့သမျှကို ဆုံးရှုံးမသွားရန်အတွက် သေချာစေပါသည်။

တည်နေရာတစ်ခုတည်းအတွက် ရည်စူးပြင်ဆင်ပါက
သင်ပြင်ဆင်တည်းဖြတ်လိုသည့်အကြိမ်တိုင်းတွင် မြေပုံအချက်အလက်များကို အဖန်ဖန်ရယူရန်လိုအပ်သည်။ အကြောင်းမှာသင်ပြင်ဆင်တည်းဖြတ်သောအချိန် တစ်ခုနှင့်တစ်ခုအကြားတွင် အခြားအသုံးပြုသူတစ်ဦးမှ ပြင်ဆင်ဖြည့်စွက်ပြောင်းလဲမှုများ ပြုလုပ်ထားနိုင်သောကြောင့်ဖြစ်၏။

ထိုကဲ့သို့ ကာလတိုအတွင်း ပြီးမြောက်အောင်ဆောင်ရွက်သင့်သော်လည်း 
မြေပုံအချက်အလက်များကို သင့်ကွန်ပျူတာတွင်သိမ်းဆည်းထားရန်
သင့်ကွန်ပျူတာတွင် သိမ်းဆည်းထားရန်အကြောင်းများလည်း ရှိလာနိုင်ပါသည်။ ဥပမာ ... အင်တာနက်ချိတ်မှု ပုံမှန်မရရှိသောအခါ 
သင်ပြင်ဆင်တည်းဖြတ်လိုသော မြေပုံအချက်အလက်များကို ရယူသိမ်းဆည်းပြင်ဆင်တည်းဖြတ်ပြီးနောက် 
အလျဉ်းသင့်သောအချိန်ပိုင်းရောက်မှသာ သင်ပြင်ဆင်တည်းဖြတ်မှုကို OpenStreetMap သို့ပြန်လည်သိမ်းဆည်းနိုင်ပါသည်။

- OSM ဖိုင်ကိုသိမ်းဆည်းရန်အတွက် layer အကွက်တွင် မိမိသိမ်းဆည်းလိုသောဖိုင်ကို လက်ရှိအလုပ်လုပ်ကိုင်နိုင်သောlayer ဖြစ်ထားရှိပါ။  
    ထို့နောက် menu ဘားတန်းပေါ်ရှိ “File” ကိုနှိပ်ပြီး “Save” ရွေးချယ်နှိပ်ပါ။ 
    မိမိထားလိုသောနေရာကိုရွေးပြီး ဖိုင်ကိုအမည်ပေးသိမ်းဆည်းပါ။ 
    အောက်တွင်ဖော်ပြထားသောခလုတ်ကိုနှိပ်၍လည်း သိမ်းဆည်းခြင်းကိုဆောင်ရွက်နိုင်သည်။

![JOSM save button][]

- JOSM ဆော့လ်ဖ်ဝဲလ်ကိုပိတ်လိုက်ပါ။ အချက်အလက်ဒေတာသည်သိမ်းဆည်းပြီးဖြစ်ပါလိမ့်မည်။ 
    ယင်းဖိုင်ကိုဖွင့်လိုပါက ဆော့လ်ဖ်ဝဲလ်ကိုဖွင့်၍ menu ဘားတန်းရှိ “File” မှ
    “Open...”ကိုနှိပ်ပါ။

အကျဉ်းချုပ်ဖော်ပြချက်
-------
ယခုသင်ခန်းစာတွင် JOSM ဆော့လ်ဖ်ဝဲလ်၏ သွင်ပြင်လက္ခဏာကိုအနည်းငယ်မျှအသေးစိတ်ကာ ရှုမြင်ခဲ့ပြီး 
ယခုအခါသင်သည်မြေပုံဆွဲခြင်းနှင့် 
OpenStreetMap မြေပုံတည်းဖြတ်ခြင်းတို့ကို အထူးပြုလေ့လာခဲ့ပြီးဖြစ်သည်။


[Layers panel]: /images/josm/josm_layers-panel.png
[Layers up down]: /images/josm/josm_layers-panel-up-down.png
[Layers show hide]: /images/josm/josm_layers-panel-show-hide.png
[Layers delete]: /images/josm/josm_layers-panel-delete.png
[Layers activate]: /images/josm/josm_layers-panel-activate.png
[GPS in JOSM]: /images/josm/josm_gps-layer.png
[Properties panel]: /images/josm/josm_properties-panel.png
[Nodes mistake]: /images/josm/josm_nodes-selected-mistake.png
[JOSM save button]: /images/josm/josm_save-button.png