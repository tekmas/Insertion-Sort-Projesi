[22, 27, 16, 2, 18, 6] dizisindeki en küçük sayı olan 2 ile 22 yer değiştirir: [2,27,16,22,18,6]
Dizinin 1. indexinden sonraki kısmına bakılır:[27,16,22,18,6] küçük sayı olan 6 ile 27 yer değiştirir: [6,16,22,18,27]
Dizinin 2. indexinden sonraki kısmına bakılır:[16,22,18,27] küçük sayı olan 16 zaten 0. indexte olduğundan sıralama değişmez: [16,22,18,27]
Dizinin 3. indexinden sonraki kısmına bakılır.[22,18,27] küçük sayı olan 18 ile 22 yer değiştirir: [18,22,27]
Dizinin 4. indexinden sonraki kısmına bakılır.[22,27] küçük sayı olan 22 zaten 0. indexte olduğundan sıralama değişmez: [22,27]
1, 2, 3 ve 4. adımlardaki sonuç dizilerinin ilk karakterleri ile 5. adımdaki dizi birleştşrildiğinde sıralamamış oluruz:[2,6,16,18,22,27]
Big-O Notation gösterimi : n+(n-1)+(n-2)...+1=(n*(n-1))/2=(n2+n)/2=O(n^2)
Worst Case'de O(n^2), Average Case'de O(n^2), best Case'de ise O(n)'dir.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? : dizinin ortasında olduğundan Average case'dir.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız :
1- [2, 3, 5, 8, 7, 9, 4, 15, 6]
2- [2, 3, 5, 8, 7, 9, 4, 15, 6]
3- [2, 3, 4, 8, 7, 9, 5, 15, 6]
4- [2, 3, 4, 5, 7, 9, 8, 15, 6]
