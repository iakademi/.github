# Güvenlik Politikası

İ-Akademi depolarının güvenliğine önem veriyoruz. Bu belge, bir güvenlik açığını nasıl bildirebileceğinizi açıklar.

## Desteklenen İçerik

Depolarımız eğitim materyali, örnek kod, şablon ve betik içerir. Genel olarak her deponun **varsayılan (main) dalındaki güncel içerik** için bildirimleri değerlendiririz. Eğitim amaçlı örneklerdeki güvenlik zafiyetleri (ör. güvensiz bir komut, açıkta kalmış sır, hatalı yapılandırma önerisi) de bildirime değerdir.

## Güvenlik Açığı Bildirimi

**Lütfen güvenlik açıklarını herkese açık issue, pull request veya tartışma olarak paylaşmayın.**

Bildirim yolları:

1. **GitHub özel güvenlik açığı bildirimi (tercih edilen):** İlgili deponun **Security** sekmesinde **Report a vulnerability** bağlantısını kullanın. Bu seçenek yalnızca depoda etkinse görünür.
2. **İletişim sayfası:** GitHub üzerinden bildirim yapamıyorsanız [iakademi.com](https://iakademi.com) sitesindeki iletişim sayfasından bize ulaşın ve ayrıntıları paylaşmadan önce güvenli bir iletişim yöntemi isteyin.

## Bildirimde Neler Bulunmalı?

- Etkilenen depo, dosya ve (varsa) satır veya commit bilgisi
- Sorunun açıklaması ve olası etkisi
- Yeniden üretme adımları veya kanıt (hassas veri içermeyecek şekilde)
- Önerilen çözüm (varsa)

## Süreç

- Bildirimi aldığımızı teyit etmeye ve değerlendirmeye çalışırız.
- Geçerli bulunan sorunlar düzeltilir veya içerik güncellenir; gerektiğinde bildirimde bulunan kişiyle iletişim kurulur.
- Düzeltme yayımlanana kadar ayrıntıların gizli tutulmasını rica ederiz (koordineli açıklama).
- Bildirimde bulunanlara, talep etmeleri halinde, teşekkür bölümünde yer verebiliriz.

## Kapsam Dışı

- Üçüncü taraf hizmetlerdeki veya bu depolarla ilgisi olmayan sistemlerdeki sorunlar
- Hizmet reddi, sosyal mühendislik veya fiziksel saldırı testleri
- Yetkisiz sistemlere yönelik testler: Yalnızca kendi sahip olduğunuz ya da test izniniz bulunan sistemlerde araştırma yapın

## Hassas Bilgi Paylaşımı

Depolara asla gerçek parola, anahtar, token veya kişisel veri eklemeyin. Yanlışlıkla eklenmiş bir sır fark ederseniz yukarıdaki yollarla bildirin; sır ifşa olmuş kabul edilip yenilenmelidir.
