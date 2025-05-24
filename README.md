# StyleVisionAI

---

**StyleVisionAI**, gardıroptaki kıyafet görsellerini otomatik olarak tanıyan ve sınıflandıran bir derin öğrenme modelidir.

Modelin eğitimi için **Fashion Product Images (Small)** veri seti kullanılmıştır. Bu veri seti, e-ticaret alanında kullanılan yüksek çözünürlüklü kıyafet fotoğraflarından ve bu ürünlere ait etiketlerden oluşmaktadır. Görseller, `images/` klasöründe yer almakta ve ürün bilgileri `styles.csv` dosyasında tanımlanmaktadır.

Bu proje kapsamında, veri setindeki tüm ürünler yerine sadece **gardıroba uygun 9 kategori** seçilmiştir:

- Casual Shoes  
- Heels  
- Jackets  
- Dresses  
- Skirts  
- Jeans  
- Trousers  
- Shirts  
- Tops  

Model bu filtrelenmiş sınıflar üzerinden eğitilmiş ve her görsel bu sınıflardan biriyle etiketlenmiştir.

### Proje Dosyaları
- `StyleVisionModel.ipynb`: Modelin eğitildiği Jupyter notebook dosyası  
- `stylevision_model_final224.h5`: Eğitilmiş modelin ağırlık dosyası  

---

**StyleVisionAI** is a deep learning model that automatically recognizes and classifies clothing images from a personal wardrobe.

The model was trained using the **Fashion Product Images (Small)** dataset. This dataset includes product images and their corresponding labels, commonly used in the e-commerce industry. Images are stored in the `images/` folder, while metadata and labels are listed in `styles.csv`.

For this project, only **9 relevant clothing categories** were selected from the dataset:

- Casual Shoes  
- Heels  
- Jackets  
- Dresses  
- Skirts  
- Jeans  
- Trousers  
- Shirts  
- Tops  

The model was trained exclusively on these filtered classes to ensure better performance on real wardrobe content.

### Project Files
- `StyleVisionModel.ipynb`: Jupyter notebook used for training the model  
- `stylevision_model_final224.h5`: Trained model weights file  
