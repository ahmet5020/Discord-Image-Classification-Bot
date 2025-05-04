# 🐱 Görsel Sınıflayıcı Discord Botu

Bu proje, kullanıcıların Discord üzerinden kedi fotoğrafları göndererek onların cinsini sınıflandırmasına ve uygun mama önerisi almasına olanak tanıyan bir yapay zeka botudur.

## 🚀 Özellikler

- Kullanıcıdan gelen görselleri analiz eder.
- Kedi türünü (tekir, sarman, british) tanımlar.
- Her tür için uygun bir mama önerisi sunar.
- Görselleri otomatik olarak yerel klasöre kaydeder.

## 🧠 Yapay Zeka

Bot, önceden eğitilmiş bir `keras_Model.h5` dosyası kullanır. Bu model, kedi görsellerini sınıflandırmak için eğitilmiştir. `labels.txt` dosyası ise sınıf adlarını içerir:

0 tekir
1 sarman
2 british

perl
Kopyala
Düzenle

## 🔧 Kurulum

```bash
pip install -r requirements.txt
python main.py
Alternatif olarak pipenv ile:

bash
Kopyala
Düzenle
pipenv install
pipenv shell
python main.py

.
├── keras_Model.h5
├── labels.txt
├── main.py
├── README.md
└── images/

---

### 📎 Ekstra: `LICENSE` (MIT örneği)

```text
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...