# Project2MergeSort

Merge Sort

## Proje 2

### [16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
Verilen dizi: [16, 21, 11, 8, 12, 22]

1. Adım: Diziyi parçalara ayırma (Divide Phase)

Diziyi ortadan ikiye böleriz:
[16, 21, 11] ve [8, 12, 22]

Sol yarıyı tekrar böleriz:
[16] ve [21, 11]

Sağ yarıyı tekrar böleriz:
[8] ve [12, 22]

Sağ yarıdaki [21, 11] ve [12, 22] dizilerini tekrar böleriz:
[21], [11], [12], [22]

2. Adım: Dizileri birleştirme (Conquer/Merge Phase)

[21] ve [11] birleştirilir:
[11, 21]

[12] ve [22] birleştirilir:
[12, 22]

[16] ve [11, 21] birleştirilir:
[11, 16, 21]

[8] ve [12, 22] birleştirilir:
[8, 12, 22]

Son olarak, [11, 16, 21] ve [8, 12, 22] birleştirilir:
[8, 11, 12, 16, 21, 22]

Sonuç: [8, 11, 12, 16, 21, 22]
```
