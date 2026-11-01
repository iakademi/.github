# Katkıda Bulunma Rehberi

İ-Akademi depolarına katkı yapmayı düşündüğünüz için teşekkür ederiz. Bu rehber, katkı sürecini hızlı ve sorunsuz hale getirmek için hazırlanmıştır.

## Başlamadan Önce

- [Davranış Kuralları](CODE_OF_CONDUCT.md) belgesini okuyun; tüm etkileşimlerde geçerlidir.
- Güvenlik açığı bulduysanız herkese açık issue **açmayın**; [SECURITY.md](SECURITY.md) belgesini izleyin.
- Katkınız, ilgili deponun lisansı (aksi belirtilmedikçe MIT) altında yayımlanır.

## Katkı Türleri

- Hata bildirimi (yanlış bilgi, çalışmayan komut/kod, yazım hatası)
- İyileştirme önerisi veya yeni konu önerisi
- Dokümantasyon ve çeviri düzeltmeleri
- Yeni örnek, lab veya şablon eklemek
- Mevcut kod ve betiklerde iyileştirme

## Issue Açma

1. Önce mevcut issue'ları arayın; aynı konu açıksa oraya yorum ekleyin.
2. Depodaki issue şablonlarını kullanın (hata bildirimi veya öneri).
3. Başlığı açık yazın, adımları ve beklenen/gerçekleşen davranışı belirtin.
4. Kimlik bilgisi, parola, kişisel veri veya özel kurum bilgisi **paylaşmayın**.

## Pull Request Süreci

1. Depoyu **fork** edin ve yerel makinenize klonlayın.
2. Ana daldan yeni bir dal oluşturun:
   ```bash
   git checkout -b duzeltme/kisa-aciklama
   ```
3. Değişikliklerinizi yapın ve test edin (betikleri çalıştırın, bağlantıları kontrol edin).
4. Anlaşılır commit mesajları yazın (aşağıya bakın).
5. Dalınızı fork'unuza gönderin ve **Pull Request** açın. Açıklamada ne değiştiğini ve nedenini yazın; ilgili issue'ya `#numara` ile bağlantı verin.
6. Gözden geçirme yorumlarına yanıt verin; gerekirse güncelleyin.

Küçük PR'lar daha hızlı incelenir. Bir PR tek bir konuya odaklanmalıdır.

## Commit Mesajı Önerisi

```text
Kısa özet (50-72 karakter, emir kipi)

Gerekirse ayrıntılı açıklama: ne ve neden değişti.
```

Örnekler: `OSPF lab doğrulama komutları eklendi`, `Parola betiğinde boş girdi hatası düzeltildi`.

## İçerik Kuralları

- **Dil:** Eğitim içerikleri Türkçedir. Teknik terimlerde yaygın İngilizce karşılık parantez içinde verilebilir.
- **Doğruluk:** Komutlar ve kodlar çalıştırılarak doğrulanmalıdır. Kullanılan sürüm/platform belirtilmelidir.
- **Telif:** Telifli metin, soru bankası, sınav içeriği veya lisansı uygun olmayan materyal eklemeyin. Kaynak gösterin.
- **Güvenlik:** Eğitim içerikleri savunma ve öğrenme odaklı olmalıdır. Yetkisiz erişim, sömürü veya kötü amaçlı kullanıma yönelik içerik kabul edilmez.
- **Gizli bilgi:** Gerçek parola, anahtar, token, IP/alan adı gibi bilgileri örneklerde kullanmayın; belgelendirme için ayrılmış örnek değerleri tercih edin (örn. `example.local`, `203.0.113.0/24`).
- **Biçim:** Markdown başlıklarını düzenli kullanın; kod bloklarında dil belirtin; dosya adlarını küçük harfli, boşluksuz ve ASCII karakterlerle yazın.

## Yerel Geliştirme İpuçları

- PowerShell betikleri için `Get-Help` ile açıklama bloklarını güncel tutun.
- Python betikleri PEP 8'e uygun yazılmalıdır.
- Bash betiklerinde `set -euo pipefail` ve `shellcheck` kullanımı önerilir.

## Sorularınız mı var?

İlgili depoda bir issue açabilir veya [iakademi.com](https://iakademi.com) iletişim sayfasını kullanabilirsiniz.

Katkılarınız için teşekkürler!
