# Proyek Model Regresi: Prediksi Kinerja Akademik Siswa

Proyek ini bertujuan untuk menganalisis dan memprediksi kinerja akademik siswa berdasarkan berbagai faktor seperti kebiasaan belajar, gaya hidup, dan latar belakang mereka. Dengan menggunakan model regresi, kita dapat memahami faktor-faktor mana yang paling berpengaruh terhadap skor ujian siswa.

## Dataset

Dataset yang digunakan dalam proyek ini adalah `student_habits_performance.csv`. Dataset ini berisi informasi berikut:

* **student_id**: ID unik untuk setiap siswa
* **age**: Usia siswa
* **gender**: Jenis kelamin siswa
* **study_hours_per_day**: Jam belajar per hari
* **social_media_hours**: Jam penggunaan media sosial per hari
* **netflix_hours**: Jam menonton Netflix per hari
* **part_time_job**: Apakah siswa memiliki pekerjaan paruh waktu (Ya/Tidak)
* **attendance_percentage**: Persentase kehadiran
* **sleep_hours**: Jam tidur per hari
* **diet_quality**: Kualitas diet (Baik, Cukup, Buruk)
* **exercise_frequency**: Frekuensi olahraga per minggu
* **parental_education_level**: Tingkat pendidikan orang tua
* **internet_quality**: Kualitas koneksi internet (Baik, Rata-rata, Buruk)
* **mental_health_rating**: Peringkat kesehatan mental (1-10)
* **extracurricular_participation**: Partisipasi dalam kegiatan ekstrakurikuler (Ya/Tidak)
* **exam_score**: Skor ujian siswa

## Instalasi

Untuk menjalankan proyek ini, Anda memerlukan pustaka Python berikut:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Anda dapat menginstalnya menggunakan pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
