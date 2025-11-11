# LieutenantHead - Makine İncelemesi (Three.js 3D Model İnteraktif İnceleme Aracı)

Bu proje, bir 3D modeli web üzerinde interaktif olarak inceleyebileceğiniz ve animasyonlarla detaylandırabileceğiniz bir üç boyutlu model görüntüleyicisidir. `three.js` ve `gsap` kütüphaneleriyle oluşturulmuştur.

## Özellikler

- **3D Model Görüntüleme:** GLTF formatındaki bir modeli yükler ve kullanıcıya sunar.
- **Fare ile Kontrol:** Sahneyi fareyle döndürebilir ve yakınlaştırabilirsiniz.
- **Parçala / Topla Butonları:** Modelin parçalarını animasyonla dışarı dağıtıp tekrar toplayabilirsiniz.
- **Otomatik Tur:** Kamerayı model etrafında otomatik döndürme.
- **Parça Vurgulama:** Farenizi herhangi bir parçanın üstüne getirdiğinizde o parça vurgulanır.
- **Tam Ekran Modu:** "F" tuşu ile tam ekrana geçiş desteği.
- **Responsive Tasarım:** Sahne ekran boyutuna göre otomatik olarak yeniden boyutlanır.

## Ekran Görüntüsü

> Buraya ilgili model ve arayüzden bir screenshot ekleyebilirsiniz.

## Kullanılan Kütüphaneler

- [three.js](https://threejs.org/) (Web tabanlı 3D grafik motoru)
- [GSAP](https://greensock.com/gsap/) (Animasyon kütüphanesi)
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) (Kamera kontrolü)
- [GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader) (GLTF dosya yükleyici)

## Kurulum ve Çalıştırma

1. **Projeyi Klonlayın:**
    ```bash
    git clone https://github.com/alicemalturan/threejs-model-detailing-review.git
    cd threejs-model-detailing-review
    ```

2. **Model Dosyasını Ekleyin:**
   - Proje kök dizinine `lieutenantHead.gltf` dosyasını yerleştirin (ve bağlı dosyaları, ör: tekstürler).
   - Not: Demo model yerine kendi `.gltf` dosyanızı da kullanabilirsiniz.

3. **Başlatın:**
   - Bilgisayarınızda canlı bir sunucu (VSCode Live Server vb.) kullanarak `test.html` dosyasını açın.  
   - Dosyayı doğrudan açarsanız CORS hatası alabilirsiniz; canlı sunucu önerilir.

## Nasıl Kullanılır?

- **Modeli Döndür:** Farenin sol tuşu + sürükle
- **Yakınlaştır/Uzaklaştır:** Fare tekerleği
- **Parçala:** "PARÇALA" butonuna tıkla
- **Topla:** "TOPLA" butonuna tıkla
- **Otomatik Tur:** "OTOMATİK TUR" butonuna tıkla
- **Vurgulama:** Herhangi bir parçanın üstüne fareyi getirin
- **Tam Ekran:** "F" tuşuna basın

## Dosya Yapısı
