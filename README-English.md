[README in Myanmar](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard)  

# kKg-Myanmar-Keyboard (Version 1)
kKg Myanmar (Unicode) Keyboard Layout that I designed for lazy users (actually, I was the 1st user :).  
I do hope it will be useful for non-Myanmar native users who are studying Myanmar (Burmese) language.  

# Introduction to kKg (ကခဂ) Keyboard Layout

Although I love Myanmar characters, I was so lazy for practicing Myanmar text typing with existing Myanmar keyboard layouts. Actually, most of the Myanmar keyboard layouts are based on old Myanmar typewriter layout and they have similar key mappings. In 2004, I have to type Myanmar text for my master thesis research relating to __Myanmar text typing on mobile phone__. I hope you can guess the situation ... He Hee.. :) And thus, I did self-study on changing keyboard layout on Linux OS with XKB and this is the history of my "kKg Keyboard Layout". 

My idea is mapping Myanmar characters on English QWERTY keyboard based on their phonetic similarities with English characters such as Myanmar consonant "က" (Ka) on k key, "ခ" (Kha) on K (Shift+K) key. Here, I have to consider which character should I put on shifted keys. Generally, frequently used characters were put on unshifted keys. Refer following key mapping:


* က on <kbd> k </kbd> key, ခ on K ( <kbd> shift </kbd> + <kbd> k </kbd> ) key  
* ဂ on <kbd> g </kbd> key, ဃ on G ( <kbd> Shift </kbd> + <kbd> g </kbd> ) key  
* စ on <kbd> s </kbd> key, ဆ on S ( <kbd> Shift </kbd> + <kbd> s </kbd> ) key  
* ဇ on <kbd> z </kbd> key, ဈ on  Z ( <kbd> Shift </kbd> + <kbd> z </kbd> ) key  
* ဒ on <kbd> d </kbd> key, ဓ on D ( <kbd> Shift </kbd> + <kbd> d </kbd> ) key  
* န on <kbd> n </kbd> key, ဏ on N ( <kbd> Shift </kbd> + <kbd> n </kbd>) key  
* ပ on <kbd> p </kbd> key, ဖ on P ( <kbd> Shift </kbd> + <kbd> p </kbd> ) key  
* ဗ on B ( <kbd> Shift </kbd> + <kbd> b </kbd>)key, ဘ on <kbd> b </kbd> key  
* မ on <kbd> m </kbd> key  
* ယ on ( <kbd> Shift </kbd> + <kbd> y </kbd>), ရ on <kbd> y </kbd> key   
* လ on <kbd> l </kbd> key, ဠ on ( <kbd> Shift </kbd> + <kbd> l </kbd> ) key ... 

Now, finished key mapping for almost all of the Myanmar consonant, right?  
However, there are 33 Myanmar consonants and 26 keys of English is not enough for mapping all Myanmar consonants. Moreover, some Myanmar consonants have same or similar pronunciation such as တ (ta) and သ (tha), ဒ (da), ဓ (da), ဋ (ta), ဍ (da) and ဎ (da), ထ (hta) and ဌ (hta). And thus, some Myanmar characters are mapped on English keys who pronunciations are totally different with Myanmar such as ည (nya) is mapping on <kbd> q </kbd>, ဋ (ta) is mapping on <kbd> v </kbd>, ဌ is mapping on capital X ( <kbd> Shift </kbd> + <kbd> x </kbd> ), ဍ is mapping on capital v ( <kbd> Shift </kbd> + <kbd> v </kbd> ) and ဦ is mapping on capital m ( <kbd> Shift </kbd> + <kbd> m </kbd> ).

One more concept that I applied is key mapping based on the similar shape of characters.  
For examples:  

Myanmar consonant "င" (Nga) is mapping to English small c, <kbd> c </kbd> key
Myanmar  ့ (sign dot below) and ံ (sign anusvara) are mapping on full stop <kbd> . </kbd> key  
Myanmar consonant sign medial ya " ျ " is mapping to small j, <kbd> j </kbd> key  

