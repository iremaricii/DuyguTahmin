# 🎭 Gerçek Zamanlı Duygu Tanıma

Bu proje, gerçek zamanlı kamera görüntüsünden yüz ifadelerini analiz ederek 7 farklı duyguyu (mutlu, üzgün, kızgın, şaşkın, nötr, korkmuş, iğrenmiş) sınıflandıran bir CNN modeline dayanmaktadır.

## 🔧 Kullanılan Teknolojiler

- Python, TensorFlow/Keras
- OpenCV (cv2)
- FER-2013 veri seti

## 🚀 Nasıl Çalıştırılır?

1. Gerekli paketleri kur:
```bash
pip install tensorflow opencv-python

Modeli eğitip kaydet:
model.save("duygu_modeli.h5")

real_time_emotion.py dosyasını çalıştır:
python real_time_emotion.py

🎥 Gerçek Zamanlı Tahmin
Kamera açılır

Yüz algılanır

Kutu içine alınır ve üzerine tahmin edilen duygu yazılır
(örneğin: Happy 😊)

![happy](https://github.com/user-attachments/assets/bb03ae40-046b-44c5-b78f-1085ee937f6d)



📁 Klasör Yapısı
📦 DuyguTahmin/
├── real_time_emotion.py
├── duygu_modeli.h5

| Etiket | Duygu       |
| ------ | ----------- |
| 0      | Angry 😠    |
| 1      | Disgust 🤢  |
| 2      | Fear 😨     |
| 3      | Happy 😄    |
| 4      | Sad 😢      |
| 5      | Surprise 😲 |
| 6      | Neutral 😐  |

