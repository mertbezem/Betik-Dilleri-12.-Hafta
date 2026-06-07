function isimGoster()
{
    //isim degiskeni sadece bu fonksiyon içinde erişilebilir
    var isim="Asya";
    alert(isim);
}
alert(isim); //değişken var ile tanımlandığı içn fonksiyon dışından erişilemez

if( 15 > 10) {
    var sayi = 17;
}
alert(sayi); //sayi degiskenine if bloğu dışından da erişilebilir
