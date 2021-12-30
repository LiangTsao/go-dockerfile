# go-dockerfile
Golang项目容器化Dockerfile

GOPROXY=https://goproxy.cn,direct

docker build -f Dockerfile -t test-go-docker:latest .

docker run -d -p 8080:8080 test-go-docker:latest

http://localhost:8080
