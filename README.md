# ForWork - Günlük İş Planlama Uygulaması

Bu uygulama, günlük işlerinizi planlamak ve takip etmek için basit bir araçtır. Günlük, haftalık, aylık ve yıllık görevleri yönetebilirsiniz.

## Özellikler

- **Görev Ekleme**: Tarih ve saat seçerek görev ekleyin
- **Not Ekleme**: Görevlere opsiyonel notlar ekleyin
- **Kategoriler**: Bugün, Bu Hafta, Bu Ay, Bu Yıl olarak görevleri görüntüleyin
- **Tamamlama**: Görevleri tamamlandı olarak işaretleyin
- **Silme**: Gereksiz görevleri silin
- **Veri Saklama**: Görevler tarayıcıda yerel olarak saklanır

## Kullanım

### Web Sitesi Olarak

1. Projeyi klonlayın
2. `npm install` ile bağımlılıkları yükleyin
3. `npm run dev` ile geliştirme sunucusunu başlatın
4. Tarayıcıda http://localhost:5173 adresine gidin

### Masaüstü Uygulaması Olarak

1. `npm run build` ile uygulamayı build edin
2. `npm run electron` ile masaüstü uygulamasını çalıştırın

### Geliştirme

- `npm run electron-dev`: Hem Vite dev server hem Electron'u birlikte çalıştırır

## Teknolojiler

- React 19
- Vite
- Electron
- LocalStorage (veri saklama)
