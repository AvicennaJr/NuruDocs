# Installation
To get started download the executables from the release page or follow the
instructions for your device below:

### Windows

 - Download the Nuru Installer [Here](https://github.com/AvicennaJr/Nuru/releases/download/v0.2.0/Nuru_Windows_Installer_v0.2.0.exe)
 - Install the downloaded installer
 - You can watch a full video guide [Here](https://youtu.be/T-lfaoqIFD4)

### Linux

 - Download the binary:

```
curl -O -L https://github.com/AvicennaJr/Nuru/releases/download/v0.2.0/nuru_linux_amd64_v0.2.0.tar.gz
```

  - Extract the file to make global available:

```
sudo tar -C /usr/local/bin -xzvf nuru_linux_amd64_v0.2.0.tar.gz
```

 - Confirm installation with:

```
nuru -v
```

### Android (Termux)

 - Make sure you have [Termux](https://f-droid.org/repo/com.termux_118.apk) installed.
 - Download the binary with this command:

```
curl -O -L https://github.com/AvicennaJr/Nuru/releases/download/v0.2.0/nuru_android_arm64_v0.2.0.tar.gz
```
 - Extract the file:

```
tar -xzvf nuru_android_arm64_v0.2.0.tar.gz
```
 - Add it to path:

```
echo "alias nuru='~/nuru'" >> .bashrc
```
 - Confirm installation with:

```
nuru -v 
```

### Building From Source

 - Make sure you have golang installed
 - Run the following command:

```
go build -o nuru main.go
```
 - You can optionally add the binary to $PATH as shown above
 - Confirm installtion with:

```
nuru -v
```
