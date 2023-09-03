import pandas as pd

# Membaca data dari file CSV
data = pd.read_csv('data.csv')

# Menampilkan beberapa data pertama
print(data.head())
import matplotlib.pyplot as plt

# Membuat plot sederhana
plt.plot([1, 2, 3, 4], [1, 4, 9, 16])
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Contoh Plot')
plt.show()
import numpy as np

# Membuat array NumPy
data = np.array([1, 2, 3, 4, 5])

# Menghitung rata-rata
mean = np.mean(data)
print("Rata-rata:", mean)
import seaborn as sns

# Memvisualisasikan hubungan antara dua variabel
sns.scatterplot(x='Age', y='Income', data=data)
