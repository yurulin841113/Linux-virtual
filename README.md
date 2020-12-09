# Linux虛擬機

## 更新
sudo apt update
sudo apt -y upgrade

## 建置Python環境
>pip確認有無pip

sudo apt -y install python3-pip
sudo pip3 install virtualenv

## 設定SSH & FTP
sudo apt -y install openssh-server
sudo apt -y install vsftpd

## git設定
>git 確認有無git

sudo apt install -y git
git config --global user.name "名字"
git config --global user.email "信箱"

## 建立django環境
python -m venv (取名字) OR virtualenv (取名字)
