# Computer Vision Algorithm Results

Repository ini berisi implementasi dan hasil dari berbagai algoritma Computer Vision menggunakan Convolutional Neural Networks (CNN) yang populer.

## Algoritma yang Digunakan

### 1. AlexNet
AlexNet adalah arsitektur CNN yang revolusioner, diperkenalkan pada 2012 oleh Alex Krizhevsky. Model ini menjadi pionir dalam penggunaan deep learning untuk image classification dan memenangkan kompetisi ImageNet 2012. AlexNet memiliki 8 layer (5 convolutional + 3 fully connected) dan menggunakan ReLU activation function.

**Hasil AlexNet:**
![AlexNet Results](AlexNet.jpeg)

### 2. VGGNet
VGGNet dikembangkan oleh Visual Geometry Group dari Oxford University. Model ini terkenal karena menggunakan filter konvolusi kecil (3x3) secara konsisten di seluruh arsitektur. VGG memiliki variasi seperti VGG-16 dan VGG-19, yang menunjukkan jumlah layer dalam network.

**Hasil VGGNet:**
![VGG Results](VGG.jpeg)

### 3. GoogleNet (Inception)
GoogleNet atau Inception Network diperkenalkan oleh Google pada 2014. Inovasi utamanya adalah penggunaan "Inception modules" yang memungkinkan network untuk memilih secara otomatis ukuran filter yang optimal. Model ini lebih efisien dalam penggunaan parameter dibandingkan arsitektur sebelumnya.

**Hasil GoogleNet:**
![GoogleNet Results](GoogleNet.jpeg)

### 4. ResNet
Residual Network (ResNet) dikembangkan oleh Microsoft Research dan memenangkan ImageNet 2015. Inovasi utamanya adalah "skip connections" atau "residual connections" yang memungkinkan training network yang sangat dalam (hingga 152 layer) tanpa mengalami vanishing gradient problem.

**Hasil ResNet:**
![ResNet Results](ResNet.jpeg)

## Ranking Performa Berdasarkan Analisis

VGG-like – Validasi paling tinggi, cepat konvergen, stabil
GoogLeNet – Stabil tapi akurasi rendah
ResNet ringan – Cocok uji coba cepat, performa masih bisa ditingkatkan
AlexNet-like – Berat untuk dataset kecil, akurasi rendah

## Struktur Repository

```
federico-cv2/
├── README.md
├── AlexNet.jpeg
├── VGG.jpeg
├── GoogleNet.jpeg
├── ResNet.jpeg
└── [source code files]
```
