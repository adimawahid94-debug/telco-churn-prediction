Methodology:
Proyek ini menerapkan Machine Learning Pipeline yang komprehensif. Dimulai dengan pembersihan data otomatis menggunakan Python untuk menangani inkonsistensi pada 5 sumber data yang berbeda. Untuk menangani ketidakseimbangan kelas (class imbalance) pada target Churn, saya menerapkan teknik pembobotan kelas pada algoritma Random Forest, memastikan model tetap sensitif terhadap sinyal pelanggan yang akan pergi tanpa mengorbankan akurasi secara keseluruhan."
Key Visualizations:
Analisis visual difokuskan pada dua aspek: Interpretability (menggunakan Feature Importance untuk membedah pendorong utama churn) dan Reliability (menggunakan Confusion Matrix dan ROC Curve untuk memvalidasi performa model pada berbagai ambang batas klasifikasi)
Actionable Insights & Recommendations:
Strategi Intervensi: "Implementasi sistem flagging otomatis untuk pelanggan dengan skor kepuasan 3. Tim Customer Success disarankan melakukan soft-approach berupa survei layanan sebelum pelanggan tersebut jatuh ke kategori risiko tinggi (skor 1-2)."
Optimalisasi Revenue: "Mengingat rata-rata tagihan pelanggan churn lebih tinggi ($74.45), perusahaan harus memprioritaskan paket loyalitas pada pengguna Fiber Optic dan kontrak bulanan, yang teridentifikasi sebagai segmen paling rentan namun paling menguntungkan."
Future Works:
Eksperimen dengan algoritma Boosting (XGBoost/LightGBM) untuk mencoba melampaui skor Recall saat ini.
Penerapan teknik Hyperparameter Tuning yang lebih ekstensif menggunakan RandomizedSearchCV.
