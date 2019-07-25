# gitlab安装步骤


## 1 安装最新版docker以及docker-compose

* 检查

```
# docker --version
Docker version 18.09.8, build 0dd43dd87f

# docker-compose --version
docker-compose version 1.24.0, build 0aa59064

```

## 2 获取安装配置

```
cd /disk/gitlab
git clone https://github.com/gnuhub/gitlab-docker.git
cd gitlab-docker

```

## 3 修改配置(7处)

```
vim docker-compose.yml
# 第5行
# 第8行
# 第9行
# 第13行
# 第14行
# 第19行
# 第22行
```

## 4 启动
```
cd /disk/gitlab/gitlab-docker
docker-compose up -d
```