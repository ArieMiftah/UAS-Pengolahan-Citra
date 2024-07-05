# UAS - Pengolahan Citra

Kelompok: 
- Arie Miftah Budiman
* Ridwan Ahri
+ Moh. Restu Nur Rizki

### Penjelasan Algoritme K-means Clustering untuk Segmentasi Gambar

#### 1. Memuat Gambar

```python
image = cv2.imread('images/helmet.jpg')
if image is None:
    raise FileNotFoundError("File gambar tidak ditemukan. Periksa kembali jalur file.")'''

#### 2. Mengubah Warna Gambar
```python
image = cv2.cvtColor(image, cv2.COLOR_BGR2RGB)
