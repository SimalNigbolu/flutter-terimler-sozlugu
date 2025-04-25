# 📘 Flutter & Dart Terimler Sözlüğü

Flutter öğrenme sürecinde karşımıza çıkan tüm temel, orta ve ileri seviye kavramları içeren kapsamlı bir sözlük.

---

## 🔤 Temel Flutter & Dart Terimleri

- **String**: Metin  
- **int**: Sayı (tam sayı)  
- **double**: Ondalıklı sayı  
- **bool**: Doğru/yanlış (true/false)  
- **var**: Değişkenin türünü Dart'ın otomatik belirlemesini sağlar  
- **dynamic**: Her tür veriyi alabilen esnek tür  
- **const**: Derleme zamanında sabit olan değer  
- **final**: Çalışma zamanında belirlenen ama değiştirilemeyen değer  
- **Widget**: Flutter’daki her şeyin yapı taşı (UI elemanı)  
- **StatelessWidget**: Değişmeyen (sabit) arayüz  
- **StatefulWidget**: Değişebilen (dinamik) arayüz  
- **State**: Stateful widget’ın durumunu (değişken verisini) yöneten yapı  
- **setState()**: Stateful widget’ın güncellenmesini sağlar  
- **BuildContext**: Widget’ın yer aldığı konum, bağlam  
- **build()**: Widget ağacını oluşturan metod  
- **MaterialApp**: Material Design tabanlı uygulama başlatıcı widget  
- **Scaffold**: Sayfa iskeleti (AppBar, body, vs.)  
- **AppBar**: Uygulamanın üst kısmındaki bar (başlık çubuğu)  
- **body**: Sayfanın ana içeriği  
- **Column**: Dikey hizalama  
- **Row**: Yatay hizalama  
- **Container**: Kutu gibi alan, genişlik/yükseklik/margin/padding verebilir  
- **Padding**: İç boşluk  
- **Margin**: Dış boşluk  
- **Text**: Metin gösterir  
- **TextField**: Kullanıcıdan metin girişini alır  
- **TextEditingController**: TextField verisini kontrol eder  
- **ElevatedButton**: Yükseltilmiş buton  
- **IconButton**: Simgeli buton  
- **FloatingActionButton**: Uçan buton (genelde sağ altta)  
- **Navigator**: Sayfalar arasında geçiş sağlar  
  - **push()**: Yeni sayfa açar  
  - **pop()**: Sayfayı kapatır  
- **ListView**: Kaydırılabilir liste  
- **ListTile**: Liste elemanı  
- **Expanded**: Boş alanı kaplayan widget  
- **Flexible**: Esnek yer kaplayan widget  
- **GestureDetector**: Dokunma, tıklama gibi hareketleri algılar  
  - **onTap**: Dokunma olayı  
- **Future**: Gelecekte dönecek veri (asenkron işlem)  
- **async**: Asenkron fonksiyon tanımlayıcı  
- **await**: Asenkron fonksiyonu bekler  
- **FutureBuilder**: Gelecekte gelen veriye göre widget çizer  
- **Stream**: Sürekli veri akışı  
- **StreamBuilder**: Stream’e göre widget çizer  
- **Provider**: Durum yönetimi için kullanılan bir paket  
- **ChangeNotifier**: Değişiklikleri dinleten sınıf  
- **Consumer**: Değişiklikleri dinleyip arayüzü günceller  
- **ThemeData**: Tema ayarları (renk, yazı tipi vb.)  
- **Color**: Renk  
- **EdgeInsets**: Boşlukları (margin/padding) tanımlar  
- **MediaQuery**: Ekran boyut bilgilerine ulaşmak için kullanılır  
- **SafeArea**: Ekrandaki çentik vs. alanlardan korur  
- **SizedBox**: Sabit boyutlu boş alan  
- **Navigator 2.0**: Yeni nesil yönlendirme sistemi  
- **GoRouter**: Yeni nesil sayfa yönlendirme paketi  
- **Assets**: Uygulama içi dosyalar (resim, ses vb.)  
- **pubspec.yaml**: Paketleri, asset’leri yönettiğimiz dosya  
- **hot reload**: Kodda yapılan değişiklikleri kaydetmeden anlık yansıtma  
- **hot restart**: Kod değişikliğini baştan ama durumu sıfırlayarak başlatma  
- **main()**: Uygulamanın başladığı yer  
- **runApp()**: Uygulamanın çalıştırılması  
- **Null Safety**: Değişkenlerin null olup olmadığını kontrol etme sistemi  
  - **required**: Zorunlu parametre  
  - **late**: Sonradan atanacak ama null olmayacak değişken  
  - **?** (soru işareti): Null olabilen tür  
  - **!** (ünlem): “Bu null değil, eminim” anlamı  
