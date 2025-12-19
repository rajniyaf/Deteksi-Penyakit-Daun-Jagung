# Deteksi-Penyakit-Daun-Jagung
Deteksi penyakit daun jagung dilakukan dengan dua model yang berbeda yakni YOLO + ViT dan YOLO + CNN.

Dataset yang digunakan dalam percobaan ini didapatkan dari Open Science Framework melalui laman https://osf.io/s6ru5/overview. Dataset selanjutnya dilakukan pre-procesing dengan augmementasi citra, pengubahan kelas untuk YOLO, croping untuk ViT dan CNN. Selanjutnya dilakukan pelatihan model dengan kode Pelatihan_Model yang dijalankan pada kaggle menggunakan GPU T4 x2 serta menginstall environment 
!pip install ultralytics
!pip install torch torchvision torchaudio pandas openpyxl scikit-learn
Setelah mendapatkan model terbaik, model disimpan dan dilakukan pengujian dengan kode Pengujian pada google colab.
