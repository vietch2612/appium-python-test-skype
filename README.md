# appium-test-skype
Automation Test sử dụng Appium và ngôn ngữ Python

## Cài đặt
### Cài đặt Python
Sử dụng `Homebrew`
```bash
brew install python
```
### Cài đặt Appium
Cài đặt node
```bash
brew install node
```
Cài đặt appium package, không được chạy các command dưới quyền `sudo`
```bash
npm install -g appium
npm install wd
```
Nếu như Terminal báo không có quyền thực thi thì hãy dùng command sau để cấp quyền
```bash
sudo chmod -R a+w /usr/local
```
Và cuối cùng là run Appium trong terminal
```bash
appium&
```

