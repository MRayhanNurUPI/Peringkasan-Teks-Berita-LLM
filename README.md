# Peringkasan Teks Berita Otomatis Menggunakan Model LLM (TUGAS FINAL NLP)

## Deskripsi
Proyek ini bertujuan untuk mengeksplorasi dan menerapkan model Large Language Model (LLM) untuk melakukan peringkasan otomatis pada teks berita berbahasa Indonesia serta Fine Tuning model LLM sesuai dengan dataset tertentu.

## Model LLM yang digunakan
- LazarusNLP/IndoNanoT5-base (https://huggingface.co/LazarusNLP/IndoNanoT5-base)
- google/mt5-small (https://huggingface.co/google/mt5-small)

## Dataset
Dataset yang digunakan untuk fine-tuning model adalah IndoSUM (folder train) dan dapat ditemukan di (https://github.com/kata-ai/indosum).

## Skenario Proyek
1) Membandingkan hasil peringkasan teks berita dengan model LLM IndoNanoT5-base sebelum dan sesudah fine-tuning.
2) Melihat hasil ringkasan teks berita dengan model LLM mt5-small dengan pendekatan pembelajaran one-shot & few-shot learning.
3) Melakukan fine-tuning pada model LLM mt5-small dan melihat hasil ringkasan teks berita dengan pendekatan 0-shot, one-shot, & few-shot learning.

## Metode Evaluasi
Hasil ringkasan dari tiap skenario dievaluasi dengan menggunakan metrik ROUGE Score.
