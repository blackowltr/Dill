# Dill Alps Testnet Rehberi

Bu rehberde Alps testnet ağına nasıl bağlanacağınızı, node kurulumunu ve validator olma adımlarını Türkçe olarak ele alacağız. Tüm adımları takip ederek Alps testnet'e başarılı bir şekilde katılabilirsiniz.

![image](https://github.com/user-attachments/assets/9458abd4-e1cf-4b58-89ab-5251ee125556)

## Node Gereksinimleri

Alps testnet ağına katılmadan önce, kuracağınız node tipi için aşağıdaki sistem gereksinimlerini kontrol edin:

| Node Tipi         | CPU      | Bellek | Disk    | Bant Genişliği | İşletim Sistemi       |
| ----------------- | -------- | ------ | ------- | -------------- | --------------------- |
| Light Validator   | 2 çekirdek| 2 GB   | 20 GB   | 8 Mb/s         | Ubuntu LTS 20.04+/MacOS|
| Full Validator    | 4 çekirdek| 8 GB   | 256 GB  | 64 Mb/s        | Ubuntu LTS 20.04+/MacOS|

## Alps Testnet'e Bağlanma

Aşağıdaki bilgileri kullanarak Alps testnet ağına bağlanabilirsiniz:

- **RPC URL**: `https://rpc-alps.dill.xyz`
- **Chain ID**: `102125`
- **Sembol**: `DILL`
- **Explorer**: [https://alps.dill.xyz](https://alps.dill.xyz)

### MetaMask'e Ağ Ekleme

MetaMask'e özel ağ eklemek için gerekli talimatlar için [bu bağlantıya](#) göz atabilirsiniz.

## Test Token'ı Almak

Alps testnet üzerinde test token alabilmek için [Discord sunucumuza](https://discord.gg/CJuq7rXM) katılmanız gerekmektedir. 

## Node Kurulumu

Light ya da Full node kurulumunu gerçekleştirmek için aşağıdaki komutu terminalde çalıştırabilirsiniz:

```bash
curl -sO https://raw.githubusercontent.com/DillLabs/launch-dill-node/main/dill.sh && chmod +x dill.sh && ./dill.sh
```

## Staking (Validatör Olma)

Alps testnet ağında validatör olabilmek için token'larınızı stake edebilirsiniz. Bunun için [staking web sitesini](https://staking.dill.xyz/) kullanabilirsiniz:

### Staking İşlemi

1. **Deposit Bilgilerinizi Yükleyin**: `deposit_data-xxxx.json` dosyanızın içeriğini giriş kutusuna yapıştırın ve "Devam Et" butonuna tıklayın.

![image](https://github.com/user-attachments/assets/30595b6d-cc2f-41cf-b353-e6706edc1dde)
   
2. **Cüzdan Bağlayın**: Eğer kullandığınız cüzdan adresi, çekim (withdrawal) adresinizle aynı ise onay kutusunu işaretlemeniz yeterlidir. Aksi takdirde, çekim adresinizi tamamen girmeniz gerekmektedir.

![image](https://github.com/user-attachments/assets/643ae638-94cd-49aa-a064-bc12bc8eb583)

3. **Deposit İşlemini Gönderin**: MetaMask üzerinden bir deposit işlemi başlatarak stake işlemini tamamlayabilirsiniz.

![image](https://github.com/user-attachments/assets/40aeb651-ebc0-40eb-bf01-898d50c7c458)

## Validatör Bilgileri

Validatör bilgilerinizi aşağıdaki sayfadan bulabilirsiniz:

[Validatör Bilgileri](https://alps.dill.xyz/validators)

Stake işlemini tamamladıktan sonra, validatör anahtarınız ile validator bilgilerinizi arayabilirsiniz. Bu bilgilerin sayfada görünmesi 30 dakika - 1 saat civarı sürebilir.
