## Hakkında

* TCP üzerinden saat senkronizasyonu yapan sunucu servisi ve istemcisidir.
* Sunucu 142. portu dinlemektedir.

## Kullanım

* Sunucu `sunucu.py` ile çalıştırılır.
* İstemci `istemci.py sunucu_ip_adresi` ile çalıştırılır.

## Sunucu

Sistem zamanını milisaniye cinsinden ve sunucu dosyası içerisinde bulunan UTC değişkeninin değerini sunucuya bağlanan istemcilere gönderir.

## İstemci

İstemci sistem zamanını sunucudan aldığı milisaniye ve UTC değerini hesaplayarak değiştirir.
