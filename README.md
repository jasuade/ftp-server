## FTP Server

FTP Server created as an exersice to practice conurrency in GO.
Available commands:

- ls
- cd ..
- get 'file'
- close

In order to run the server container:

$ docker run --rm --name=ftp -d -v /host/volume:/container/volume -p 5000:5000 ftp