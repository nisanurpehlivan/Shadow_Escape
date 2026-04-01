# Shadow Escape - Android Bulmaca Oyunu

Shadow Escape, Android platformu için Java diliyle geliştirdiğim, mantık ve dikkat temelli bir kaçış oyunudur. Projenin temel amacı, kullanıcıya sürükleyici bir atmosfer eşliğinde farklı türde bulmacalar sunmak ve her odada farklı bir çözüm mekaniğiyle oyuncunun problem çözme yeteneğini test etmektir.

## Proje Vizyonu ve Tasarım
Bu projeyi geliştirirken odaklandığım ana nokta, mobil bir uygulama içerisinde oyun döngüsünü (game loop) ve kullanıcı etkileşimini doğru yönetebilmekti. Tasarım tarafında, oyuncuyu atmosferin içine çekmek için koyu tonlar ve altın sarısı (Gold) detaylar içeren özel bir görsel dil tercih ettim.

## Oyunun Yapısı ve Odalar
Oyun, birbirini takip eden ve zorluk seviyesi giderek artan 4 farklı odadan oluşmaktadır:

*   **Oda 1 (Kütüphane):** Görsel dikkat ve sayma üzerine kurulu bir başlangıç aşaması.
*   **Oda 2 (Simya Laboratuvarı):** Mantıksal eleme ve doğru renk kombinasyonlarını bulma odaklı bir bölüm.
*   **Oda 3 (Antik Şifre Odası):** Semboller ve harfler arasındaki ilişkiyi çözmeye dayalı bir kriptografi bulmacası. Bu odanın anahtarı "ISIK" kelimesidir.
*   **Oda 4 (Final):** Önceki bölümlerde elde edilen bilgilerin sentezlendiği ve tüm dikkatin toplandığı son kaçış kapısı.

## Teknik Özellikler
Uygulamanın teknik altyapısında şu teknolojiler ve yöntemler yer almaktadır:

- **Programlama Dili:** Java
- **Geliştirme Ortamı:** Android Studio
- **Arayüz:** XML tabanlı Custom Layoutlar ve Vektörel Çizimler.
- **Veri Aktarımı:** Activity'ler arası bilgi taşıma için Intent yapısı.
- **Zaman Yönetimi:** Oyuncunun performansını ölçmek için arka planda çalışan Handler tabanlı sayaç sistemi.
- **Kullanıcı Deneyimi:** İpucu (Hint) sistemi ve dinamik geri bildirim mesajları.

## Kurulum ve Çalıştırma
Projeyi kendi cihazınızda veya emülatörde test etmek isterseniz:

1. Depoyu bilgisayarınıza indirin.
2. Android Studio'yu açın ve projeyi "Open" diyerek seçin.
3. Gradle senkronizasyonunun bitmesini bekleyin.
4. Android 7.0 (API 24) ve üzeri bir cihazda uygulamayı çalıştırın.

---
Bu proje, Android geliştirme sürecindeki yetkinliklerimi sergilemek amacıyla hazırladığım kişisel bir çalışmadır.