- **DartPad**: Online Dart editörü  
- **flutter.dev**: Flutter’ın resmi sitesi  

---

## 🧩 Flutter Orta & İleri Seviye Terimler

- **async**: Asenkron fonksiyon tanımı  
- **await**: Asenkron işlemi bekleme  
- **Future**: Gelecekte dönecek veri tipi  
- **Stream**: Sürekli veri akışı  
- **StreamController**: Akışı kontrol eden yapı  
- **StreamBuilder**: Stream verisine göre arayüzü yeniden çizme  
- **Navigator**: Sayfalar arası geçiş yöneticisi  
  - **push()**: Yeni sayfaya geçiş  
  - **pop()**: Sayfadan geri dönüş  
  - **pushReplacement()**: Mevcut sayfanın yerine yeni sayfa açma  
  - **pushNamed()**: İsimle sayfa açma (route sistemi)  
  - **PageRouteBuilder**: Özel sayfa geçiş animasyonları  
- **MediaQuery**: Ekran boyutlarını ölçmek için  
- **LayoutBuilder**: İçeriğe göre boyutlandırma sağlar  
- **OrientationBuilder**: Dikey/yatay yön algılayıcı  
- **AspectRatio**: Genişlik-yükseklik oranı belirler  
- **Expanded**: Tüm boş alanı kaplayan widget  
- **Flexible**: Esnek genişlikte widget  
- **Form**: Form alanı  
  - **TextFormField**: Form için metin alanı  
  - **validator**: Doğrulama fonksiyonu  
- **GlobalKey**: Formu yönetmek için anahtar  
- **shared_preferences**: Kalıcı küçük veriler için kullanılan paket  
- **hive**: NoSQL tabanlı hızlı veritabanı  
- **sqflite**: SQLite tabanlı klasik veritabanı  
- **moor (drift)**: Modern SQLite ORM (Object Relation Mapping)  
- **http**: API'den veri çekmek için kullanılan paket  
- **Dio**: Gelişmiş HTTP istek kütüphanesi  
- **jsonDecode**: JSON verisini Dart nesnesine çevirme  
- **jsonEncode**: Dart nesnesini JSON’a çevirme  
- **Model**: Verileri temsil eden sınıf  
  - **fromJson**: JSON’dan model üretir  
  - **toJson**: Modeli JSON’a çevirir  
- **CustomPainter**: Özel çizim yapmayı sağlar  
- **Canvas**: Çizim alanı  
- **Paint**: Renk, fırça vs. ayarları  
- **Path**: Çizgi, eğri, şekil oluşturma  
- **Tween**: Değerler arasında geçiş yapar  
- **AnimationController**: Animasyonun süresi ve kontrolü  
- **AnimatedBuilder**: Animasyonla widget oluşturur  
- **AnimatedContainer**: Otomatik animasyonlu container  
- **Hero**: Sayfalar arası geçiş animasyonu  
- **Curve**: Animasyonun eğrisi (örnek: Curves.easeInOut)  

---

