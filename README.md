# Stock Fingerprint for Shamrock
Shamrock cihazları için Stock Fingerprint ayarlama modülü.  
Bu Magisk modülü sayesinde Stock ROM Fingerprint'e(cihaz imzasına) sahip olabilir ve Google'ın SafetyNet kontrolünden geçebilirsiniz.
SafetyNet'i geçerek de Netflix ve banka uygulamaları gibi sistem modifikasyonuna sıcak bakmayan uygulamaları sanki orijinal sistemi kullanır gibi kullanabilirsiniz.

## Uyarı
* Modülün işe yaraması ve SafetyNet'in başarılı olması için basicIntegrity kontrolünün de başarılı olması gerekmektedir. Aksi takdirde hiçbir şekilde ctsProfile kontrolü başarılı olmayacaktır.
* Her custom ROM'da işe yaramayabilir. LineageOS 14.1 2018 Ağustos sürümü ile test edilmiştir ve Netflix bile kullanabilirsiniz.

## Bilinen Sorunlar
* Bazı ROM'larda Google Play Hizmetleri tarafından sistem güncellemesinin tetiklenmesine neden olabilir fakat sistemi asla güncelleyemez. Sadece gitmeyen sinir bozucu bir bildirim bırakır :p

## İndirme
* [v1.0.1](https://github.com/omerakgoz34/shamrock-stock-fingerprint/releases/download/v1.0.1/shamrock-stock-fingerprint_v1.0.1.zip)

## Kurulum
1. Magisk'in Hide özelliğini açıp MagiskHide menüsünden com.android.vending, com.google.android.gms ve com.google.android.gsf paket adını içeren bütün uygulamar için gizlemeyi aktif edin.
2. Modülü yükleyin.
3. İlk aşamada bahsedilen uygulamaları android ayarlarından durdurup verilerini temizleyin ve hemen ardından telefonu yeniden başlatın.
4. basicIntegrity kontrolü başarılıysa muhtemelen ctsProfile ve SafetyNet de tamamen başarılı olacaktır. Modülü kaldırmak için hiçbir ekstra işleme gerek yoktur ve sisteminizde hiçbir kalıcı iz bırakmaz.
