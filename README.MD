# 个人使用的 ansible 脚本集合
最大限度重用


## roles 介绍和使用

## 使用须知
1. 设定hosts,注意要设定要搭建的分组
2. 设定group_vars目录下指定分组的变量
3. 调用: ansible-playbook -i hosts site.yml --limit apt-mirror

## 测试环境
** aws ubuntu 14.04 **
ansible 1.7.2

## 功能介绍
* apt-mirror 实现搭建Ubuntu 源


todo:
* nginx 暂时只支持一个http站点定义
