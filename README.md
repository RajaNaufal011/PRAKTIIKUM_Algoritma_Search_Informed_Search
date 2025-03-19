# PRAKTIIKUM_Algoritma_Search_Informed_Search
#2306020_Raja Naufal Fadhil Ns

# Implementasi Algoritma Pencarian dengan Informasi Tambahan (*Informed Search*)

Repository ini berisi implementasi berbagai algoritma pencarian dengan informasi tambahan (*Informed Search*) dalam bahasa Python. Algoritma yang tersedia meliputi:

## **Algoritma Pencarian dengan Informasi Tambahan**

- **Greedy Best-First Search (GBFS)**: Algoritma yang memilih node berdasarkan estimasi heuristik terhadap tujuan tanpa mempertimbangkan biaya perjalanan sebelumnya.
- **A* Tree Search**: Implementasi algoritma A* dengan pendekatan *tree search*, di mana tidak ada daftar node yang telah dieksplorasi.
- **A* Graph Search**: Implementasi algoritma A* dengan pendekatan *graph search*, yang menyimpan daftar node yang telah dikunjungi untuk menghindari eksplorasi ulang.

Algoritma-algoritma ini digunakan untuk menemukan jalur optimal dalam suatu graf dengan memanfaatkan informasi heuristik guna meningkatkan efisiensi pencarian.

## **Struktur Repository**

📂 **File dalam Repository**

- `greedy_best_first.py` → Implementasi *Greedy Best-First Search*  
- `a_star_tree.py` → Implementasi *A* Tree Search  
- `a_star_graph.py` → Implementasi *A* Graph Search  

Setiap file mencakup implementasi algoritma serta contoh penggunaannya yang dapat diuji secara langsung.

## **Cara Menjalankan di Google Colab atau Terminal**

1. Clone repository ke Google Colab atau komputer lokal:  
   ```bash
   git clone https://github.com/username/repository-name.git  
   cd repository-name  
   ```  
2. Jalankan file Python yang diinginkan:  
   ```bash
   python greedy_best_first.py  
   python a_star_tree.py  
   python a_star_graph.py  
   ```  

## **Kontribusi**
Kontribusi dalam bentuk perbaikan kode, optimasi algoritma, atau penambahan fitur baru sangat dihargai. Silakan lakukan *fork*, buat perubahan, dan ajukan *pull request*.

## **Lisensi**
Repository ini dirilis di bawah lisensi [MIT](LICENSE).

