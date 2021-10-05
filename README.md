# Binary Search Tree Project

* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

![binarytree](https://user-images.githubusercontent.com/69795798/136092026-922e6770-f875-4c07-a26e-2921de3147f2.png)


* root = 7
* Sıradaki elemanlar root değerinden başlayarak kontrol edilir. Root değerinden büyükse sağa, küçükse sola yerleştirilir. Her adımda sıradaki düğüm ile kıyaslanarak sağa veya sola yerleştirilir.
* Sıradaki eleman 5; 5<7 olduğu --> 7'nin solundan devam edilir.
* Sıradaki eleman 1. 1<7 ve 1<5 --> 5'in solundan devam edilir.
* Sıradaki eleman 8. 8>7 --> 7'in sağından devam edilir.
* Sıradaki eleman 3. 3<7, 3<5 ve 3>1 --> 1'in sağından devam edilir.
* Sıradaki eleman 6. 6<7 ve 6>5 --> 5'in sağından devam edilir.
* Sıradaki eleman 0. 0<7,0<5 ve 0<1 --> 1'in solundan devam edilir.
* Sıradaki eleman 9. 9>7 ve 9>8 --> 8'in sağından devam edilir.
* Sıradaki eleman 4. 4<7, 4<5, 4>1 ve 4>3 --> 3'ün sağından devam edilir.
* Sıradaki eleman 2. 2<7, 2<5, 2>1 ve 2<3 --> 3'ün solundan devam edilir.