Some character mappings are based on similarity of usage between Myanmar and English.  
For example:  

Myanmar sign little section "၊" is mapping on English comma <kbd> , </kbd> key  

Based on above concepts, the following is the kKg keyboard mapping according to Myanmar characters order:

 * For Myanmar Consonant  
 
   | က<br>k | ခ<br>K | ဂ<br>g | ဃ<br>G | င<br>c |
   | :-------------: |:-------------: |:-------------: |:-------------: |:-------------: |
   | စ<br>**s** | ဆ<br>**S** |ဇ<br>**z**  |ဈ<br>**Z**  |ည<br>**q** |
   | ဋ<br>**v** | ဌ<br>**X** |ဍ<br>**V**  |ဎ<br>**~**  |ဏ<br>**N** |
   | တ<br>**T** | ထ<br>**x** |ဒ<br>**d**  |ဓ<br>**D**  |န<br>**n** |
   | ပ<br>**p** | ဖ<br>**P** |ဗ<br>**B**  |ဘ<br>**b**  |မ<br>**m** |
   | ယ<br>**Y** | ရ<br>**y** | လ<br>**l** | ဝ<br>**w**  | သ<br>**t** |
   || ဟ<br>**h** | ဠ<br>**L** |အ<br>**a** ||

* For Myanmar vowels   

   | ာ<br>r | ါ<br>R | ိ<br>i | ီ<br>I |
   | :-------------: |:-------------: |:-------------: |:-------------: |
   | ု<br>**u** | ူ<br>**U** | ေ<br>**A**  | ဲ<br>**e**  |
   | ဩ<br>**O** | ဪ<br>**o** | ့<br>**.**  | ံ<br>**>**  |
   | း<br>**;** |
   

I think now you can guess the name of kKg is representing first three Myanmar consonants "က", "ခ" and "ဂ". Although I don't think my keyboard mapping kKg is the best for Myanmar text typing, it is really useful for me. I am using it and I hope it will be useful for someone who doesn't want to practice current Myanmar keyboard layouts. Especially for non-native Myanmar who just want to type some Myanmar words for his/her works. Current kKg keyboard layout (version 1.0) is as follow:  

![kKg Keyboard Layout Version.1](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/ver1/kKg-Keyboard-Layout-Ver1.png)

Typing orders are same with other Myanmar Unicode Keyboard layouts such as Myanmar3 keyboard layout.  
First, you have to type Myanmar consonant and follow by other vowels.  
For example:  

"က" + " ေ " for "ကေ"  
"က" + " ု "  + " ံ " for "ကုံ"  

For stacked (PadSint) characters:  

"က" + " ္ " + "က" for "က္က"  

# Installation  

kKg keyboard is not only for Linux OS and I plan to upload installer for Windows after testing on two/three Windows OS. Please wait for a while.  

## Installation kKg on Ubuntu OS  

### Installation Method (1)  
If you plan to replace default Myanmar keyboard layout with kKg, do the following steps. With this installation method, you can see only kKg keyboard layout with the default name "Burmese" in your Text Entry Settings. You can return back to default Myanmar keyboard when you need.  

 1. First move to xkb/symbols directory:   
   cd /usr/share/X11/xkb/symbols/  
   
 2. Change filename (default Myanmar symbols file) "mm" to "mm.default":  
    sudo mv ./mm ./mm.default  
    
 3. Copy [kkg](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/ver1/kkg) file into /usr/share/X11/xkb/symbols/ directory as "mm":  
    sudo cp ~/your-download-path/kkg ./mm   
    
 4. Click the input method icon (top right corner of X Windows Desktop), select "Text Entry Settings..." menu and click "+" button and then select "Burmese" as shown in following figure:  
 
 ![choose-input-source-dialogue-box](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/xkb-intro/choose-input-source.png)
 
 Or  
 You can also go from "System Setting", "Text Entry" and click "+" for adding/selecting a keyboard layout.  
 
 5. After you added "Burmese" keyboard layout, you can change your current input method or keyboard layout to "Burmese" by clicking text input method icon (top right corner of X Windows Desktop) as shown in the following figure or pressing "Super+Space Bar" (you might need to press 2/3 times, it depends on how many text input method are you using on your X Windows). Here "[Super](https://help.ubuntu.com/stable/ubuntu-help/windows-key.html)" Key means "Windows" key or "Command" key in Apple keyboard.   
 
 ![text-input-method-icon](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/xkb-intro/text-input-method-icon.png)  
 
 In the above figure, Ja is indicating that current keyboard layout is using "Japanese".  
 
 ### Uninstallation for Installation Method No.(1)
 
 If you want to switch back to Ubuntu default Myanmar keyboard layout, change filename "mm.default" under the path /usr/share/X11/xkb/symbols/ to "mm".  

