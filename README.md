# webpagerecorder
web page recorder

<h2 align="center">Features</h2>
<p><p> 
  <ul>
<li>high performance recorder </li>
    <li>concurrent multiple page recorder </li>
    <li>record url </li>
    <li> convert webpage to video (mp4) </li>
    <li>restream  to rtmp live stream (youtube and other rtmp live )</li>    
     <li>record (webm mp4 mkv format) </li>
     <li>live (hls) </li>
</ul>
<p><p> 
<h2 align="center">install webpagerecorder</h2>
<p><p> 
 <pre>
 create folder for record file :
 $ mkdir -m 777 record
 run docker : 
 $ docker run   --network=host -v record:/home/ubuntu/Downloads  -v record:/home/ubuntu/wprNode/public/recordfile/    --name wpr alit771/webpagerecorder:v2.1
 </pre>

The software is installed open the chrome browser and enter the http://localhost:3000/list.html

<p><p> 
