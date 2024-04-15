**Background & Problem Statement**
Jumlah informasi yang tersedia melalui internet terus meningkat pesat di era digitalisasi saat ini. Pengguna sering kali mengalami kesulitan dalam menemukan dan mengkonsumsi informasi yang relevan bagi mereka. Portal berita online seperti Liputan 6 menjadi salah satu sumber utama informasi dengan menyajikan berita-berita terkini dalam berbagai bidang.

Dengan banyaknya berita yang dipublikasikan setiap hari di portal berita tersebut, pengguna sering kali tidak memiliki waktu atau kesabaran untuk membaca seluruh artikel. Oleh karena itu, pada project kali ini akan dirancang sistem yang dapat merangkum konten berita menjadi ringkasan yang mencakup inti dari informasi yang disampaikan yang biasa disebut text summarization.

**Objectives:**
Melakukan eksperimen dengan membandingkan model-model pretrained BERT untuk text summarization menggunakan dataset Liputan 6.

**Scope:**
Menggunakan data Liputan 6
Menggunakan BERT language model
Menggunakan V100 GPU/16 GB dan RAM 12.7 GB

**Text Preprocessing**
1. Convert number format
2. Remove parentheses
3. Remove specific word
4. Remove puncuation
5. Remove extra space
6. Case folding (lowercase)
7. Remove stopwords (EDA)
8. Remove singe characters


<img width="619" alt="Screenshot 2024-04-15 at 15 07 02" src="https://github.com/AlfianAliM/Liputan-6-Text-Summarization-Bert2Bert-/assets/115053112/a12dc292-6c72-4d38-9c27-f1c1876b18f7">
<img width="635" alt="Screenshot 2024-04-15 at 15 05 58" src="https://github.com/AlfianAliM/Liputan-6-Text-Summarization-Bert2Bert-/assets/115053112/3bfc8953-81d1-44f5-b58f-b43e7eca3e3a">

**Summary**
1. Model (model_batch_2_lr_1e-5) pretrained cahya/bert2bert-indonesian-summarization yang di-finetune menggunakan 10% data id_liputan6, batch = 2, dan learning rate = 5e-5 menghasilkan performa ROUGE paling baik dibandingkan model lainnya.
2. Selain dari performa prediksi, performa proses training dari model ini juga sangat baik karena training duration hanya membutuhkan waktu 1697 seconds dengan kebutuhan resource yang relatif rendah.

**Future Improvements**
1. Dikarenakan dataset yang besar dan model yang cukup kompleks, maka dibutuhkan resource yang besar untuk projek selanjutnya.
2. Project ini menggunakan 10% dari total train dataset, maka projek selanjutnya menggunakan seluruh dataset untuk train fine tuning dengan resource yang mendukung. 
3. Melakukan error analysis.
4. Menggunakan model text-summarization yang up-to-date (SOTA)
# Liputan-6-Text-Summarization-Bert2Bert-
