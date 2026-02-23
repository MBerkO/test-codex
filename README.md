# Proje Vitrini

Bu repo, web projelerini tek bir yerde **barındırmak ve sergilemek** için hazırlanmış sade bir vitrin arayüzüdür.

## Mevcut projeler
- `kartvizit.html` → Minimalist dijital kartvizit sayfası
- `pdf-konu-bolucu.html` → Yapay zekâ destekli PDF konu başlığına göre bölme planı üreten sayfa (demo)

## Vitrin özellikleri
- Hero alanı ve proje istatistikleri
- Karanlık / açık tema geçişi
- JS içindeki proje listesinden dinamik kart üretimi
- Kategoriye göre filtreleme
- Etiket ve toplam proje sayısı gösterimi

## Nasıl proje eklerim?
`index.html` içindeki `projects` dizisine yeni obje eklemen yeterlidir:

```js
{
  name: "Yeni Proje",
  description: "Proje açıklaması",
  stack: ["Teknoloji", "Teknoloji"],
  status: "Devam ediyor",
  link: "https://ornek.com",
  category: "Landing"
}
```

## Yerelde çalıştırma
```bash
python3 -m http.server 4173
```

Sonrasında `http://localhost:4173` adresini ziyaret et.
