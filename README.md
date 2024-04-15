# Liputan-6-Text-Summarization-Bert2Bert-

Background & Problem Statement

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

   ![image](https://github.com/AlfianAliM/Liputan-6-Text-Summarization-Bert2Bert-/assets/115053112/99ccbd9b-1dd3-4e58-a52e-acfb96048dd3)
