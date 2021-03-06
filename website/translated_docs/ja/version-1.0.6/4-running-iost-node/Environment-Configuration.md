---
id: version-1.0.6-Environment-Configuration
title: 環境と設定
sidebar_label: 環境と設定
original_id: Environment-Configuration
---

## 前提条件

* Go 1.9 以上 (Go 1.11 推奨)
* `git-lfs` (v2.5.2 推奨)
* Rocksdb v5.14.3 以上
* Docker v18.06.0-ce 以上 (旧バージョンはテストしていません)

## 動作環境

現在のところ、開発には次の環境がサポートされています。

* [Mac OS X](#mac-os-x)
* [Ubuntu/Linux](#ubuntu-linux)
* [Docker](#docker)

## Mac OS X

### git-lfsのインストール

```
brew install git-lfs
git lfs install
```

### rocksdbのインストール

```
brew install rocksdb
```

### コンパイルとユニットテスト

```
git clone git@github.com:iost-official/go-iost.git
make build
make test
```

## Ubuntu/Linux

### git-lfsのインストール

```
brew install git-lfs
git lfs install
```

### rocksdbのインストール

```
apt install -y libgflags-dev libsnappy-dev zlib1g-dev libbz2-dev liblz4-dev libzstd-dev
git clone -b "v5.14.3" https://github.com/facebook/rocksdb.git && \
cd rocksdb && make static_lib && make install-static
```

### コンパイルとユニットテスト

```
git clone git@github.com:iost-official/go-iost.git
make build
make test
```

## Docker

### Dockerのインストール

#### Mac OS X

Refer to [Official Documents](https://docs.docker.com/docker-for-mac/install) to install on Mac OS X.

#### Ubuntu/Linux

Refer to [Official Documents](https://docs.docker.com/install/linux/docker-ce/ubuntu#install-using-the-repository) to install on Ubuntu.

### コンパイルとユニットテスト

```
git clone git@github.com:iost-official/go-iost.git
cd go-iost
docker run -it --rm -v $(pwd):/gopath/src/github.com/iost-official/go-iost iostio/iost-dev:1.0.0 make build
docker run -it --rm -v $(pwd):/gopath/src/github.com/iost-official/go-iost iostio/iost-dev:1.0.0 make test
```
