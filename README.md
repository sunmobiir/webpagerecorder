# webpagerecorder
web page recorder

 <pre>
 mkdir -m 777 record
 docker run   --network=host -v record:/home/ubuntu/Downloads  -v record:/home/ubuntu/wprNode/public/recordfile/    --name wpr alit771/webpagerecorder:v2.1
 </pre>

The software is installed open the chrome browser and enter the http://localhost:3000/list.html
