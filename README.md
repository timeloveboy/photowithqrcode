## web模式 try this link

http://localhost:8005/makeimg?bg=京东广告图.jpg&x=648&y=207&width=220&height=220&qrtext=http://mxz.so/2u34

或者
http://localhost:8005/makeimg?bg=http://www.themeparx.com/img-worlds-of-adventure-143.jpg&x=648&y=207&width=220&height=220&qrtext=http://mxz.so/2u34

+ 查看您的背景图

http://localhost:8005/bgimg/京东广告图.jpg

http://localhost:8005/bgimg/抱抱广告图.jpg


## cmd模式

go run cmdapp.go -bg="bgimg/京东广告图.jpg" -out="bgimg/jd.png" -qrtext="yourlink" -x="648" -y="205" -w="220" -h="220" 

## 输出图片格式
png