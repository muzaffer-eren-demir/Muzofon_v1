_Tarih: 21.01.2021_

# Muzofon
## Muzofon Nedir ?
Muzofon, benim elektronik, yazılım, tasarım alanlarında kendimi geliştirmek için yaptığım proje serisidir. Adından da anlaşılacağı üzere serinin ana fikri ortaya çalışan bir _telefon_ örneği koymaktır. Telefonların nasıl özelliklere sahip olacağı benim isteğim ve becerime göre şekillenmekte. Dolayısıyla her bir telefon örneği, beni hedeflediğim alanlarda geliştirnekle beraber bu alanlardaki becerilerime de ayna tutmaktadır. Serinin tüm maddi yükü bana aittir. Tüm yazılımları, tasarımları, üretimi de kendim yapmaktayım. 

## Muzofon V1 
Telefon vaziyetinde bulunmayan ancak serinin ortaya çıkmasına neden olan ilk prototiptir. Kalbinde, kendi elektronik dükkanımızın tozlu raflarında bulduğum **Quectel M95 Rasberry Pi Shield** vardır. Bu shield normalde bir **Orange Pi One** üzerinde takılıydı ancak uygun bağlantıları bulup **Arduino Uno** ile habeleştirmeyi sağlayabildim. Daha sonra Arduino'yu aracı olarak kullanıp **Arduino IDE** seri portu üzerinden doğrudan **AT** komutları gönderip okudum. Böylece **GSM** modülüne gerekli işlemleri el ile yaptırdım.

İlgili projenin videosu: 

https://github.com/user-attachments/assets/3281eb23-7581-4666-9a08-e71e0d3f8edc

Maalesef bu projeden elimde kalan tek şey bu video.

## Bana Kattıkları:
Bu proje ile ilk defa **GSM** modülü _"Quectel M95"_ kullandım ve **AT** komutları -AT, ATD, ATH, ATA- ile tanıştım. Bu sayede işlevsel bir telefon ortaya koyma serüvenine girmiş oldum.

### O Zamanki Ben:
Bu projeyi tam olarak 21.01.2021 tahinde çalışır hale sokmuşum bu bilgiyi de videonun başlığından elde ediyorum ancak hafızamdan kalanlar ve diğer projelerimin tarihileri de buna işaret ediyor. Bu tarihte 13 yaşındaydım ve yaklaşık 1-2 yıldır bu alanla uğraşmaya başlamıştım. Maalesef o zamanlar herhangi bir yere, yaptığım projelerimin kaydını tutmadığımdan bunu seneler sonra yapıyorum. Bir projeyi bitirdiğimde hemen diğerine geçiyordum bunun için masam hiç toplu kalmıyordu. Kendi yaptığım güç kaynağı ve hoparlörde video arkaplanında gözüküyor...

Bu videoyu şimdi izleyince gördüğüm kritik hata gsm modülü anteni. O zamanlar duran dalga oranı, empedans gibi RF kavramlarından bir haber olduğumdan _ne kadar büyük anten o kadar iyi çekim gücü_ felsefesini benimsemiştim. Bunun böyle olmadığını çok sonra öğrendim... Quectel M95'e ne kadar teşekkür etsem az!
