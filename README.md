# Appium Android - Skype
Automation Test sử dụng Appium và ngôn ngữ Python

## Cài đặt
### Cài đặt Python
Sử dụng `Homebrew`
```zsh
brew install python
```
### Cài đặt Appium
Cài đặt node
```zsh
brew install node
```
Cài đặt appium package, không được chạy các command dưới quyền `sudo`
```zsh
npm install -g appium
npm install wd
```
Nếu như Terminal báo không có quyền thực thi thì hãy dùng command sau để cấp quyền
```zsh
sudo chmod -R a+w /usr/local
```
Và cuối cùng là run Appium trong terminal
```zsh
appium&
```

