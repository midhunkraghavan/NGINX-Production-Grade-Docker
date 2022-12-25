 ### Create Build
 
 * sudo docker build -t myweb .

 ### Run Build on Specified PORT

 * sudo docker run -p 4000:80 myweb

 ### Run Build on Specified PORT with attaching Volumes

 * sudo docker run -p 8000:80 -v $(pwd):/usr/share/nginx/html myweb