## 🕵️‍♀️ İleri Seviye, Az Bilinen Ama Çok İşe Yarayacak Flutter Terimler

- **InheritedWidget**: Widget ağında veri aktarmak için temel yapı  
- **InheritedModel**: Aynı verinin sadece belirli parçalarının değişiminde yeniden çizim sağlar  
- **Builder**: Yeni context üretmek için kullanılır  
- **GlobalKey**: Widget'lara global erişim sağlar  
- **FocusNode**: Klavye odaklanması için kontrol noktası  
- **FocusScopeNode**: Birden fazla odak noktası arasında geçiş yapmayı sağlar  
- **Ticker**: Animasyonların zamanlayıcısı  
- **SingleTickerProviderStateMixin**: Tek animasyon kontrolcüsü sağlar  
- **TickerProviderStateMixin**: Birden fazla animasyon sağlayıcısı  
- **WillPopScope**: Geri tuşuna basıldığında özel işlem yapar  
- **ReorderableListView**: Sürükle bırakla sıralama yapılabilen liste  
- **Draggable / DragTarget**: Sürüklenebilir widgetlar  
- **GestureDetector**: Dokunma, kaydırma, çift tıklama gibi etkileşimleri algılar  
- **Listener**: Düşük seviyeli dokunma olaylarını algılar  
- **RawGestureDetector**: Kendi özel dokunma tanımlarını yazmak için  
- **SliverAppBar**: Scroll edince küçülüp büyüyen app bar  
- **SliverList**: Daha performanslı scroll listesi  
- **SliverGrid**: Sliver yapısında grid gösterimi  
- **CustomScrollView**: Sliver'ları birleştirip özel scroll yapısı sağlar  

---

## 🔑 Value & Key Yönetimi

- **ValueNotifier**: Küçük veriler için mini bir state yönetimi  
- **ValueListenableBuilder**: ValueNotifier dinleyicisi  
- **Extension**: Dart’ta mevcut sınıflara yeni fonksiyonlar eklemeye yarar  
- **Mixin**: Birden fazla sınıftan özellik miras almak için kullanılır  
- **Keys**: Widget'lara özel kimlik verir  
  - **UniqueKey()**: Her seferinde yeni key üretir  
  - **ValueKey()**: Belirli bir değere göre key verir  

---

## 🧠 Diğer Paketler & Araçlar

- **flutter_bloc_test**: Bloc yapıları için test paketi  
- **mockito**: Sahte veri ve nesne oluşturmak için kullanılır (testlerde)  
- **flutter_hooks**: React tarzı mantıklar ekler  
  - **useState**: Widget içinde state tutar  
  - **useEffect**: Yan etkiler tanımlar  
- **flutter_local_notifications**: Yerel bildirimler  
- **firebase_messaging**: Firebase ile push bildirim  
- **Responsive**: Ekran boyutuna duyarlı tasarım  
- **flutter_screenutil**: Pixel/dp/pt uyumlu boyutlama paketi  
- **AssetImage**: Uygulama içindeki görseli gösterir  
- **NetworkImage**: İnternetten görsel getirir  
- **CachedNetworkImage**: Görseli cache’le gösterir  
- **FadeInImage**: Görsel yüklenene kadar placeholder gösterir  
- **flutter_svg**: SVG formatlı görsel gösterme  
- **file_picker**: Dosya seçici  
- **image_picker**: Kamera ya da galeriden görsel seçme  
- **path_provider**: Uygulama klasörlerine erişim  

---

## 🧪 Test & Debug

- **Unit Test**: Fonksiyonları test etme  
- **Widget Test**: Arayüz testleri  
- **Integration Test**: Tüm uygulama testleri  
- **debugPrint()**: Uzun metinleri bile bölmeden yazdırır  
- **assert()**: Hata ayıklama için doğrulama  
- **Flutter DevTools**: Performans, log ve hata analiz aracı  

---
