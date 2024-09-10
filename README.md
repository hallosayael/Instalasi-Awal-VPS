## Instalasi Awal Penggunaan VPS
### Ikuti Step by Step
```
apt update
```
```
apt install git
```
```
apt install apt-transport-https ca-certificates software-properties-common curl
```
```
curl -f -s -S -L https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
```
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
```
```
apt update
```
```
cd /root
```
```
sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```
```
sudo systemctl status docker
```
### Cek Versi Docker
```
docker --version
```
> Jika muncul pesan seperti ini `Docker version xxx.xxxx` artinya Docker sudah terpasang, jika tidak muncul silahkan install kembali dockernya
# Instal Otomatis

```
apt update && apt upgrade -y
```

Biarkan Instalisasi Selesai, Agak Lama


```
apt install -y build-essential
```
```
apt install -y curl
```

# Cek Versi Node (Rekomendasi Versi Node v18.xx)

```
apt install -y nodejs
```

```
node -v
```
- Jika versi node kalian dibawah v18, Jalankan step dibawah ini.

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```
```
source ~/.bashrc
```
```
nvm --version
```
```
nvm ls
```
```
nvm ls-remote
```
### contoh install v18.13.0 mau install versi berapapun bebas
```
nvm install v18.13.0
```
# Install screen
```
apt install screen
```
