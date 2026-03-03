# LieutenantHead - Gelişmiş 3D Model İnceleme (Three.js)

Bu proje, web üzerinde profesyonel seviye 3D model inceleme deneyimi sağlamak için geliştirilmiş modern bir Three.js görüntüleyicisidir.

## Sunulan Özellikler

### 1) Temel Etkileşim ve Görüntüleme
- 360° döndürme, kaydırma (pan) ve yakınlaştırma (zoom)
- Otomatik döndürme (auto-rotate)
- Tek tıkla standart bakış açıları (ön / arka / yan / üst)
- Poster benzeri yükleme ekranı ve ilerleme çubuğu

### 2) Teknik ve Görsel Kalite
- PBR malzeme yaklaşımı (MeshStandardMaterial)
- Aydınlatma ve gölge yoğunluğu kontrolü
- HDR/IBL ortam seçimi (venice/studio)
- GLTF / GLB / OBJ / STL format desteği
- Ölçüm aracı (iki nokta arası mesafe)
- Kesit alma (section plane) slider
- Draco + Meshopt desteği (GLTF/GLB için)

### 3) UX ve Gelişmiş Özellikler
- AR ile görüntüleme butonu (Android Scene Viewer akışı)
- Gömülü animasyonları oynat/durdur + hız ayarı
- Hotspot bilgi noktaları
- Varyant seçici (renk değiştirme)

## Çalıştırma

```bash
python3 -m http.server 4173
```

Ardından:

- `http://localhost:4173/test.html`

## Kullanım Notları

- Varsayılan model: `lieutenantHead.gltf`
- Alt panelden farklı formatta model dosyası seçerek canlı yükleme yapabilirsiniz.
- Mobilde AR için Android + Scene Viewer uyumlu tarayıcı gerekir.
