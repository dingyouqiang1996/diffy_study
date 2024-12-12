- 课程地址: `http://b.jtthink.com/read.php?tid=1134`
- 文档: `https://docs.dify.ai/zh-hans`
- 功能:
  - Agent构建
  - AI workflow编排
  - RAG检索
  - 模型管理
- dify: `v0.10.1`
```
wget https://github.com/langgenius/dify/archive/refs/tags/0.11.0.zip
```
- `ubuntu` 安装docker
```shell
sudo apt-get update
sudo apt-get install ca-certificates curl
sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc
echo \
    "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
    $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
    sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
sudo docker run hello-world
```