# SEI 1.0.4 Güncelleme Scripti | Upgrade Script SEI 1.0.4beta

![three](https://cdn.discordapp.com/attachments/987875932129886231/989551097158975578/ssss.png)

## Sunucu Kurulumu | Server Installation

### [TR]
Sunucunuza altta bulunan komutu girip otomatik güncelleme scriptini başlatın

### [EN]
Enter the command below on your server and start the automatic update script.


`SCRIPT BAKIMDADIR GUNCEL KOMUTLAR DUZENLENIYOR`


## Unjail olmak | To be unjailed

![three](https://cdn.discordapp.com/attachments/987875932129886231/989551527628787732/unknown.png)

### [TR]
Validatör sayfanıza girdiğinizde sağ üst köşede bu şekilde bir görüntü varsa alttaki komutu yazmanız gerekiyor.  
- --from=walletname  
Kısmında cüzdan adınızı walletname yazısını silip yazmanız gerekiyor.

### [EN]
When you enter the validator page, if there is an image like this in the upper right corner, you need to type the command below.  
- --from=walletname  
In the section, you need write your wallet name

```
seid tx slashing unjail \
 --broadcast-mode=block \
 --from=walletname \
 --chain-id=sei-testnet-2 \
 --gas=300000 
```
