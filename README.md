# Practice

root@ip-172-31-28-127:~/project3# history
    1  apt update -y
    2  clear
    3  apt get update -y
    4  docker ps
    5  systemctl status docker
    6  apt install docker.io -y
    7  docker version
    8  exit
    9  apt update -y
   10  clear
   11  docker version
   12  docker images
   13  docker pull httpd
   14  docker images
   15  lsof -i 80
   16  clear
   17  docker images
   18  lsof -i -P -n|grep "LISTEN"
   19  history
   20  apt install apache2 -y
   21  lsof -i -P -n|grep "LISTEN"
   22  docker images
   23  docker inspect httpd
   24  docker run -itd -p 82:80 httpd
   25  docker ps
   26  cd /usr/local/apache2/htdocs
   27  cd /usr
   28  cd local
   29  cd apache2
   30  ls
   31  cd include
   32  ls
   33  cd ..
   34  docker container ls
   35  docker inspect 04088226daa7
   36  cd /usr/local/apache2
   37  docker exec -it 04088226daa7 /bin/bash
   38  sudo docker ls
   39  sudo docker container ls
   40  lsof -i -P -n|grep LISTEN
   41  docker exec -it 4d5b82d341ab /bin/bash
   42  docker stats
   43  docker logs 4d5b82d341ab
   44  docker logs 04088226daa7
   45  docker images
   46  mkdir project1
   47  cd project1
   48  pwd
   49  vi Dockerfile
   50  ls
   51  cd project1
   52  ls
   53  vi Dockerfile
   54  ls
   55  cd project1
   56  docker images
   57  docker ps -a
   58  docker run -itd -p 82:80 httpd
   59  docker ps -a
   60  docker exec -it ba00906638e1 /bin/bash
   61  docker images
   62  docker ls
   63  docker images
   64  docker container ls
   65  docker run -itd -p 82:80 httpd_updated_image
   66  docker container ls
   67  docker -exec -it 44e2742c9f15 /bin/bash
   68  docker exec -it 44e2742c9f15 /bin/bash
   69  exit
   70  clear
   71  docker container ls
   72  docker logs 44e2742c9f15
   73  clear
   74  docker volume ls
   75  docker volume create newdocker-volume
   76  docker volume ls
   77  docker container ls
   78  docker run -itd --mount source=newdocker-volume,target=/user/local/apache2/htdocs-p 82:80 httpd_updated_image
   79  sudo docker run -itd --mount source=newdocker-volume,target=/user/local/apache2/htdocs-p 82:80 httpd_updated_image
   80  docker kill httpd_updated_image
   81  docker kill 44e2742c9f15
   82  docker container ls
   83  docker images
   84  docker run -itd --mount source=newdocker-volume,target=/user/local/apache2/htdocs-p 82:80 httpd_updated_image
   85  docker login
   86  docker volume ls
   87  clear
   88  docker ps
   89  docker voulme ls
   90  docker volume ls
   91  docker login --username=Narayanhari
   92  cd /usr/local/apache
   93  docker exec -it 8422c945de4f /bin/bash
   94  docker ps
   95  docker rm -f 8422
   96  docker ps
   97  docker volume ls
   98  docker run -itd --mount source=newdocker-volume,target=/usr/local/apache2/htdocs -p 82:80 httpd_updated_image 
   99  find / -name newdocker-volume
  100  cd /var/lib/docker/volumes/newdocker-volume
  101  ls -l
  102  cd _data
  103  ls -l
  104  cd /var/lib/docker/volumes/newdocker-volume/_data
  105  ls -l
  106  cat index.html
  107  cd /usr/local/apache2/htdocs
  108  docker container ls
  109  docker exec -it e8631d7f750c /bin/bash
  110  ls -l
  111  ls
  112  cat index.html
  113  docker ps
  114  docker exec -it e8631d7f750c /bin/bash
  115  ls
  116  docker exec -it e8631d7f750c /bin/bash
  117  ls -l
  118  cat index2.html
  119  docker ps
  120  docker rm -f e861
  121  docker ps
  122  docker rm -f e8631d7f750c
  123  docker ps
  124  ls -l
  125  docker images
  126  docker ps -a
  127  docker ps
  128  docker volume
  129  cd ..
  130  ls
  131  cd ..
  132  ls
  133  docker images
  134  docker run -itd --mount source=newdocker-volume,target=/usr/local/apache2/htdocs -p 82:80 httpd 2776f4da9d55
  135  docker run -itd 2776f4da9d55 
  136  docker ps -a
  137  docker ps
  138  docker run -itd --mount source=newdocker-volume,target=/usr/local/apache2/htdocs  httpd 2776f4da9d55
  139  docker exec -it 2776f4da9d55 /bin/bash
  140  docker run -itd --mount source=newdocker-volume,target=/usr/local/apache2/htdocs httpd b62748509f3c 
  141  docker ps
  142  docker kill b62748509f3c
  143  docker ps
  144  docker run -itd --mount source=newdocker-volume,target=/usr/local/apache2/htdocs -p 82:80 httpd
  145  docker ps
  146  docker exec -it 2f16d87a45a9 /bin/bash
  147  ls -l
  148  cd newdocker-volume
  149  ls
  150  cd _data
  151  ls
  152  ls
  153  cd project1
  154  ls
  155  vi Dockerfile
  156  pwd
  157  cd /root/project1
  158  ls
  159  vi Dockerfile
  160  cat Dockerfile
  161  vi index1.html
  162  vi index2.html
  163  ls -l
  164  docker ps
  165  vi Dockerfile
  166  docker build . -t httpd1
  167  docker images
  168  docker run -itd -p 82:80 httpd1
  169  lsof -i -P -n|grep LISTEN
  170  docker container ls
  171  docker kill 2f16d87a45a9
  172  docker container ls
  173  lsof -i -P -n|grep LISTEN
  174  docker images
  175  docker run -itd -p 82:80 httpd1
  176  docker container ls
  177  ls 0l
  178  ls -l
  179  cd project2
  180  ls -lrt
  181  cat Dockerfile
  182  vi Dockerfile
  183  docker build . -t ubuntu1
  184  ls
  185  cd Dockerfile
  186  ls -l
  187  cat Dockerfile
  188  cd ..
  189  cd project1
  190  ls
  191  cat Dockerfile
  192  cd ..
  193  ls
  194  cd project2
  195  ls
  196  vi index1234.html
  197  ls
  198  cat Dockerfile
  199  vi Dockerfile
  200  docker build . -t ubuntu1
  201  docker images
  202  docker run -itd -p 82:80 ubuntu1
  203  docker ps
  204  ls
  205  cd project2
  206  docker images
  207  docker inspect 310a5129d8ed
  208  docker ps
  209  docker inspect 8c22e358b306
  210  ls -l
  211  cd ..
  212  ls
  213  ls -l
  214  docker network ls
  215  docker inspect 850d1fb4783c
  216  docker network ls
  217  docker inspect 850d1fb4783c
  218  docker ls
  219  docker images
  220  docker inspect 8c22e358b3064a0f
  221  docker ps
  222  docker-compose version
  223  apt intall docker-compose -y
  224  docker-compose version
  225  apt install docker-compose -y
  226  ls
  227  cd project2
  228  ls
  229  vi Dockerfile
  230  vim Dockerfile
  231  cat Dockerfile
  232  docker voulume ls
  233  clear
  234  docker network ls
  235  docker-compose version
  236  ls
  237  cd project3
  238  docker ps
  239  docker -exec -it 2d54dec252af /bin/bash
  240  docker exec -it 2d54dec252af /bin/bash
  241  docker os
  242  docker ps
  243  docker exec -it c5c28e6954d5 /bin/bash
  244  docker images
  245  docker image tag wordpress:latest narayanhari/node-todo-cicd:wordpress_v1
  246  docker login
  247  docker image push narayanhari/node-todo-cicd:wordpress_v1
