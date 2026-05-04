# 🛒 WiStore — React Alışveriş Uygulaması

> ✅ **Bu proje herhangi bir yapay zeka aracı kullanılmadan, tamamen insan tarafından geliştirilmiştir.**

WiStore, [Fake Store API](https://fakestoreapi.com/) kullanarak ürünleri kategorilere göre listeleyen, React ile geliştirilmiş bir e-ticaret ön yüz uygulamasıdır.

---

## 📸 Ekran Görüntüleri

**Elektronik Kategorisi**

![WiStore Electronics](./screenshot-electronics.png)

![WiStore Electronics - Devamı](./screenshot-electronics-2.png)

**Mücevher Kategorisi**

![WiStore Jewelery](./screenshot-jewelery.png)

---

## 🚀 Özellikler

- **Kategori bazlı ürün listeleme** — Sol panelden seçilen kategoriye göre ürünler dinamik olarak güncellenir
- **Canlı API entegrasyonu** — Kategoriler ve ürünler Fake Store API'den gerçek zamanlı çekilir
- **Bileşen tabanlı mimari** — Header, Footer, SideBar, Products, ProductList ve Product bileşenleriyle modüler yapı
- **React Hooks** — `useState` ve `useEffect` ile yönetilen state ve yan etkiler
- **Axios** ile HTTP istekleri
- **Vitest + Testing Library** ile birim testler

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Versiyon |
|-----------|----------|
| React | 18 |
| Vite | 5 |
| Axios | 1.6 |
| Vitest | 1.1 |
| @testing-library/react | 14 |
| ESLint | 8 |

---

## 📁 Proje Yapısı

```
src/
├── components/
│   ├── Header.jsx        # Üst başlık
│   ├── Footer.jsx        # Alt bilgi
│   ├── SideBar.jsx       # Kategori paneli
│   ├── CategoryList.jsx  # Kategori listesi
│   ├── Category.jsx      # Tekil kategori öğesi
│   ├── Products.jsx      # Ürün alanı (API çağrısı)
│   ├── ProductList.jsx   # Ürün listesi
│   ├── Product.jsx       # Tekil ürün kartı
│   └── Layout.css        # Genel düzen stilleri
├── App.jsx               # Ana bileşen
├── main.jsx              # Uygulama giriş noktası
└── index.css             # Global stiller
```

---

## ⚙️ Kurulum ve Çalıştırma

```bash
# Bağımlılıkları yükle
npm install

# Geliştirme sunucusunu başlat
npm run dev

# Testleri çalıştır
npm test

# Geliştirme sunucusu ve testleri aynı anda çalıştır
npm run wit
```

---

## 🔌 API

Uygulama [Fake Store API](https://fakestoreapi.com/) kullanmaktadır.

| Endpoint | Açıklama |
|----------|----------|
| `GET /products/categories` | Tüm kategorileri getirir |
| `GET /products/category/:name` | Kategoriye ait ürünleri getirir |

---

## 📝 Lisans

Bu proje eğitim amaçlı geliştirilmiştir.
