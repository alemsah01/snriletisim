SNR İLETİŞİM - Bulutta Android APK oluşturma

1. Bu ZIP'i açın.
2. İçeriğini GitHub'da yeni ve PRIVATE bir repository'ye yükleyin.
3. Actions sekmesine girip "SNR Iletisim Android APK" iş akışını çalıştırın.
4. İşlem başarılı olunca workflow çalışmasının Artifacts bölümünden SNR-ILETISIM-APK dosyasını indirin.
5. ZIP içinden app-debug.apk dosyasını Android telefona aktararak kurun.

Notlar:
- APK debug imzalıdır; telefonda test ve doğrudan kurulum için uygundur.
- Uygulama arayüzü ve mevcut IndexedDB veritabanı HTML dosyasından gelir.
- Uygulama verileri telefonun uygulama alanında tutulur. Uygulamayı kaldırmak veya uygulama verilerini temizlemek kayıtları silebilir; JSON yedeği alın.
- CSV dışa aktarma, JSON geri yükleme ve yazdırma/PDF özellikleri Android WebView üzerinde ayrıca test edilmelidir.
