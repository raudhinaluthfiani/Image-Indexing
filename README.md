# Image-Indexing
1.	Persiapan sebelum menjalankan dan mengkonfigurasi toolkit image search engine  
-	clone toolkit https://github.com/kudeh/image-search-engine di komputer  
$ git clone https://github.com/kudeh/image-search-engine  
<img width="491" alt="1" src="https://user-images.githubusercontent.com/49057899/66782912-fe7aa600-ef00-11e9-9b75-7a3a593a609f.png">




-	lihat versi python di komputer, sebab toolkit yang digunakan berbasis python   
$ python –version  
-	install python jika belum terinstall di komputer  
$ sudo apt-get install python  
2.	Penginstalan requirements package pada toolkit  
-	masuk ke dalam directory git yang telah diclone yaitu ‘image-search-engine’  
$ cd image-search-engine  
<img width="518" alt="2" src="https://user-images.githubusercontent.com/49057899/66782934-0c302b80-ef01-11e9-838a-06e82d3cedfa.png">
-	install requirements package  
$ pip3 install -r requirements.txt (jika menggunakan python 3)  
$ pip install -r requirements.txt (jika masih menggunakan python 2)  
<img width="510" alt="3" src="https://user-images.githubusercontent.com/49057899/66783008-3a157000-ef01-11e9-9f7d-8ceb3b2b34f8.png">
Jika terjadi error, bisa menggunakan syntaks lain seperti :  
$ sudo pip3 install -r requirements.txt (jika menggunakan python 3)  
<img width="514" alt="4" src="https://user-images.githubusercontent.com/49057899/66783047-4dc0d680-ef01-11e9-8438-4c5f753cfd3b.png">

-	install numpy dan openvc  
$ pip3 install numpy  
<img width="489" alt="5" src="https://user-images.githubusercontent.com/49057899/66783065-587b6b80-ef01-11e9-804c-0c29671d2d94.png">








-	install opencv  
$ sudo apt-get install python-opencv  
<img width="454" alt="6" src="https://user-images.githubusercontent.com/49057899/66783092-66c98780-ef01-11e9-806b-8515fbe7c73e.PNG">










3.	Menjalankan toolkit  
-	untuk menjalankannya kita harus masuk ke dalam directory app  
$ cd app  
<img width="513" alt="7" src="https://user-images.githubusercontent.com/49057899/66783138-7cd74800-ef01-11e9-8594-229f091a6d36.PNG">
-	menjalankan toolkit  
$ python3 index.py –dataset static/images –index index.csv  

<img width="506" alt="8" src="https://user-images.githubusercontent.com/49057899/66783168-8eb8eb00-ef01-11e9-8480-5e5c3d09aa12.PNG">

-	hasil dari indexing nya akan disimpan di file index.csv  
$ nano index.csv  
<img width="521" alt="9" src="https://user-images.githubusercontent.com/49057899/66783179-9a0c1680-ef01-11e9-9c66-38a6247aab95.PNG">
-	hasil image-indexing  
<img width="515" alt="10" src="https://user-images.githubusercontent.com/49057899/66783196-a4c6ab80-ef01-11e9-8326-b6704350dd03.PNG">

Source Link : https://github.com/kudeh/image-search-engine  
