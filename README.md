# play-with-proxy


## run git behind proxy network
  *git config --global http:proxy http://proxyserver.com:port
  *git clone http://link.repo.git
  
  
## install python-pip behind proxy network
  >pip --proxy http://proxyserver.com:port install package
  > python pip --proxy http://proxyserver.com:port install package
  
  
## apt update package behind proxy network
add file 'apt.conf' on directory '/etc/apt/'
  `Acquire::http::proxy "http://proxyserver.com:port";`
  `Acquire::https::proxy "https://proxyserver.com:port";`
