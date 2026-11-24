# FORUM_DL
# Comparative Study of Generative Models

Project ini dibuat untuk tugas studi komparatif beberapa model generatif menggunakan dataset FashionMNIST. Secara singkat ini ipynb merupakan untuk tugas forum kampus

Model yang dibandingkan:

- Vanilla Autoencoder (AE)
- Sparse Autoencoder (SAE)
- Variational Autoencoder (VAE)
- Vanilla GAN
- DCGAN
- DDPM

Selain itu dilakukan juga eksperimen menggunakan MLP Classifier untuk menganalisis representasi latent feature yang dipelajari model.

---

## Dataset

FashionMNIST

- 70.000 grayscale images
- 10 kategori fashion
- Ukuran gambar 28x28 pixel

---

## Evaluasi

Beberapa metrik yang digunakan:

- MSE
- PSNR
- SSIM
- FID

Eksperimen tambahan:

- Weight Transpose Projection
- Latent Transpose Projection
- Frozen Latent Decoder
- Random Latent Sampling
- Latent Interpolation

---

## Cara Menjalankan

Install dependency:

```bash
pip install -r requirements.txt
