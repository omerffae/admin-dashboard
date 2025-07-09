# Admin Dashboard Projesi

Bu proje, modern ve kullanıcı dostu bir yönetim paneli uygulamasıdır. Next.js 14 kullanılarak geliştirilmiş olup, TypeScript ile yazılmıştır.


![Proje Görseli](/public/admin_dashboard.gif)  


## 🚀 Özellikler

- 📊 Modern ve duyarlı tasarım
- 🔐 Güvenli kimlik doğrulama sistemi
- 📱 Mobil uyumlu arayüz
- 📈 Veri görselleştirme ve grafikler
- 🛍️ Ürün yönetimi
- 👥 Kullanıcı yönetimi
- 🌙 Karanlık/Aydınlık tema desteği

## 🛠️ Teknolojiler

- [Next.js 14](https://nextjs.org/) - React framework
- [TypeScript](https://www.typescriptlang.org/) - Tip güvenliği
- [Tailwind CSS](https://tailwindcss.com/) - Stil ve tasarım
- [Shadcn/ui](https://ui.shadcn.com/) - UI bileşenleri
- [React Icons](https://react-icons.github.io/react-icons/) - İkonlar
- [Recharts](https://recharts.org/) - Grafikler

## 📦 Kurulum

1. Projeyi klonlayın:
```bash
git clone [https://github.com/omerffae/admin-dashboard.git]
```

2. Bağımlılıkları yükleyin:
```bash
npm install
# veya
yarn install
```

3. Geliştirme sunucusunu başlatın:
```bash
npm run dev
# veya
yarn dev
```

4. Tarayıcınızda [http://localhost:3000](http://localhost:3000) adresini açın.

## 📁 Proje Yapısı

```
src/
├── app/              # Sayfa yönlendirmeleri ve layout
├── components/       # Yeniden kullanılabilir bileşenler
│   ├── header/      # Üst menü bileşenleri
│   ├── sidebar/     # Yan menü bileşenleri
│   ├── products/    # Ürün ile ilgili bileşenler
│   ├── home/        # Ana sayfa bileşenleri
│   └── graphics/    # Grafik bileşenleri
├── utils/           # Yardımcı fonksiyonlar
├── types/           # TypeScript tip tanımlamaları
└── assets/          # Statik dosyalar
```

## 🔧 Ortam Değişkenleri

Projeyi çalıştırmak için aşağıdaki ortam değişkenlerini `.env.local` dosyasında tanımlamanız gerekmektedir:

```env
NEXT_PUBLIC_API_URL=your_api_url
```

## 📝 Kullanım

1. Giriş yapın veya hesap oluşturun
2. Sol menüden istediğiniz bölüme gidin
3. Ürünleri yönetin, grafikleri görüntüleyin veya kullanıcıları düzenleyin

## 🤝 Katkıda Bulunma

1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

## 📞 İletişim

Proje Sahibi - [@omerffae](https://twitter.com/omerffae)

Proje Linki: [https://github.com/omerffae/admin-dashboard.git](https://github.com/omerffae/admin-dashboard.git)
