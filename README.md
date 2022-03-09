# sleepy-catalogue

Proof of concept OGC API Records Crawable catalog

This is a nginx with few rules to emulate a catalog, that right now is based on static files on the file system (check /data folder)

To test just run

`docker-compose up -d`

Available enpoints are 

http://localhost/collections/masked_rec

http://localhost/collections/masked_rec/items

http://localhost/collections/masked_rec/items/{feature_id} <-- working on a rewrite rule to fix this





