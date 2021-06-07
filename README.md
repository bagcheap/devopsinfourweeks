# devopsinfourweeks


## ROCKY LINUX COMMANDS
### [student@rocky83 devopsinfourweeks]$ history
    1.  sudo yum install vim git -y
    2.  git clone https://github.com/sandervanvugt/deveopsinfourweeks
    3.  git clone https://github.com/sandervanvugt/devopsinfourweeks
    4.  cd devopsinfourweeks/
    5.  ls
    6.  ./counter.sh 12
    7.  sudo dnf install epel-release
    8.  sudo dnf install -y ansible
    9.  sudo sh -c 'echo 192.168.29.85 ubuntu.example.com ubuntu >> /etc/hosts'
   10.  cat /etc/hosts
   11.  ping ubuntu
   12.  ssh-keygen
   13.  ssh-copy-id ubuntu
   14.  echo ubuntu >> inventory
   15.  ansible ubuntu -m ping -i inventory -u student
   16.  ansible ubuntu -m ping -i inventory -u student -K
   17.  history
   18.  sudo ls -l /root
   19.  ansible-doc -l
   20.  ansible ubuntu -u student -b -K -m user "name=linda" 
   21.  ansible ubuntu -u student -b -K -m user -a "name=linda" 
   22.  ansible ubuntu -u student -b -K -m package -a "name=nmap" 
   23.  ansible ubuntu -u student -b -K -m user -a "name=linda" 
   24.  vim ansible.cfg 
   25.  ls
   26.  vim deploy-webserver.yaml 
   27.  vim ans-deploy-webserver.yaml 
   28.  cd ..
   29.  git clone https://github.com/sandervanvugt/ansible-4h
   30.  git clone https://github.com/sandervanvugt/ansible-3h
   31.  cd ansible-3h/
   32.  ls
   33.  cd base/
   34.  ls
   35.  cd ../install/
   36.  ls
   37.  vim vsftpd.yml 
   38.  ansible-playbook vsftpd.yml 
   39.  vim inventory 
   40.  ansible-playbook vsftpd.yml 
   41.  vim ansible.cfg 
   42.  ansible-playbook vsftpd.yml 
   43.  sudo ls /root
   44.  ansible-playbook vsftpd.yml -K
   45.  cd ..
   46.  cd ansible-3h/install/
   47.  vim vsftpd.yml 
   48.  cd ../../devopsinfourweeks/
   49.  ls
   50.  vim ansible-ubuntu.yml 
   51.  ansible-playbook ansible-ubuntu.yml 
   52.  ansible-playbook ansible-ubuntu.yml -K
   53.  ./counter.sh 12
   54.  history


## UBUNTU COMMANDSstudent@student-virtual-machine:~$ history
    1.  sudo reboot
    2.  free -
    3.  free -m
    4.  apt install -y git vim
    5.  sudo apt install -y git vim
    6.  ip a
    7.  sudo reboot
    8.  id
    9.  docker run fedora
   10.  docker ps
   11.  docker ps -a
   12.  docker run nginx
   13.  docker run nginx -d
   14.  docker run -d nginx 
   15.  docker ps
   16.  ps fax | less
   17.  docker run -it fedora sh
   18.  docker ps
   19.  docker inspect fedora:latest | less
   20.  docker inspect lucid_agnesi 
   21.  docker run --name webserver --memory="128m" -d -p 8080:80 nginx
   22.  docker ps
   23.  curl localhost:8080
   24.  history
