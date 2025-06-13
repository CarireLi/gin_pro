<!-- 初始化 -->
go mod init github.com/CarireLi/gin_pro.git

go mod tidy

ssh-keygen -t rsa -b 4096 -C "2459400814@qq.com"

<!-- 下载最新的GIN框架和依赖 -->
go get -u github.com/gin-gonic/gin

<!-- 配置用户 -->
git config --global user.email "2459400814@qq.com"
git config --global user.name "CarireLi"
  
  
git config --global user.name
git config --global user.email

