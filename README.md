# Markov Chain in Myanmar Language

I wrote this small snippet based on golang's [markov chain implementation](https://golang.org/doc/codewalk/markov/) to experiment what markov chain generated texts look like in Myanmar language. Since Myanmar Language don't have spaces between words, I wrote [a small package](https://github.com/ha-shine/mmutil) to break the sentences into words. **Currently this works only in unicode**

# Test

In [1.txt](/1.txt) is the content of [this](https://www.facebook.com/YoYarLay/posts/1581873948522518) facebook post and I got the below as an output.

ယင် ကောင် နဲ့  သူ့ ရဲ့ သား ကောင် တစ် ကောင် ရဲ့  ဖျတ် ခ နဲ ဖြစ် လာ သော  ပုံ ရိပ် တွေ ကို  လက် နဲ့ လှမ်း ရိုက် မ လဲ ဆို တဲ့  အ မြန် နှုန်း တစ် ခု ကို ကို  ထုတ် လွှတ် ပြီး  ဒီ လျှပ် စီး ကြောင်း တွေ က  ကွန် ပျု တာပေါ် မှာ  ဇ ယား တစ် ခုပေါ် လာ စေ ပါ တယ် ။  ယင် ကောင် တွေ ရဲ့  ဘတ် ထ ရီ အ ဖြစ်  လုပ် ဆောင် ပေး တဲ့  ပျံ သန်း နိုင် တဲ့  ပုံး တစ် ပုံး တည်း မှာ  လွှတ် ပေး လိုက် ပြီး မှတ် တမ်း တင် ထား ပါ တယ် ။  ဒါ ပေ မဲ့  လိပ် တစ် ကောင် ရဲ့  ဖျတ် ခ နဲ ဖြစ် လာ သော  ပုံ ရိပ် များ ကို  ပေါင်း စပ် နှုန်း လို့ခေါ် ပါ တယ် ။  ဖြစ် စဉ် တစ် ခု နဲ့  ပို့ ကြ တာ ပါ ။  ဒါ က  သ ဘာ ဝ တ ရား ကြီး က ပေး ထား တဲ့  စွမ်း အား တစ် ခု ကြည့် နေ သ လို ပါ ပဲ ။ ယင် ကောင် တွ ထဲ  အ မြင် အား ကောင်း နေ ဖို့  လို အပ် ပါ တယ် ။  ဒီ လို  မိုက် တို ခွန် ဒ ရီး ယား တွေ  အ များ ကြီး ပါ နေ ရင် လည်း  ယင် ကောင် တွေ ကျ တော့  လှမ်း ရိုက် တာ လောက် က  သူ့ အ တွက်  ယင် ကောင် တွေ ကျ တော့  ဘာ ကြောင့်  အ ရမ်း

Super fun! :smile: