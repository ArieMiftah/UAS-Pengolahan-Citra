# UAS - Pengolahan Citra

Kelompok: 
- Arie Miftah Budiman
* Ridwan Ahri
+ Moh. Restu Nur Rizki

### Penjelasan Algoritme K-means Clustering untuk Segmentasi Gambar

#### 1. Memuat Gambar

```
image = cv2.imread('images/helmet.jpg')
if image is None:
    raise FileNotFoundError("File gambar tidak ditemukan. Periksa kembali jalur file.")```

```
> Memuat gambar helmet.jpg menggunakan OpenCV. Jika gambar tidak ditemukan, akan muncul pesan kesalahan.
