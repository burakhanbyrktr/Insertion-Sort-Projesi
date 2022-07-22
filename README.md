# Insertion-Sort-Projesi
Patika.dev Ekleme Sıralama Bitirme Projesi
#Ekleme Sıralama Projesi
[22,27,16,2,18,6] - Ekleme Sıralaması

֎ 1-Yukarı verilen verilebilir sıralama düzenini aşamalarını not edin.

֎ 2-Big-O gösterimini yazınız.

֎ 3-Zaman Karmaşıklık: Ortalama durum: Aradığımız sayının olmaması olması,En kötü durum: Aradığımız sayının sonda olması, En iyi durum: Aradığımız sayının en olması olması.

֎ 4-Dizi sıralandıktan sonra 18 sayı hangi davaya girer? Yazınız.

֎ 5-[7,3,5,8,2,9,4,15,6] dizinin Ekleme Sırala'a göre ilk 4 adımını yazın.
Ekleme Sıralama Aşamaları
[22,27,16,2,18,6] - (n)

[2|,27,16,22,18,6] - (n-1)

[2,6|,16,22,18,27] - (n-2)

[2,6,16|,18,22,27] - (n-3)

Büyük O Notasyonu Gösterimi

En Kötü Durum: O(n²) = n+(n-1)+(n-2)...+1

Ortalama Vaka: O(n²)

En İyi Durum: O(n)

Zaman Karmaşıklığı

En Kötü Durum: [27,22,18,16,6,2]

En İyi Durum: [2,6,16,18,22,27]

18 Sayısının Vaka Durumu

Dizimiz küçükten büyü sıralandıktan sonra [2,6,16,18,22,27] şeklini alır ve 18 sayısı bu ortanca değeridir. Yani ortalama durumda diyebiliriz.

[7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]
www.patika.dev

