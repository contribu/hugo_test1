

## install

```bash
cd $(mktemp -d)
wget https://github.com/gohugoio/hugo/releases/download/v0.42.1/hugo_0.42.1_Linux-64bit.tar.gz
tar -zxvf hugo_0.42.1_Linux-64bit.tar.gz
sudo mv hugo /usr/local/bin/
```

## initialize

```bash
hugo new site test1
```

## run

```bash
hugo server -D --bind="0.0.0.0"
```

## 問題

vagrantでpollingが使えないらしい
https://github.com/gohugoio/hugo/issues/2340