# Wearther Gizlilik Politikası

Wearther; hava durumuna ve gardıroba göre günlük kombin önerisi sunan bir uygulamadır.
Bu politika, hangi verilerin toplandığını, nasıl kullanıldığını ve haklarınızı açıklar.

**Son güncelleme:** 2026-05-14

---

## Toplanan veriler

| Veri | Amaç | Zorunlu mu? |
|------|------|------------|
| E-posta adresi ve kullanıcı kimliği | Hesap yönetimi | Evet |
| Kullanıcının oluşturduğu gardırop kayıtları | Kombin önerileri | Evet |
| Kombin geçmişi (ne zaman ne giyildi) | Kıyafet yıkama takibi, öneri iyileştirme | Evet |
| Konum (GPS veya manuel şehir) | Anlık hava durumu verisi çekmek | Hayır — isteğe bağlı |

Konum verisi yalnızca hava durumu API'sine koordinat göndermek için kullanılır;
cihazdaki ham konum kaydedilmez veya üçüncü taraflarla paylaşılmaz.

---

## Verilerin kullanımı

Toplanan tüm veriler yalnızca uygulama işlevselliği için kullanılır:
- Oturum açmış kullanıcıya ait gardırop verilerini senkronize etmek
- Yerel hava durumunu çekmek
- Kişiselleştirilmiş kombin önerileri üretmek

Veriler başka amaçlarla (reklam, profilleme, üçüncü taraf satışı) kullanılmaz.

---

## Üçüncü taraf hizmetler

- **Firebase Authentication** (Google LLC) — kimlik doğrulama
- **Cloud Firestore** (Google LLC) — gardırop ve ayar verilerinin bulutta saklanması
- **Google Sign-In** (Google LLC) — Google hesabıyla giriş seçeneği
- **Open-Meteo** — konum koordinatından hava durumu verisi çekme (kişisel veri iletilmez)

Firebase ve Google gizlilik politikası: https://policies.google.com/privacy

---

## Veri saklama ve silme

- Verileriniz, hesabınız aktif olduğu sürece saklanır.
- **Hesap silme:** Ayarlar ekranındaki "Hesabı sil" seçeneğiyle tüm kişisel
  verilerinizi (gardırop, kombin geçmişi, ayarlar) kalıcı olarak silebilirsiniz.
- Tek tek kıyafet kayıtlarını Gardırop ekranından istediğiniz zaman silebilirsiniz.

---

## İletişim

Gizlilik politikasıyla ilgili sorularınız için: **[DESTEK E-POSTASI EKLEYİN]**

---

> **Not:** Bu belge, Play Store yüklemesinden önce gerçek bir URL üzerinde
> yayınlanmalıdır (GitHub Pages, Notion veya herhangi bir statik sayfa).
> Yayın URL'sini hem Play Console'a hem de uygulamadaki gizlilik politikası
> linkine girmeyi unutmayın.
