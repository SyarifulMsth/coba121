# Predictive Analytics Portfolio Project: Case Study of Diamond Price Prediction💎	

Predictive Analytics Lifecycle (CRISP-DM):
  1. Business Understanding
  2. Data understanding 
  3. Data preparation 
  4. Modeling 
  5. Evaluation 
  6. Deployment

## Business Understanding
Saya bekerja di sebuah perusahaan yang bergerak di bidang jual-beli diamonds (berlian). Model bisnis perusahaan tersebut adalah distributor dan retail, perusahaan membeli diamonds dari produsen kemudian menjualnya kepada konsumen. Perusahaan juga menerima penjualan kembali diamonds dari konsumen. Untuk efisiensi, perusahaan ingin menerapkan automasi pada sistem dalam memprediksi harga diamonds dengan teknik predictive modelling. 

Pada kasus ini, perusahaan mengetahui bahwa harga sebuah diamonds dengan karakteristik tertentu bernilai $9000 di pasaran.  Jika ingin mendapatkan profit, tentu perusahaan harus mendapatkan harga beli diamond yang lebih rendah dari $9000. Sebut saja misal, harga belinya adalah $5000. Sudah pasti ini akan menjadi keuntungan besar bagi perusahaan. Sebaliknya, jika perusahaan membeli diamonds tersebut dengan harga di atas $9000, maka perusahaan akan rugi.

Tentu saja semua bisnis mengejar profit. Oleh karena itu, penting bagi perusahaan untuk mengetahui dan dapat memprediksi harga diamonds di pasar. Prediksi akan digunakan untuk menentukan berapa harga beli yang pantas untuk diamonds dengan karakteristik tertentu sehingga perusahaan bisa mendapatkan profit sebesar mungkin.

Tidak seperti emas yang harga jual dan belinya mengacu pada harga perdagangan emas dunia, harga diamonds dipengaruhi oleh beberapa fitur khusus. Fitur tersebut antara lain, karat, ukuran, bentuk potongan, warna, serta tingkat kejernihan diamonds. Tidak adanya acuan harga diamonds seperti acuan harga emas menyebabkan perusahaan memerlukan sistem untuk memprediksi harganya.

### Problem Statements dan Goals
Berdasarkan kondisi yang telah diuraikan sebelumnya, perusahaan akan mengembangkan sebuah sistem prediksi harga diamonds untuk menjawab permasalahan berikut.

Dari serangkaian fitur yang ada, fitur apa yang paling berpengaruh terhadap harga diamonds?
Berapa harga pasar diamonds dengan karakteristik atau fitur tertentu?  
Untuk menjawab pertanyaan tersebut, maka diperlukan predictive modelling dengan tujuan atau goals sebagai berikut:
  - Mengetahui fitur yang paling berkorelasi dengan harga diamonds.
  - Membuat model machine learning yang dapat memprediksi harga diamonds seakurat mungkin berdasarkan fitur-fitur yang ada.

### Metodologi
Tujuan utama dari kasus kali ini adalah memprediksi harga diamonds. Harga diamonds merupakan variabel kontinu dalam predictive analytics, sehingga ini merupakan permasalahan regresi. Oleh karena itu, metodologi pada proyek ini yaitu model regresi dengan harga diamonds sebagai target.

### Metrik
Metrik digunakan untuk mengevaluasi seberapa baik model yang telah dibuat untuk memprediksi harga. Untuk kasus regresi, beberapa metrik yang biasanya digunakan adalah Mean Squared Error (MSE) atau Root Mean Square Error (RMSE). Secara umum, metrik ini mengukur seberapa jauh hasil prediksi dengan nilai yang sebenarnya. 
Pengembangan model akan menggunakan beberapa algoritma machine learning yaitu K-Nearest Neighbor, Random Forest, dan Boosting Algorithm. Dari ketiga model ini, akan dipilih satu model yang memiliki nilai kesalahan prediksi terkecil.
