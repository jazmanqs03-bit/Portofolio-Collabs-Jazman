<img width="1589" height="690" alt="image" src="https://github.com/user-attachments/assets/76093275-91d8-4fad-a88d-2bd80bf2627e" />
##Analisa Reservoir dengan Collabs - Machnie Learn
### Analisa data komplek Perminyakan :
Analisa data komplek perminyakan pada kali ini adalah dengan Konsep EDA - Eksploratori Data analisis.
Eksploratori data analisis dilakukan dengan menginput facies data yang terdiri dari Depth, well formation, Gamma Ray, Resistvity - ILD_LOG10, DeltaPHI, PHIND - Porosity, PE - Photoelktrik Elect. 
#### Histogram dengan perbedaan Warna dan ketinggian nilai :
Histogram berwarna ini menunjukkan bahwa setiap log memiliki karakter distribusi yang berbeda, mencerminkan variasi litologi, fluida, dan mineralogi reservoir. Perbedaan warna berasal dari perbedaan frekuensi relatif dalam setiap bin, di mana warna terang menandakan interval yang paling dominan secara statistik. Pendekatan ini efektif untuk eksplorasi data awal (EDA) dan membantu mengidentifikasi populasi utama, outlier, serta tingkat heterogenitas reservoir sebelum dilakukan analisis lanjutan seperti clustering atau machine learning.
##### Heatmap :
Heatmap korelasi ini menggambarkan hubungan linier antar parameter log sumur dan atribut turunan yang digunakan dalam analisis petrofisika dan machine learning, meliputi Facies, Depth, Gamma Ray (GR), ILD_log10 (resistivitas), DeltaPHI, PHIND (porositas), Photoelectric (PE), NM_M (Nonmarine–Marine indicator), dan RELPOS (Relative Position). Nilai korelasi berkisar dari –1 hingga +1, di mana warna merah menunjukkan korelasi positif kuat, warna biru menunjukkan korelasi negatif kuat, dan warna netral menunjukkan hubungan yang lemah atau tidak signifikan.
###### Pembacaan Log : 
Dilakukan plot log dengan analisa bahwa menampilkan integrasi lima track log utama—Gamma Ray, Resistivitas, Delta Phi, Porositas Densitas (PHIND), dan Photoelectric Effect (PE)—yang digunakan untuk mengkarakterisasi litologi, kualitas reservoir, efek fluida, serta indikasi mineralogi secara vertikal terhadap kedalaman. Setiap track disajikan dengan zona interpretatif berarsir untuk menegaskan batas litologi, tipe fluida, respon gas, kualitas porositas, dan komposisi mineral dominan.

Pendekatan multi-log ini memungkinkan analisis terpadu antara respon fisik batuan dan fluida, sehingga transisi dari shale ke pasir, perubahan kandungan fluida (air–hidrokarbon–gas), serta variasi mineral penyusun dapat diidentifikasi secara lebih konsisten. Dengan demikian, visualisasi ini menjadi dasar yang kuat untuk interpretasi reservoir, penentuan interval prospektif, dan validasi hasil analisis lanjutan seperti electrofacies berbasis machine learning.

####### Crossplot Well Log : 
Crossplot well log yang mengintegrasikan Gamma Ray, DeltaPHI, porositas (PHIND), resistivitas, dan Photoelectric Effect (PE) untuk mengidentifikasi hubungan litologi, efek gas, kualitas reservoir, serta karakter mineralogi. Pewarnaan berdasarkan facies memperlihatkan sebaran dan overlap respon log, sehingga memudahkan pemahaman heterogenitas batuan dan dasar interpretasi facies serta analisis lanjutan berbasis machine learning.
