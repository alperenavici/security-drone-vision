security-drone-vision/
│── dataset/                   # Veri setleri (etiketlenmiş veriler, test/geliştirme verileri)
│── models/                    # Eğitilmiş modeller ve model ağırlıkları
│── src/                       # Ana kodlar
│   ├── detection/             # Nesne tespiti kodları (YOLO, OpenCV vb.)
│   ├── tracking/              # Hareket izleme algoritmaları
│   ├── preprocessing/         # Veri ön işleme (görüntü temizleme, artırma)
│   ├── integration/           # Drone ile entegrasyon kodları (MAVLink, RTSP vb.)
│   ├── mobile_interface/      # Mobil uygulama ile bağlantı (WebSocket, MQTT)
│── notebooks/                 # Araştırma ve test için Jupyter Notebook dosyaları
│── configs/                   # Konfigürasyon dosyaları (model parametreleri, ağ bağlantıları)
│── logs/                      # Model eğitimi ve hata ayıklama logları
│── tests/                     # Test ve doğrulama kodları
│── docs/                      # Teknik dökümantasyon (proje planı, kullanım kılavuzu)
│── requirements.txt           # Bağımlılıkların listesi (OpenCV, TensorFlow, PyTorch vb.)
│── README.md                  # Proje açıklaması, kurulum ve kullanım talimatları
│── .gitignore                 # Gereksiz dosyaları hariç tutma