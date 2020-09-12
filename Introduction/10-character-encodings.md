# Character Encodings

Everything in a computer is a number. If we want to have letters in computers, we need to all agree on what number corresponds to what letter, this is called "character encoding".

> Bilgisayarın içindeki her şey bir sayıdır.

The simplest encoding is called ASCII. In ASCII, `A` is 65, `B` is 66, `&` is 38. ASCII characters are stored using only 7 bits, which means there's only 27=128 characters possible.

ASCII works fine for encoding basic English/Latin characters, but there's way more than 128 characters in the world! Unicode is the name of a system that supports up to 1,112,064 characters, which includes letters from every major alphabet, and lots of other characters like math symbols, emojis and more.

But now there's the question of how do we store these characters, how big does the "number have to be". UTF-32 is a character encoding that uses one 32 bit number for each character. This makes a lot of sense, but it wastes a lot of space. Why do we need a number big enough to hold 1,112,064 values, when most of the time we're only going to use the first 128 values.

UTF-8 is a "variable length encoding". That means a lot of the time, each character only takes up 8 bits, but it can expand to up to 32 bits if necessary. This system can support any Unicode character without wasting space, which has made it the most popular character encoding.

Now as for how this relates to webpages, when your browser gets a webpage from a server, it needs to know which encoding to use. If you don't specify anything, most browsers will default to ASCII. This is usually fine, since all characters required for html like `<` can be written in ASCII, and you can add special Unicode characters to your HTML by writing things like `&#x2660`.

### Translated Version

But if you want to include Unicode characters right in your code, then the file will be saved as UTF-8, and you will need to include a header or meta tag to tell your browser the right way to read your file.

Bir bilgisayardaki her şey bir sayıdır. Bilgisayarlarda harflerin olmasını istiyorsak, hangi sayının hangi harfe karşılık geldiği konusunda hepimiz anlaşmalıyız, buna "karakter kodlaması" denir.

En basit kodlamaya ASCII denir. ASCII'de `A` 65, `B` 66 ve 38'dir. ASCII karakterleri yalnızca 7 bit kullanılarak depolanır, yani yalnızca 27 = 128 karakter olasıdır.

ASCII, temel İngilizce / Latince karakterleri kodlamak için iyi çalışıyor, ancak dünyada 128'den fazla karakter var! Unicode, her ana alfabeden gelen harfleri ve matematik sembolleri, emojiler ve daha fazlası gibi diğer birçok karakteri içeren 1.112.064 karaktere kadar destekleyen bir sistemin adıdır.

Ama şimdi bu karakterleri nasıl saklayacağımız, "sayının" ne kadar büyük olması gerektiği sorusu var. UTF-32, her karakter için bir 32 bitlik sayı kullanan bir karakter kodlamasıdır. Bu çok mantıklı ama çok yer israf ediyor. Çoğu zaman sadece ilk 128 değeri kullanacağımız halde neden 1.112.064 değeri tutacak kadar büyük bir sayıya ihtiyacımız var?

UTF-8 bir "değişken uzunluklu kodlama" dır. Bu, çoğu zaman, her karakterin yalnızca 8 bit kapladığı anlamına gelir, ancak gerekirse 32 bite kadar genişletilebilir. Bu sistem herhangi bir Unicode karakterini alan israf etmeden destekleyebilir, bu da onu en popüler karakter kodlaması haline getirmiştir.

Şimdi bunun web sayfalarıyla nasıl ilişkili olduğuna gelince, tarayıcınız bir sunucudan bir web sayfası aldığında, hangi kodlamanın kullanılacağını bilmesi gerekir. Hiçbir şey belirtmezseniz, çoğu tarayıcı varsayılan olarak ASCII'ye geçer. Bu genellikle iyidir, çünkü `<` gibi html için gereken tüm karakterler ASCII'de yazılabilir ve HTML'nize `&#x2660` gibi şeyler yazarak özel Unicode karakterleri ekleyebilirsiniz.

Ancak, kodunuza doğrudan Unicode karakterlerini dahil etmek istiyorsanız, dosya UTF-8 olarak kaydedilir ve tarayıcınıza dosyanızı doğru şekilde okumak için bir başlık veya meta etiket eklemeniz gerekir.

---

## Useful Links
