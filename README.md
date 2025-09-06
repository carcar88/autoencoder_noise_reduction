# autoencoder_noise_reduction
_Repository_ ini menunjukkan model _autoencoder_ yang digunakan untuk melakukan _image noise reduction_. Model pertama merupakan _base model_ dengan arsitektur seperti berikut:
<img width="874" height="615" alt="image" src="https://github.com/user-attachments/assets/b57c1969-788c-4865-b46f-eb145b4863a9" />
Model kedua adalah hasil modifikasi base model dengan mengimplementasikan u-net model. Hal ini dilakukan karena pada _base model_, banyak fitur gambar yang hilang saat proses _encoding_. Penggunaan u-net model dapat mengembalikan fitur-fitur yang hilang saat proses _encoding_. Kedua model dievaluasi menggunakan skor SSIM.

------------------------------
This repository showcases an autoencoder model used for image noise reduction. The first model is the base model with this architect: 
<img width="874" height="615" alt="image" src="https://github.com/user-attachments/assets/a530a096-daee-427f-a388-0bccacca9ce3" />
The second model is the modification of the base model with the implementation of a u-net model. This is done in order to combat the feature lost that happened during the encoder process from the base model. The implementation of the u-net model will combat this problem by returning the lost features. Both models were evaluated using SSIM score.


