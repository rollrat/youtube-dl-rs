# youtube-dl for Rust

This project is forked from `RustPython`

## Why RustPython?

## FFI Api

## Flutter Binding

## How to run

```sh
git clone https://github.com/microsoft/vcpkg
cd vcpkg
./bootstrap-vcpkg.bat
./vcpkg.exe install openssl-windows:x64-windows
./vcpkg.exe install openssl:x64-windows-static
./vcpkg.exe integrate install
set VCPKGRS_DYNAMIC=1
$env:OPENSSL_DIR="G:\Dev2\vcpkg\installed\x64-windows"

cargo run --release --features freeze-stdlib,stdlib,ssl .\yt_dlp\__main__.py
```
