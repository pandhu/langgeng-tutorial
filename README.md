
# Langgeng RFM Data Analysis Tutorial

  

Helloo, ini adalah repository untuk tutorial RFM Data Analysis menggunakan python.

  

## Tools yang perlu diinstall
1. Visual Studio Code 
	Visual studio code adalah teks editor yang sering digunakan untuk melakukan pemrograman.
	Download di sini https://code.visualstudio.com/
2. Python
	Python adalah bahasa pemrograman yang paling sering digunakan untuk data analysis
	Download di sini [Windows](https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe) atau [MacOs](https://www.python.org/ftp/python/3.11.0/python-3.11.0-macos11.pkg)

### Mempersiapkan Visual Studio Code
Ada beberapa plugin/extention yang perlu diinstall dan beberapa persiapan lainnya di dalam visual studio code

1. Buat Folder Project **langgeng-tutorial** dan buka folder dengan menggunakan Visual Studio Code
2. Install Jupyter
	Ke menu **Extentions** > **Search** Jupyter > **Install**
3. Buat file **rfm.ipynb** dalam folder **langgeng-tutorial**
	Kita akan dibukakan lembaran baru file jupyter notebook
4. Install Virtual ENV
	Buka menu **Terminal** > **New Terminal** 
	lalu ketik command di bawah ini
	 ``pip install virtualenv``
5. Aktivasi Virtual ENV
	Ketik Command ini di Terminal
	``source venv/bin/activate``
6. Buat file baru di dalam folder langgeng-tutorial dengan nama **requirements.txt**
	Copy isi file https://github.com/pandhu/langgeng-tutorial/blob/master/requirements.txt pada file requirements.txt yang sudah dibuat
7. Install python package
	Ketik Command ini di Terminal
	``pip install -r requirements.txt``
8. Set kernel jupyter ke python pada virtual env
9. Visual Studio Code siap digunakan

## Data Analysis
Seperti pengolahan data pada umumnya, proses analisis data kita akan bagi menjadi 3 bagian

1. Data Input
	Di sini kita akan berbicara terkait bagaimana cara kita membaca data dari CSV atau HTML tabel
2. Data Preprocessing
	Data preprocessing ini dilakukan dengan tujuan membersihkan data input atau menyeragamkan format data sebelum dilakukan pengolahan data lebih lanjut
3. Data Processing
	Pada bagian ini kita sudah masuk pada pengolahan data yang sudah dibersihkan sebelumnya
4. Data Visualizing
	Setelah data diolah, kita akan coba menampilkan data dalam bentuk grafik-grafik

Untuk tutorial lengkap silakan ke file rfm.ipynb