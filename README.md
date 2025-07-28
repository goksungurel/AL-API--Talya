
# 🤖 AI API Service (Text-to-Text)

Bu proje, farklı yapay zeka servis sağlayıcıları (OpenAI, Gemini, DeepSeek vb.) ile metin tabanlı sohbet gerçekleştirmek amacıyla geliştirilmiş **genel amaçlı bir API servisidir**.  
Python (Flask) ile yazılmış backend, kullanıcıdan gelen mesajı ilgili modele yönlendirir ve yanıtı standart bir formatta geri döndürür.

---

## 🧠 Projenin Amacı

- Kullanıcıdan gelen metni alıp modele iletmek  
- OpenAI ve benzeri servislerle entegre çalışmak  
- Modüler yapı sayesinde modele özel dosyalarda yönlendirme yapmak  
- Frontend’e ihtiyaç duymadan API ile AI cevapları almak

---

## 🔧 Kullanılan Teknolojiler
- Python 
- Flask  
- Requests  
- python-dotenv

---

## 📁 Proje Dosya Yapısı

ai-api-project/
├── app.py # Flask uygulaması ve /api/analyze endpoint'i

├── openai_service.py # OpenAI modeline istek atan servis

├── gemini_service.py # Gemini için 

├── deepseek_service.py # DeepSeek için 

├── .env # API anahtarları (gizli)

├── requirements.txt # Gerekli paketler

---
🛠 Geliştirme Fikirleri

Diğer AI sağlayıcıları (Gemini, DeepSeek) için entegrasyon
API loglama ve hata yönetimi
Yanıt önbellekleme (caching)
Kullanıcı kimlik doğrulama (opsiyonel)
Unit testler ve otomatik test entegrasyonu