* Note: Your future upgrade relating to xkb package will return back to default mm keyboard.  

### Installation Method (2)  
If you want to add kKg keyboard as a new keyboard layout in your X Windows:  
(I assume you already downloaded kKg-Myanmar-Keyboard from this GitHub)

 1. Copy downloaded [kkg](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/ver1/kkg) symbols file to /usr/share/X11/xkb/symbols/ path:
 ```
    sudo cp ~/your-download-path/kkg /usr/share/X11/xkb/symbols/kkg
 ```
 2. Change to /usr/share/X11/xkb/rules/:
 ```
 cd /usr/share/X11/xkb/rules
 ```
 3. Open evdev.xml file with an editor such as vi, emacs and gedit:
 ```
 sudo gedit evdev.xml
 ```
  put following XML content, save and quit:
 
 ```xml
 <layout> 
      <configItem>
        <name>kkg</name>
        
        <shortDescription>kkg</shortDescription>
        <description>kKg (Myanmar)</description>
        <languageList>
          <iso639Id>mya</iso639Id>
        </languageList>
      </configItem>
      <variantList/>
    </layout> 
 ```
 
 4. Open evdev.lst file and add following line:
 
 ```
  kkg             kKg (Myanmar)
 ```

Adding above line according to the alphabetical order is better for searching (see the following figure):

![adding-in-evdev.lst-file](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/xkb-intro/adding-kkg-evdev.lst.png)

5. Open "Text Entry dialogue box" by clicking "US" (If your current keyboard layout is US) and selecting the "Text Entry Settings...".

*Another option: You can also open "Text Entry dialogue box" by clicking the "Settings icon" in the upper-right corner of the screen, select "System Setting..." and then select "Text Entry".*

![text-entry-dialogue-box](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/xkb-intro/Text-Entry-Dbox.jpg) 

6. Click the "+" button under the list of installed keyboard layouts and then select "kkg (Myanmar)" as shown in the following figure:

![choose-an-kkg-input-Source](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/xkb-intro/ChooseAnInputSource.jpg)

7. To test "kKg (Myanmar)" keyboard layout is working or not, look at the keyboard layout icon, in the upper-right corner of your screen, and then switch your current keyboard layout to "kKg (Myanmar)" (see following figure).

![selecting-kkg-eg](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/xkb-intro/selecting-kkg-eg.jpg)

You can also switch keyboard layout by pressing "Super Key" + "Space Bar". Here, "Super Key" is Windows key or Command key.

Note: Depends on your Ubuntu OS distributions, sometimes you also have to update base.lst, base.xml, xfree86.lst, xfree86.xml as I mentioned in step 3 and 4. One more information is that I have to reboot for activating a new keyboard layout on Ubuntu OS 14.04 LTS computer.  

### Uninstallation for Installation Method No.(2)  

Just remove the text (XML content and one sentence) in the files that you added such as evdev.xml and evdev.lst.
If you updated base.xml, base.lst, xfree86.xml, xfree86.lst, remove in that files also.


