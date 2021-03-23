# BASE64 EXAMPLE
## <strong> Base64: </strong> Binary verinin sadece bazı ASCII karakter içerecek şekilde kodlanması anlamına gelir.
## <strong>BASE64 ENCODİNG:</strong>Binary verileri metine dönüştürerek saklamaya veya iletmeye yarayan tekniklerden en yaygın olarak kullanılandır.
<strong>Görüntüyü sunucuya yüklemek veya görüntüyü veritabanına kaydetmek istemeniz durumunda gerçekten yardımcı olur.</strong>
<hr />
<strong>Görüntüyü nasıl Base64 Stringine çevirebiliriz?</strong>
<ol>
<li>İlk olarak görüntüyü Bitmap'e dönüştürün.</li>
<li>Daha sonra Bitmap'i ByteArrayOutputStream olarak sıkıştırın.</li>
<li>ByteArrayOutputStream'i bayt dizisine dönüştürme.</li>
<li>Son olarak oluşan bayt dizisini Base64 dizesine dönüştür.</li>
</ol>
<hr />
<strong>Base64 Stringden Görüntüyü nasıl elde ederim?</strong>
<ol>
<li>Base64 dizesini bayt dizisine çevirin.</li>
<li>Şimdi oluşan bayt dizisini bitmap'e dönüştürün.</li>
</ol>

```java
Bu teknik ile temel olarak 8 bitlik baytlardan oluşan binary veri 6 bitlik
parçalara bölünür.(2^6=64) 6 bit ile ifade edilen 64 farklı sayı,
ASCII karakter kümesinde Printable Character olarak ifade edilen karakterlerle eşleştirilmiştir.
}
```


<img src="https://user-images.githubusercontent.com/76810449/112138549-b0cc9780-8be2-11eb-9f87-591a0531030b.gif" width="340" height="540" />


