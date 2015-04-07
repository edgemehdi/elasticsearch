# elasticsearch
#pull the repo
sudo docker pull edgemehdi/elasticsearch

#Run the image
sudo docker run -d -p 9200:9200 edgemehdi/elasticsearch

#check in browser
http://localhost:9200/_plugin/head