# For First-time Myanmar Text Typing with kKg Keyboard  
If you wish to try Myanmar text typing with kKg keyboard, I do suggest you to see keyboard layout and try to catch up the concept of kKg keyboard design. I assumed that you already know the pronunciation of Myanmar consonants and vowels. If you don't know the pronunciation of Myanmar characters, refer [Unicode chart](http://www.unicode.org/charts/PDF/U1000.pdf) and [Romanization Table](https://www.loc.gov/catdir/cpso/romanization/burmese.pdf). Generally, you can guess the keys for Myanmar characters based on their pronunciations such as "က" (Ka Gyi) on <kbd> k </kbd> key, "ခ" (Kha Khway) also on <kbd> k </kbd> key  but the point is you have to practise for "unshifted" and "shift" assignments. As a first step, I do suggest you to start practice typing Myanmar consonants according to their alphabetical order (i.e. "က" (Ka) to "အ" (A)). If you want to start typing Myanmar words and sentences quickly, you can skip some Myanmar consonants that rarely used in daily communication such as "ဋ", "ဍ", ဎ and "ဠ".   

  Similarly, you also have to practice for key mappings of Myanmar vowels based on their pronunciation order (i.e. A, AA, I, II, U, UU, E, AI, O, AU, EN, ARR or အ၊ ာ၊ ိ၊ ီ၊ ု၊ ူ၊ ေ၊ ဲ၊ ော့၊ ော်၊ ံ၊ ား). Although I haven't made formal user study, I roughly did a kind of user study on kKg keyboard layout with some of my friends and I found that they can start typing Myanmar words and sentences with appropriate speed after practicing around 30 minutes. The following is the procedure of typing practice that I used:
   
1. Frequently used Myanmar consonants  

   ```
   က   ခ   ဂ   ဃ   င
   စ   ဆ   ဇ   ဈ   ည
   ဌ   ဏ
   တ   ထ   ဒ   ဓ   န
   ပ   ဖ   ဗ   ဘ   မ
   ယ   ရ   လ   ဝ  သ
   ဟ   အ
      
    ဝ   ထ   က   လ   သ
   ```  
  
2. Myanmar vowels  

    ```
    ာ   ါ   ိ   ီ   ု   ူ   ေ   ဲ  ့  ်   ံ   း
    ```
    
3. Combination of consonant and vowels  
  
    ```
    က ကာ ကိ ကီ ကု ကူ ကေ ကဲ ကော့ ကော် ကံ ကား
    ခ ခါ ခိ ခီ ခု ခူ ခေ ခဲ ခေါ့ ခေါ် ခံ ခါး
    ဂ ဂါ ဂိ ဂီ ဂု ဂူ ဂေ ဂဲ ဂေါ့ ဂေါ် ဂံ ဂါး
    စ စာ စိ စီ စု စူ စေ စဲ စော့ စော် စံ စား
    ပ ပါ ပိ ပီ ပု ပူ ပေ ပဲ ပေါ့ ပေါ် ပံ ပါး
    မ မာ မိ မီ မု မူ မေ မဲ မော့ မော် မံ မား
    အ အာ အိ အီ အု အူ အေ အဲ အော့ အော် အံ အား
    ```
