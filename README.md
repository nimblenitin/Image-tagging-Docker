# Image-tagging-Docker

Docker tags are mutable named references to Docker images, much like branch refs in Git. They make it easy to pull and run images, and for image authors to roll out updates automatically

Steps to tag a newly created image-

```

1. Tag an image referenced by Image ID
$ sudo docker tag IMAGE_ID demo/nginx_img:version1.0

2. Tag an image referenced by name
$ sudo docker tag IMAGE_NAME demo/nginx_img:version2.0

3. Tag an image referenced by name and tag
$ sudo docker tag IMAGE_NAME:IMAGE_TAG demo/nginx_img:version3.0.latest

4. Tag an image for a private repository
$ sudo docker tag IMAGE_ID myregistry:5000/demo/nginx_img:version4.0

5. Use below command to see the newly tagged image
$ sudo docker images

```
