# imagemagick
Imagemagick ile yapılabilecekler...


Bir klasördeki tüm imajları optimize etmek;
<!-- language: php -->
mogrify -strip -interlace Plane -gaussian-blur 0.05 -quality 85% -flatten *
<!-- language: php -->

Tek bir dosyayı optimize etmek
<!-- language: php -->
magick test.png -format JPG -strip -interlace Plane -gaussian-blur 0.05 -quality 85% -flatten result.jpg
<!-- language: php -->
