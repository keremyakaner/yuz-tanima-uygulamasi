# Yüz Tanıma Sistemi

## 📜 Proje Hakkında

Bu proje, Python kullanarak Tkinter, `face_recognition` ve `opencv-python` kütüphaneleriyle geliştirilmiş bir yüz tanıma sistemini içermektedir. Uygulama, birden fazla kişinin yüzünü tanıyabilir ve kullanıcılar fotoğraf yükleyerek yüzlerini tanıttıktan sonra gerçek zamanlı video akışında yüz tanıma yapabilirler. Ayrıca sesli geri bildirim ve tanıma geçmişi de sistemde yer almaktadır.

## 🎯 Proje Amacı

Bu projenin amacı:
- Python’da Tkinter kütüphanesi ile kullanıcı arayüzü oluşturabilmek.
- `face_recognition` ve `opencv-python` kütüphanelerini kullanarak yüz tanıma işlemi gerçekleştirmek.
- Tkinter ile arayüzü entegre ederek, kullanıcı dostu bir yüz tanıma uygulaması geliştirmektir.

## ⚙️ Gereksinimler

Projeyi çalıştırabilmek için aşağıdaki Python kütüphanelerine ihtiyacınız olacak:
- `tkinter` - Kullanıcı arayüzü için.
- `face_recognition` - Yüz tanıma işlemleri için.
- `opencv-python` - Video işleme için.
- `Pillow` (PIL) - Görüntü işleme için.
- `pyttsx3` - Sesli yanıt için.

## 🔧 Kütüphane Yükleme

1. Gerekli kütüphaneleri yüklemek için aşağıdaki komutları kullanabilirsiniz:
```bash 
pip install tkinter
pip install face_recognition
pip install opencv-python
pip install pillow
pip install pyttsx3
``` 
## 🚀 Projeyi Çalıştırma
1. Proje dosyasını bilgisayarınıza indirin.
2. Terminal veya Komut İstemcisi’ni açın ve proje klasörüne gidin.
3. Aşağıdaki komutla uygulamayı başlatın:

```bash
python face_recognition_app.py
```

## 🖥️ Kullanıcı Arayüzü Özellikleri
- Yüz Tanıt (Resim Yükle): Kullanıcı, bir fotoğraf yükleyerek yüzünü sisteme tanıtır.
- Kamerayı Başlat: Kamerayı açarak gerçek zamanlı yüz tanıma işlemi yapılır.
- Yüz Tanı: Gerçek zamanlı videoda tanınan kişileri ekranda gösterir.
- Çıkış: Uygulamayı kapatır.

## 📁 Proje Yapısı
Proje klasörü içinde şu dosyalar bulunur:
- yuz-tanima.py — Ana Python dosyası
- Elon.jpg — Örnek yüz fotoğrafı
- yuz_tanima_video/ — Örnek proje videosu (Klasör)
- README.md — Proje açıklamaları

