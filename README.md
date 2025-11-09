# 🧠 ABAP WEB BLOG

SAP ABAP üzerine geliştirme notları, örnek kod parçacıkları ve kişisel deneyimlerimi paylaştığım minimal bir blog projesidir.  
Flask tabanlı olarak geliştirilmiştir ve dinamik içerik yönetimi sağlar.

---

## 🚀 Özellikler

- 📝 **Yönetici Paneli:** `/zytez` adresinden erişilebilir (gizli giriş).  
- 🔐 **Kimlik Doğrulama:** `.env` dosyasında saklanan kullanıcı adı ve şifre ile korunan admin paneli.  
- ✍️ **Zengin Metin Editörü:**  
  - Görsel ekleme  
  - Yazı biçimlendirme (bold, renk, başlık, liste vb.)  
  - Görsel boyutlandırma (resize)  
- 🗑️ **Blog Silme:** Başlığa göre blog yazılarını silebilme özelliği.  
- 🔎 **Arama:** Başlık bazlı dinamik arama özelliği.  
- 📱 **Responsive tasarım:** Mobil ve masaüstü ekranlara uyumlu.  
- 🖼️ **Animasyon ve görseller:** Lottie animasyonları ve statik varlık yönetimi (`/assets` klasörü).  

---

## ⚙️ Kurulum

Projeyi yerel ortamında çalıştırmak için:

```bash
# Sanal ortam oluştur
python -m venv .venv

# Ortamı aktif et
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# Gerekli paketleri yükle
pip install -r requirements.txt
