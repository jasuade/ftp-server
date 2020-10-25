## FTP Server

FTP Concurrent Server in GO.
Available commands:

- ls
- cd ..
- get 'file'
- close

In order to run the server container:

$ docker run --rm --name=ftp -d -v /host/volume:/container/volume -p 5000:5000 ftp

NOTE: you have to create a shared volume in the container host machine otherwise the server can not access the files.
