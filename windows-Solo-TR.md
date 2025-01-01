
# InitChain Windows Solo Kurulum ; 

#### Link: https://github.com/Project-InitVerse/ini-chain/releases/tag/v1.0.0

![image](https://github.com/user-attachments/assets/9a7697ea-10cf-44fb-bff8-dab2872a5e09)

#### Windows olanı indirin - zip olarak gelecek yeni bir klasör oluşturun ve içine atın.

![image](https://github.com/user-attachments/assets/4457d1ad-3f5a-4bb2-bd57-88b10da7a661)

#### Sonra yukarıdaki dosya yolu kısmına "cmd" yazıp enterleyin.

![image](https://github.com/user-attachments/assets/1fdb3bf2-e34f-4324-9a6b-0a29dab368cb)

#### Bu Komutu Yapıştırın Başlayacaktır ;

```bash
geth-windows-x64.exe --datadir data --http.api="eth,admin,miner,net,web3,personal" --allow-insecure-unlock --testnet console
```

![image](https://github.com/user-attachments/assets/0a2fc8fe-4f64-4071-a177-0c5ec4bb5991)


#### Başlangıç ; 

![image](https://github.com/user-attachments/assets/f4c29dc4-2c07-4e54-9d74-17fb52ead0dd)

#### Sonra attığınız dosyada "data" adlı bir dosya oluşturacak ve sync olmaya başlayacak. En başlarda ortalama 1 GB alan kaplıyor.

![image](https://github.com/user-attachments/assets/7790bc59-9803-471b-a276-10575472db50)

![image](https://github.com/user-attachments/assets/62ea8b5d-cc81-4be8-b34a-72d2e94c5258)

#### Buradaki Adresi kendi adresiniz ile değiştirin. Sonra Sağ tık ile yapıştırıp enterleyin.

```bash
miner.setEtherbase("0x0304f5193FCe6A27e3789c27EE2B9D95177e21A5")
```

#### Örnek ; 

- Siz sağ tık yapınca sanki yazmamış gibi gözüküyor lakin enter'e bastığınızda true yazısını göreceksiniz.

![image](https://github.com/user-attachments/assets/6a399710-e2fa-4304-9509-7a8f6e2bdc67)

#### Başlatalım / Çekirdek ayarlayalım ; 

```bash
miner.start()
```

- Kaç çekirdek vermek istiyorsak () arasına yazmanız gerekiyor misal 3 çekirdek ; miner.start(3)

![image](https://github.com/user-attachments/assets/df8aaaff-e2ec-45d4-a0ef-29644c3e9695)

#### Artık çalışıyor - tüm çekirdekleri verince bilgisayarınız fırına döner dikkatli olunuz. Ben 3 verdim şimdilik. Sıvı soğutma ile 74 Derece.
