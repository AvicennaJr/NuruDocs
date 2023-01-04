# Kusakinisha (Installation)

### Windows

 - Pakua Kisakinishi cha Nuru [hapa](https://github.com/AvicennaJr/Nuru/releases/download/v0.2.0/Nuru_Windows_Installer_v0.2.0.exe)
 - Sakinisha kisakinishi kilichopakuliwa
 - Unaweza kutazama mwongozo kamili [here](https://youtu.be/T-lfaoqIFD4)

### Linux

 - Pakua binary:

```
curl -O -L https://github.com/AvicennaJr/Nuru/releases/download/v0.2.0/nuru_linux_amd64_v0.2.0.tar.gz
```

  - Dondoo faili:

```
sudo tar -C /usr/local/bin -xzvf nuru_linux_amd64_v0.2.0.tar.gz
```

 - Thibitisha usakinishaji na:

```
nuru -v
```

### Android (Termux)

 - Hakikisha umesakinisha [Termux](https://f-droid.org/repo/com.termux_118.apk).
 - Pakua binary na command hii:

```
curl -O -L https://github.com/AvicennaJr/Nuru/releases/download/v0.2.0/nuru_android_arm64_v0.2.0.tar.gz
```
 - Dondoo faili:

```
tar -xzvf nuru_android_arm64_v0.2.0.tar.gz
```
 - Iweke kwenye path:

```
echo "alias nuru='~/nuru'" >> .bashrc
```
 - Thibitisha usakinishaji na:

```
nuru -v 
```

### Kuijenga kutoka chanzo

 - Hakikisha umeweka golang
 - Andika command hii:

```
go build -o nuru main.go
```
 - Thibitisha usakinishaji na:

```
nuru -v
```