4. Practicing " ျ ", " ြ ", " ွ ", " ှ " and some Myanmar words  
  
    ```
    ကွ ပွ မွ လွ
    ကျ ကျွ ကြ ကြွ
    ကျွဲ ကြွဲ ချွဲ ဂျွဲ
    မွဲ ပွဲ ဆွဲ ရွဲ
    မမ လှလှ
    နွှဲ နွှဲ ကျွဲ ကျွဲ
    မျ မြ မျာ များ
    ကျောင်းသား ကျောင်းသူ ဆရာမ ကျောင်းသွား 
    ရောင်းကောင်း စားကောင်း ကောင်းမှကောင်း
    မသိ တယောက် နှစ်ယောက် သုံးလေးယောက်
    ```
   
 5. Practicing short Myanmar sentences together with two Myanmar symbols  "၊" (sign little section) and "။" (sign section).  
   
     ```
     မမ ဝဝ ထထ က
     အက ပထမ
     ကပါ ကပါ မမရာ
     ညည လသာသာ
    
     ကျောင်းမှန်မှန်တက်၊ စာမခက်။
     မအိပ်မနေ၊ အသက်ရှည်။
     မေးပါများ၊ စကားရ။
    
     ရန်ကုန်မှာ၊ လူများတယ်။
     နယ်မှာက၊ လူနည်းတယ်။
     ```
    
 6. Stacked words  
  
     ```
     တက္ကသိုလ်၊ မိတ္တီလာ၊ ပုပ္ပါး၊ သမ္မတ၊ ပြဿနာ၊ ပစ္စည်းများ။
     ```
   
 7. Finally, start typing some Myanmar sentences that come into your mind. You might still make some typing mistakes but keep practice. Eventually, you’ll find out that you are typing Myanmar sentences quickly and easily.  
 
   I also uploaded demo video of how to practice kKg keyboard layout:  
   
  [![video-4-1st-time-users](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/ver1/kkg-videoscreen.png)](https://youtu.be/qqNIumkvpYM)   
  
   Enjoy, kKg keyboard!  

# To-Do list
* Preparing kKg keyboard for Windows OS
* Making formal user-study when I get a chance
* Release kKg signwriting keyboard for Myanmar signers (Finished!)

# References

When I developed kKg keyboard I mainly referred man pages of XKB configuration commands and "An Unreliable Guide to XKB Configuration". I also found that there are some good references when I made a revision for the explanation of how I used XKB in Myanmar language and some of them are as follows:   

1. [XKB Homepage: https://www.x.org/wiki/XKB/](https://www.x.org/wiki/XKB/)
2. [An Unreliable Guide to XKB Configuration: https://www.charvolant.org/doug/xkb/html/xkb.html](https://www.charvolant.org/doug/xkb/html/xkb.html)  
3. [The X Keyboard Extension: https://www.x.org/releases/X11R7.7/doc/libX11/XKB/xkblib.html#Xkb_Implementation](https://www.x.org/releases/X11R7.7/doc/libX11/XKB/xkblib.html#Xkb_Implementation)  
4. [Creating custom keyboard layouts for X11 using XKB: http://michal.kosmulski.org/computing/articles/custom-keyboard-layouts-xkb.html](http://michal.kosmulski.org/computing/articles/custom-keyboard-layouts-xkb.html)  
5. [Custom keyboard layout definitions: https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions](https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions)  
6. [XkbKeyTypesForCoreSymbols (3) - Linux Man Page: https://www.systutorials.com/docs/linux/man/3-XkbKeyTypesForCoreSymbols/](https://www.systutorials.com/docs/linux/man/3-XkbKeyTypesForCoreSymbols/)
7. [Ivan Pascal's X Keyboard Extension: http://pascal.tsu.ru/en/xkb/](http://pascal.tsu.ru/en/xkb/)
8. [The X Keyboard Extension: Protocol Specification: https://www.x.org/docs/XKB/XKBproto.pdf](https://www.x.org/docs/XKB/XKBproto.pdf)
9. [Extending the X Keyboard Map with XKB: http://madduck.net/docs/extending-xkb/](http://madduck.net/docs/extending-xkb/)
10. [evdev protocol: https://who-t.blogspot.jp/2016/09/understanding-evdev.html](https://who-t.blogspot.jp/2016/09/understanding-evdev.html)
11. [Keyboard Input-Output: https://unix.stackexchange.com/questions/116629/how-do-keyboard-input-and-text-output-work](https://unix.stackexchange.com/questions/116629/how-do-keyboard-input-and-text-output-work)
12. [A Readable Reconstruction of The X Keyboard Extension Library Specification: https://grahamwideman.wikispaces.com/file/view/XKeyboardExtensionLib_GWToWord-20130613-b6.pdf](https://grahamwideman.wikispaces.com/file/view/XKeyboardExtensionLib_GWToWord-20130613-b6.pdf)

