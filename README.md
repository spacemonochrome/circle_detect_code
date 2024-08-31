# Hough Dönüşümü ile çember tespiti - Determining a circle with the Hough Transform
OpenCV kütüphanesi ile beraber yazılmış bu python kodu çember tespiti yapabilmektedir. Paul Hough dönüşümünü kullanmaktadır.
Verimliliği düşüktür. Bilgisayar işlemcisinde saniye 30 kare gibi bir hızda çalışmakta lakin Raspberry Pi gibi düşük sistemli bilgisayarlarda saniyede 1 kare bile işlememektedir. verimsizdir ama gene de üstüne uğraşılmıştır. Detaylı anlatım için aşağıdaki makaleyi inceleyebilirsiniz.

This Python code, written with the OpenCV library, can detect circles. It uses the Paul Hough transformation.
Its efficiency is low. It runs at a speed of 30 frames per second on the computer processor, but it does not process even 1 frame per second on low-system computers such as Raspberry Pi. It's inefficient, but it's still worked on. For detailed explanation, you can review the article below.

[SUTIS -proceeding-book-29-33.pdf](https://github.com/spacemonochrome/circle_detect_code/files/14733551/SUTIS.-proceeding-book-29-33.pdf)

Kütüphane kurulumu - installing library
NumPy kurulumu
```bash
pip install numpy
```

OpenCV Kurulumu
```bash
pip install opencv-python
```

Girdi Görüntüsü - Input
![image](https://github.com/spacemonochrome/circle_detect_code/assets/52783312/d92b5642-72ed-487b-bdff-ddd41122de90)

Çıktı Görüntüsü - Output
![cikti](https://github.com/spacemonochrome/circle_detect_code/assets/52783312/121373dd-dd75-4e6a-ab6a-231ca015fee9)

İşlemin görselleştirilmesi - visualization of the process
![image](https://github.com/spacemonochrome/circle_detect_code/assets/52783312/5ac7036e-c14b-49e8-9bad-6494c71cc5ab)


