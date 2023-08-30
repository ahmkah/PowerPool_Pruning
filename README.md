# PowerPool_Pruning
## dappnode ==> Packages ==> Sepolia Geth ==> Config içinde yazan EXTRA_OPTIONS kısımdaki altı çizili olanyerleri yedekliyoruz.

![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/d5f89e82-e670-4f18-bb09-b3ea1b2d0039)

## dappnode ==> Packages ==> Sepolia Geth ==> Info içinde Remove yapıp tüm dosyayı siliyoruz.

![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/614d9ec5-3b58-4544-b4a3-eb141be8c86e)

## dappnode ==> Packages ==> Sepolia Geth ==> Config içinde yazan EXTRA_OPTIONS kısımdaki  ``--snapshot=false`` yazıyoruz ve update tıklıyoruz. Sync olmasını bekliyoruz.

![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/07ebdbda-02ae-4299-9591-7febda52296a)

## dappnode ==> Dashboard üzerinde Sepolia Geth sync olmasını bekliyoruz 
![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/b8cec9d1-bbaf-4667-96f5-960cd75c8d83)

![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/4a55f196-b596-4357-8e13-63a11071e9ed)

## dappnode ==> Packages ==> Sepolia Geth ==> Logs içinde blok yüksekliğini not alıyoruz. 

![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/4b9df6ed-50e2-4a0f-88dc-de0854238b28)

## Şimdi yapacağımız 288 blok bu şekilde geçmesini beklemek ... 288 blok geçtiken sonra 

## dappnode ==> Packages ==> Sepolia Geth ==> Config içinde yazan EXTRA_OPTIONS kısıma ``snapshot prune-state`` yazıyoruz ve update tıklıyoruz. Budama işleminin yapılmasını bekliyoruz

![image](https://github.com/ahmkah/PowerPool_Pruning/assets/99053148/310c1be2-cfee-4b4e-baa5-b2a1f377aca1)

* Writing state bloom to disk              name=/sepolia/geth/statebloom.0x409490d515d3f315bea34e05f1e0fe522c56ea44a849fffff38b1cf9d27c2e9f.bf.gz  şeklinde bir dosyo kaydedecek. Zaten en sağda ``eta`` yazan kısımda kaç dakika kaldığını söylüyor bu işlemin tamamlanmasını bekleyin.

## dappnode ==> Packages ==> Sepolia Geth ==> Config içinde yazan EXTRA_OPTIONS kısımdaki  ``--http.api eth,engine,net,web3,txpool, --ws.api eth,engine,net,web3,txpool`` yazıyoruz ve update tıklıyoruz. Sync olmasını bekliyoruz. İşlem bu kadar pruning oldu.

* Şimdi PowerArgent yeniden başlatın ve herşey normale dönsün





