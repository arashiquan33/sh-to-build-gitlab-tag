# sh-to-build-gitlab-tag
使用shell脚本动态构建gitlab新tag并且自动升级package.json version


#!/bin/bash

## 脚本调用方法 ./build-tag.sh tag号
## eg: ./build-tag.sh v1.2.8

## 每次构建新版本之前创建新标签、版本号、推送标签到gitlab

## 2.创建新版本
## 3.打tag
## 4.推送tag
