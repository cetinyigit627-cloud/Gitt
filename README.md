# Cyber Runner 2D

Flutter + Flame ile geliştirilmiş 2D oyun.

## GitHub Actions ile APK oluşturma

1. Bu klasörün içeriğini (klasörün kendisini değil) GitHub'da yeni bir repository'ye yükleyin.
2. GitHub repository'sinde **Actions** sekmesine girin.
3. `Build Cyber Runner Android APK` iş akışının çalışmasını bekleyin. Otomatik başlamazsa **Run workflow** seçeneğini kullanın.
4. Başarılı çalışmanın sayfasında **Artifacts** bölümünden `cyber-runner-release-apk` dosyasını indirin.
5. ZIP'i açın; içindeki `app-release.apk` dosyası Android telefona kurulabilir.

İş akışı, eksik Android platform dosyalarını ve Gradle Wrapper'ı GitHub Actions üzerinde Flutter ile yeniden üretir. APK debug anahtarıyla imzalanır; Google Play yayını için ayrıca kendi release imzalama anahtarınız gerekir.
