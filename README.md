# n8n_docker
n8n學習

安裝
docker volume create n8n_data

docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n

更新
docker pull docker.n8n.io/n8nio/n8n
