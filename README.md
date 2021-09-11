Error: Package: docker-ce-17.12.0.ce-1.el7.centos.x86_64 (docker-ce-stable)
Requires: container-selinux >= 2.9
http://mirror.centos.org/centos/7/extras/x86_64/Packages/  

下载 container-selinux-2.119.2-1.911c772.el7_8.noarch.rpm
 rpm -ivh container-selinux-2.119.2-1.911c772.el7_8.noarch.rpm   还报错         
yum -y install selinux-policy selinux-policy-base selinux-policy-targeted
yum install policycoreutils-python
rpm -ivh container-selinux-2.119.2-1.911c772.el7_8.noarch.rpm 



