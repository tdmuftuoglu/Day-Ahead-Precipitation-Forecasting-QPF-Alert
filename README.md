Day-Ahead Precipitation Forecasting: QPF + Alert
Gün-Öncesi Yağış Tahmini: QPF + Uyarı
(Köyceğiz, Turkey Case Study / Köyceğiz, Türkiye Vaka Çalışması)

This repository provides a reproducible Google Colab pipeline for day-ahead precipitation forecasting using a dual-stage machine learning framework and analyzing the results with SHAP explainability. The methodology was applied in the case study of Köyceğiz, Turkey, and is associated with the scientific article:
"High-Accuracy Day-Ahead Precipitation Forecasting with an Interpretable CatBoost Regressor and a LightGBM-Based Extreme-Event Alerting Pipeline"

Bu repo, iki aşamalı bir makine öğrenmesi çerçevesi kullanarak gün-öncesi yağış tahmini yapmak ve sonuçları SHAP ile açıklanabilirlik analizi yaparak incelemek için tekrarlanabilir bir Google Colab kodu sunmaktadır. Metodoloji, Köyceğiz, Türkiye vaka çalışmasında uygulanmış olup aşağıdaki bilimsel makale ile ilişkilidir:
"High-Accuracy Day-Ahead Precipitation Forecasting with an Interpretable CatBoost Regressor and a LightGBM-Based Extreme-Event Alerting Pipeline"

How to Use (Google Colab) / Nasıl Kullanılır?
This project is designed for one-click execution in Google Colab.
Bu proje, Google Colab'de tek tıkla çalışacak şekilde tasarlanmıştır.

Open the Notebook: Open KoycegizPrecipExtended.ipynb in Google Colab.

Not Defterini Açın: KoycegizPrecipExtended.ipynb dosyasını Google Colab'de açın.

Run All Cells: In the Colab interface, navigate to Runtime → Run all.

Tüm Hücreleri Çalıştırın: Colab arayüzünde Çalışma Zamanı → Tümünü çalıştır seçeneğini seçin.

Automatic Data Processing: The script will automatically download and preprocess the NASA POWER dataset (2001–2024).

Otomatik Veri İşleme: Kod, NASA POWER veri setini (2001–2024) otomatik olarak indirecek ve ön işlemlerden geçirecektir.

Download Results: All diagnostic plots, metric tables, and SHAP analyses will be generated automatically.

Sonuçları İndirin: Tüm tanı grafikleri, metrik tabloları ve SHAP analizleri otomatik olarak oluşturulacaktır.

Repository Structure / Repo Yapısı
KoycegizPrecipExtended.ipynb → The Google Colab notebook containing the complete end-to-end pipeline. / Uçtan uca tüm adımları içeren Google Colab not defteri.

LICENSE → The MIT License file. / MIT Lisans dosyası.

README.md → This documentation file. / Bu dokümantasyon dosyası.

Outputs / Üretilen Çıktılar
The script automatically generates the following files:
Kod, aşağıdaki dosyaları otomatik olarak üretir:

Correlation Heatmaps and Time Series / Korelasyon Isı Haritaları ve Zaman Serileri

Regression and Classification Performance Plots / Regresyon ve Sınıflandırma Performans Grafikleri (R², F1-Score, Confusion Matrix)

SHAP Explainability Figures / SHAP Açıklanabilirlik Grafikleri

Descriptive Statistics and Metric Tables / Tanımlayıcı İstatistikler ve Metrik Tabloları

Citation / Atıf
If you use this code in your research, please cite the repository:
Bu kodu araştırmalarınızda kullanırsanız, lütfen repoya atıfta bulunun:

Muftuoglu, T. D. (2025). High-Accuracy Day-Ahead Precipitation Forecasting with an Interpretable CatBoost Regressor and a LightGBM-Based Extreme-Event Alerting Pipeline. GitHub Repository. https://github.com/tdmuftuoglu/Day-Ahead-Precipitation-Forecasting-QPF-Alert

Author / Yazar
Dr. Tevfik Denizhan Müftüoğlu

License / Lisans
This project is licensed under the MIT License. You are free to use, modify, and distribute it, provided the original author attribution is maintained.

Bu proje MIT Lisansı altında lisanslanmıştır. Orijinal yazar atfı korunduğu sürece kodu kullanmakta, değiştirmekte ve dağıtmakta serbestsiniz.
