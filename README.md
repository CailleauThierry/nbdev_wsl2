# Project name here
> Summary description here.


This file will become your README and also the index of your documentation.

## Install

`pip install your_project_name`

## How to use

Fill me in please! Don't forget code examples:

```
1+1
```




    2



Quick addition to 00_core.ipynb which will before my Readme.md and my main page

Working on installing nbdev on WSL21 Ubuntu VERSION="20.04.2 LTS (Focal Fossa)"


neuradaiWalter Wiggins
Nov '20
SOLUTION: sudo apt-get install build-essential
Apparently, these “essential” libs were not installed by default in the WSL Ubuntu 20.04 distro…
Now everything works.

From <https://forums.fast.ai/t/fastpages-local-dev-on-wsl2-server-refused-to-connect/82069> 



thierry@TCAILLEAU-02:~$ python3 --version
Python 3.8.5


thierry@TCAILLEAU-02:~$ sudo apt install python3-pip
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  binutils binutils-common binutils-x86-64-linux-gnu build-essential cpp cpp-9 dpkg-dev fakeroot g++ g++-9 gcc gcc-9 gcc-9-base libalgorithm-diff-perl libalgorithm-diff-xs-perl libalgorithm-merge-perl libasan5 libatomic1 libbinutils libc-dev-bin libc6-dev
  libcc1-0 libcrypt-dev libctf-nobfd0 libctf0 libdpkg-perl libexpat1-dev libfakeroot libfile-fcntllock-perl libgcc-9-dev libgomp1 libisl22 libitm1 liblsan0 libmpc3 libpython3-dev libpython3.8-dev libquadmath0 libstdc++-9-dev libtsan0 libubsan1 linux-libc-dev
  make manpages-dev python-pip-whl python3-dev python3-wheel python3.8-dev zlib1g-dev
Suggested packages:
  binutils-doc cpp-doc gcc-9-locales debian-keyring g++-multilib g++-9-multilib gcc-9-doc gcc-multilib autoconf automake libtool flex bison gdb gcc-doc gcc-9-multilib glibc-doc bzr libstdc++-9-doc make-doc
The following NEW packages will be installed:
  binutils binutils-common binutils-x86-64-linux-gnu build-essential cpp cpp-9 dpkg-dev fakeroot g++ g++-9 gcc gcc-9 gcc-9-base libalgorithm-diff-perl libalgorithm-diff-xs-perl libalgorithm-merge-perl libasan5 libatomic1 libbinutils libc-dev-bin libc6-dev
  libcc1-0 libcrypt-dev libctf-nobfd0 libctf0 libdpkg-perl libexpat1-dev libfakeroot libfile-fcntllock-perl libgcc-9-dev libgomp1 libisl22 libitm1 liblsan0 libmpc3 libpython3-dev libpython3.8-dev libquadmath0 libstdc++-9-dev libtsan0 libubsan1 linux-libc-dev
  make manpages-dev python-pip-whl python3-dev python3-pip python3-wheel python3.8-dev zlib1g-dev
0 upgraded, 50 newly installed, 0 to remove and 0 not upgraded.
Need to get 10.3 MB/46.8 MB of archives.
After this operation, 200 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 binutils-common amd64 2.34-6ubuntu1.1 [207 kB]
Get:2 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 libbinutils amd64 2.34-6ubuntu1.1 [475 kB]
Get:3 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 libctf-nobfd0 amd64 2.34-6ubuntu1.1 [47.1 kB]
Get:4 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 libctf0 amd64 2.34-6ubuntu1.1 [46.6 kB]
Get:5 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 binutils-x86-64-linux-gnu amd64 2.34-6ubuntu1.1 [1613 kB]
Get:6 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 binutils amd64 2.34-6ubuntu1.1 [3380 B]
Get:7 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 linux-libc-dev amd64 5.4.0-71.79 [1127 kB]
Get:8 http://archive.ubuntu.com/ubuntu focal/main amd64 libexpat1-dev amd64 2.2.9-1build1 [116 kB]
Get:9 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 libpython3.8-dev amd64 3.8.5-1~20.04.2 [3942 kB]
Get:10 http://archive.ubuntu.com/ubuntu focal/main amd64 libpython3-dev amd64 3.8.2-0ubuntu2 [7236 B]
Get:11 http://archive.ubuntu.com/ubuntu focal-updates/universe amd64 python-pip-whl all 20.0.2-5ubuntu1.1 [1799 kB]
Get:12 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 zlib1g-dev amd64 1:1.2.11.dfsg-2ubuntu1.2 [155 kB]
Get:13 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 python3.8-dev amd64 3.8.5-1~20.04.2 [515 kB]
Get:14 http://archive.ubuntu.com/ubuntu focal/main amd64 python3-dev amd64 3.8.2-0ubuntu2 [1212 B]
Get:15 http://archive.ubuntu.com/ubuntu focal/universe amd64 python3-wheel all 0.34.2-1 [23.8 kB]
Get:16 http://archive.ubuntu.com/ubuntu focal-updates/universe amd64 python3-pip all 20.0.2-5ubuntu1.1 [230 kB]
Fetched 10.3 MB in 1s (16.4 MB/s)    
Extracting templates from packages: 100%
Selecting previously unselected package binutils-common:amd64.
(Reading database ... 32306 files and directories currently installed.)
Preparing to unpack .../00-binutils-common_2.34-6ubuntu1.1_amd64.deb ...
Unpacking binutils-common:amd64 (2.34-6ubuntu1.1) ...
Selecting previously unselected package libbinutils:amd64.
Preparing to unpack .../01-libbinutils_2.34-6ubuntu1.1_amd64.deb ...
Unpacking libbinutils:amd64 (2.34-6ubuntu1.1) ...
Selecting previously unselected package libctf-nobfd0:amd64.
Preparing to unpack .../02-libctf-nobfd0_2.34-6ubuntu1.1_amd64.deb ...
Unpacking libctf-nobfd0:amd64 (2.34-6ubuntu1.1) ...
Selecting previously unselected package libctf0:amd64.
Preparing to unpack .../03-libctf0_2.34-6ubuntu1.1_amd64.deb ...
Unpacking libctf0:amd64 (2.34-6ubuntu1.1) ...
Selecting previously unselected package binutils-x86-64-linux-gnu.
Preparing to unpack .../04-binutils-x86-64-linux-gnu_2.34-6ubuntu1.1_amd64.deb ...
Unpacking binutils-x86-64-linux-gnu (2.34-6ubuntu1.1) ...
Selecting previously unselected package binutils.
Preparing to unpack .../05-binutils_2.34-6ubuntu1.1_amd64.deb ...
Unpacking binutils (2.34-6ubuntu1.1) ...
Selecting previously unselected package libc-dev-bin.
Preparing to unpack .../06-libc-dev-bin_2.31-0ubuntu9.2_amd64.deb ...
Unpacking libc-dev-bin (2.31-0ubuntu9.2) ...
Selecting previously unselected package linux-libc-dev:amd64.
Preparing to unpack .../07-linux-libc-dev_5.4.0-71.79_amd64.deb ...
Unpacking linux-libc-dev:amd64 (5.4.0-71.79) ...
Selecting previously unselected package libcrypt-dev:amd64.
Preparing to unpack .../08-libcrypt-dev_1%3a4.4.10-10ubuntu4_amd64.deb ...
Unpacking libcrypt-dev:amd64 (1:4.4.10-10ubuntu4) ...
Selecting previously unselected package libc6-dev:amd64.
Preparing to unpack .../09-libc6-dev_2.31-0ubuntu9.2_amd64.deb ...
Unpacking libc6-dev:amd64 (2.31-0ubuntu9.2) ...
Selecting previously unselected package gcc-9-base:amd64.
Preparing to unpack .../10-gcc-9-base_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking gcc-9-base:amd64 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package libisl22:amd64.
Preparing to unpack .../11-libisl22_0.22.1-1_amd64.deb ...
Unpacking libisl22:amd64 (0.22.1-1) ...
Selecting previously unselected package libmpc3:amd64.
Preparing to unpack .../12-libmpc3_1.1.0-1_amd64.deb ...
Unpacking libmpc3:amd64 (1.1.0-1) ...
Selecting previously unselected package cpp-9.
Preparing to unpack .../13-cpp-9_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking cpp-9 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package cpp.
Preparing to unpack .../14-cpp_4%3a9.3.0-1ubuntu2_amd64.deb ...
Unpacking cpp (4:9.3.0-1ubuntu2) ...
Selecting previously unselected package libcc1-0:amd64.
Preparing to unpack .../15-libcc1-0_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libcc1-0:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libgomp1:amd64.
Preparing to unpack .../16-libgomp1_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libgomp1:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libitm1:amd64.
Preparing to unpack .../17-libitm1_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libitm1:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libatomic1:amd64.
Preparing to unpack .../18-libatomic1_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libatomic1:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libasan5:amd64.
Preparing to unpack .../19-libasan5_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking libasan5:amd64 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package liblsan0:amd64.
Preparing to unpack .../20-liblsan0_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking liblsan0:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libtsan0:amd64.
Preparing to unpack .../21-libtsan0_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libtsan0:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libubsan1:amd64.
Preparing to unpack .../22-libubsan1_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libubsan1:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libquadmath0:amd64.
Preparing to unpack .../23-libquadmath0_10.2.0-5ubuntu1~20.04_amd64.deb ...
Unpacking libquadmath0:amd64 (10.2.0-5ubuntu1~20.04) ...
Selecting previously unselected package libgcc-9-dev:amd64.
Preparing to unpack .../24-libgcc-9-dev_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking libgcc-9-dev:amd64 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package gcc-9.
Preparing to unpack .../25-gcc-9_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking gcc-9 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package gcc.
Preparing to unpack .../26-gcc_4%3a9.3.0-1ubuntu2_amd64.deb ...
Unpacking gcc (4:9.3.0-1ubuntu2) ...
Selecting previously unselected package libstdc++-9-dev:amd64.
Preparing to unpack .../27-libstdc++-9-dev_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking libstdc++-9-dev:amd64 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package g++-9.
Preparing to unpack .../28-g++-9_9.3.0-17ubuntu1~20.04_amd64.deb ...
Unpacking g++-9 (9.3.0-17ubuntu1~20.04) ...
Selecting previously unselected package g++.
Preparing to unpack .../29-g++_4%3a9.3.0-1ubuntu2_amd64.deb ...
Unpacking g++ (4:9.3.0-1ubuntu2) ...
Selecting previously unselected package make.
Preparing to unpack .../30-make_4.2.1-1.2_amd64.deb ...
Unpacking make (4.2.1-1.2) ...
Selecting previously unselected package libdpkg-perl.
Preparing to unpack .../31-libdpkg-perl_1.19.7ubuntu3_all.deb ...
Unpacking libdpkg-perl (1.19.7ubuntu3) ...
Selecting previously unselected package dpkg-dev.
Preparing to unpack .../32-dpkg-dev_1.19.7ubuntu3_all.deb ...
Unpacking dpkg-dev (1.19.7ubuntu3) ...
Selecting previously unselected package build-essential.
Preparing to unpack .../33-build-essential_12.8ubuntu1.1_amd64.deb ...
Unpacking build-essential (12.8ubuntu1.1) ...
Selecting previously unselected package libfakeroot:amd64.
Preparing to unpack .../34-libfakeroot_1.24-1_amd64.deb ...
Unpacking libfakeroot:amd64 (1.24-1) ...
Selecting previously unselected package fakeroot.
Preparing to unpack .../35-fakeroot_1.24-1_amd64.deb ...
Unpacking fakeroot (1.24-1) ...
Selecting previously unselected package libalgorithm-diff-perl.
Preparing to unpack .../36-libalgorithm-diff-perl_1.19.03-2_all.deb ...
Unpacking libalgorithm-diff-perl (1.19.03-2) ...
Selecting previously unselected package libalgorithm-diff-xs-perl.
Preparing to unpack .../37-libalgorithm-diff-xs-perl_0.04-6_amd64.deb ...
Unpacking libalgorithm-diff-xs-perl (0.04-6) ...
Selecting previously unselected package libalgorithm-merge-perl.
Preparing to unpack .../38-libalgorithm-merge-perl_0.08-3_all.deb ...
Unpacking libalgorithm-merge-perl (0.08-3) ...
Selecting previously unselected package libexpat1-dev:amd64.
Preparing to unpack .../39-libexpat1-dev_2.2.9-1build1_amd64.deb ...
Unpacking libexpat1-dev:amd64 (2.2.9-1build1) ...
Selecting previously unselected package libfile-fcntllock-perl.
Preparing to unpack .../40-libfile-fcntllock-perl_0.22-3build4_amd64.deb ...
Unpacking libfile-fcntllock-perl (0.22-3build4) ...
Selecting previously unselected package libpython3.8-dev:amd64.
Preparing to unpack .../41-libpython3.8-dev_3.8.5-1~20.04.2_amd64.deb ...
Unpacking libpython3.8-dev:amd64 (3.8.5-1~20.04.2) ...
Selecting previously unselected package libpython3-dev:amd64.
Preparing to unpack .../42-libpython3-dev_3.8.2-0ubuntu2_amd64.deb ...
Unpacking libpython3-dev:amd64 (3.8.2-0ubuntu2) ...
Selecting previously unselected package manpages-dev.
Preparing to unpack .../43-manpages-dev_5.05-1_all.deb ...
Unpacking manpages-dev (5.05-1) ...
Selecting previously unselected package python-pip-whl.
Preparing to unpack .../44-python-pip-whl_20.0.2-5ubuntu1.1_all.deb ...
Unpacking python-pip-whl (20.0.2-5ubuntu1.1) ...
Selecting previously unselected package zlib1g-dev:amd64.
Preparing to unpack .../45-zlib1g-dev_1%3a1.2.11.dfsg-2ubuntu1.2_amd64.deb ...
Unpacking zlib1g-dev:amd64 (1:1.2.11.dfsg-2ubuntu1.2) ...
Selecting previously unselected package python3.8-dev.
Preparing to unpack .../46-python3.8-dev_3.8.5-1~20.04.2_amd64.deb ...
Unpacking python3.8-dev (3.8.5-1~20.04.2) ...
Selecting previously unselected package python3-dev.
Preparing to unpack .../47-python3-dev_3.8.2-0ubuntu2_amd64.deb ...
Unpacking python3-dev (3.8.2-0ubuntu2) ...
Selecting previously unselected package python3-wheel.
Preparing to unpack .../48-python3-wheel_0.34.2-1_all.deb ...
Unpacking python3-wheel (0.34.2-1) ...
Selecting previously unselected package python3-pip.
Preparing to unpack .../49-python3-pip_20.0.2-5ubuntu1.1_all.deb ...
Unpacking python3-pip (20.0.2-5ubuntu1.1) ...
Setting up manpages-dev (5.05-1) ...
Setting up libfile-fcntllock-perl (0.22-3build4) ...
Setting up libalgorithm-diff-perl (1.19.03-2) ...
Setting up binutils-common:amd64 (2.34-6ubuntu1.1) ...
Setting up linux-libc-dev:amd64 (5.4.0-71.79) ...
Setting up libctf-nobfd0:amd64 (2.34-6ubuntu1.1) ...
Setting up libgomp1:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up python3-wheel (0.34.2-1) ...
Setting up libfakeroot:amd64 (1.24-1) ...
Setting up fakeroot (1.24-1) ...
update-alternatives: using /usr/bin/fakeroot-sysv to provide /usr/bin/fakeroot (fakeroot) in auto mode
Setting up make (4.2.1-1.2) ...
Setting up libquadmath0:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up libmpc3:amd64 (1.1.0-1) ...
Setting up libatomic1:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up libdpkg-perl (1.19.7ubuntu3) ...
Setting up libubsan1:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up libcrypt-dev:amd64 (1:4.4.10-10ubuntu4) ...
Setting up libisl22:amd64 (0.22.1-1) ...
Setting up python-pip-whl (20.0.2-5ubuntu1.1) ...
Setting up libbinutils:amd64 (2.34-6ubuntu1.1) ...
Setting up libc-dev-bin (2.31-0ubuntu9.2) ...
Setting up libalgorithm-diff-xs-perl (0.04-6) ...
Setting up libcc1-0:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up liblsan0:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up libitm1:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up gcc-9-base:amd64 (9.3.0-17ubuntu1~20.04) ...
Setting up libalgorithm-merge-perl (0.08-3) ...
Setting up libtsan0:amd64 (10.2.0-5ubuntu1~20.04) ...
Setting up libctf0:amd64 (2.34-6ubuntu1.1) ...
Setting up libasan5:amd64 (9.3.0-17ubuntu1~20.04) ...
Setting up python3-pip (20.0.2-5ubuntu1.1) ...
Setting up cpp-9 (9.3.0-17ubuntu1~20.04) ...
Setting up libc6-dev:amd64 (2.31-0ubuntu9.2) ...
Setting up binutils-x86-64-linux-gnu (2.34-6ubuntu1.1) ...
Setting up binutils (2.34-6ubuntu1.1) ...
Setting up dpkg-dev (1.19.7ubuntu3) ...
Setting up libgcc-9-dev:amd64 (9.3.0-17ubuntu1~20.04) ...
Setting up libexpat1-dev:amd64 (2.2.9-1build1) ...
Setting up libpython3.8-dev:amd64 (3.8.5-1~20.04.2) ...
Setting up zlib1g-dev:amd64 (1:1.2.11.dfsg-2ubuntu1.2) ...
Setting up cpp (4:9.3.0-1ubuntu2) ...
Setting up gcc-9 (9.3.0-17ubuntu1~20.04) ...
Setting up libpython3-dev:amd64 (3.8.2-0ubuntu2) ...
Setting up libstdc++-9-dev:amd64 (9.3.0-17ubuntu1~20.04) ...
Setting up gcc (4:9.3.0-1ubuntu2) ...
Setting up g++-9 (9.3.0-17ubuntu1~20.04) ...
Setting up python3.8-dev (3.8.5-1~20.04.2) ...
Setting up g++ (4:9.3.0-1ubuntu2) ...
update-alternatives: using /usr/bin/g++ to provide /usr/bin/c++ (c++) in auto mode
Setting up build-essential (12.8ubuntu1.1) ...
Setting up python3-dev (3.8.2-0ubuntu2) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.2) ...
thierry@TCAILLEAU-02:~$ pip install jupyter

Command 'pip' not found, but there are 18 similar ones.

thierry@TCAILLEAU-02:~$ pip3 install jupyter
Collecting jupyter
  Downloading jupyter-1.0.0-py2.py3-none-any.whl (2.7 kB)
Collecting jupyter-console
  Downloading jupyter_console-6.4.0-py3-none-any.whl (22 kB)
Collecting qtconsole
  Downloading qtconsole-5.0.3-py3-none-any.whl (119 kB)
     |████████████████████████████████| 119 kB 20.5 MB/s 
Collecting notebook
  Downloading notebook-6.3.0-py3-none-any.whl (9.5 MB)
     |████████████████████████████████| 9.5 MB 27.3 MB/s 
Collecting ipywidgets
  Downloading ipywidgets-7.6.3-py2.py3-none-any.whl (121 kB)
     |████████████████████████████████| 121 kB 42.4 MB/s 
Collecting ipykernel
  Downloading ipykernel-5.5.3-py3-none-any.whl (120 kB)
     |████████████████████████████████| 120 kB 34.4 MB/s 
Collecting nbconvert
  Downloading nbconvert-6.0.7-py3-none-any.whl (552 kB)
     |████████████████████████████████| 552 kB 37.1 MB/s 
Collecting prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0
  Downloading prompt_toolkit-3.0.18-py3-none-any.whl (367 kB)
     |████████████████████████████████| 367 kB 32.5 MB/s 
Collecting ipython
  Downloading ipython-7.22.0-py3-none-any.whl (785 kB)
     |████████████████████████████████| 785 kB 8.4 MB/s 
Collecting pygments
  Downloading Pygments-2.8.1-py3-none-any.whl (983 kB)
     |████████████████████████████████| 983 kB 28.7 MB/s 
Collecting jupyter-client
  Downloading jupyter_client-6.1.12-py3-none-any.whl (112 kB)
     |████████████████████████████████| 112 kB 33.2 MB/s 
Collecting traitlets
  Downloading traitlets-5.0.5-py3-none-any.whl (100 kB)
     |████████████████████████████████| 100 kB 6.5 MB/s 
Collecting qtpy
  Downloading QtPy-1.9.0-py2.py3-none-any.whl (54 kB)
     |████████████████████████████████| 54 kB 1.9 MB/s 
Collecting jupyter-core
  Downloading jupyter_core-4.7.1-py3-none-any.whl (82 kB)
     |████████████████████████████████| 82 kB 814 kB/s 
Collecting ipython-genutils
  Downloading ipython_genutils-0.2.0-py2.py3-none-any.whl (26 kB)
Collecting pyzmq>=17.1
  Downloading pyzmq-22.0.3-cp38-cp38-manylinux2010_x86_64.whl (1.1 MB)
     |████████████████████████████████| 1.1 MB 40.5 MB/s 
Collecting tornado>=6.1
  Downloading tornado-6.1-cp38-cp38-manylinux2010_x86_64.whl (427 kB)
     |████████████████████████████████| 427 kB 26.2 MB/s 
Collecting argon2-cffi
  Downloading argon2_cffi-20.1.0-cp35-abi3-manylinux1_x86_64.whl (97 kB)
     |████████████████████████████████| 97 kB 4.6 MB/s 
Requirement already satisfied: jinja2 in /usr/lib/python3/dist-packages (from notebook->jupyter) (2.10.1)
Collecting nbformat
  Downloading nbformat-5.1.3-py3-none-any.whl (178 kB)
     |████████████████████████████████| 178 kB 27.0 MB/s 
Collecting prometheus-client
  Downloading prometheus_client-0.10.1-py2.py3-none-any.whl (55 kB)
     |████████████████████████████████| 55 kB 2.4 MB/s 
Collecting Send2Trash>=1.5.0
  Downloading Send2Trash-1.5.0-py3-none-any.whl (12 kB)
Collecting terminado>=0.8.3
  Downloading terminado-0.9.4-py3-none-any.whl (14 kB)
Collecting jupyterlab-widgets>=1.0.0; python_version >= "3.6"
  Downloading jupyterlab_widgets-1.0.0-py3-none-any.whl (243 kB)
     |████████████████████████████████| 243 kB 34.3 MB/s 
Collecting widgetsnbextension~=3.5.0
  Downloading widgetsnbextension-3.5.1-py2.py3-none-any.whl (2.2 MB)
     |████████████████████████████████| 2.2 MB 36.2 MB/s 
Requirement already satisfied: entrypoints>=0.2.2 in /usr/lib/python3/dist-packages (from nbconvert->jupyter) (0.3)
Collecting jupyterlab-pygments
  Downloading jupyterlab_pygments-0.1.2-py2.py3-none-any.whl (4.6 kB)
Collecting bleach
  Downloading bleach-3.3.0-py2.py3-none-any.whl (283 kB)
     |████████████████████████████████| 283 kB 42.8 MB/s 
Collecting pandocfilters>=1.4.1
  Downloading pandocfilters-1.4.3.tar.gz (16 kB)
Collecting testpath
  Downloading testpath-0.4.4-py2.py3-none-any.whl (163 kB)
     |████████████████████████████████| 163 kB 40.4 MB/s 
Collecting defusedxml
  Downloading defusedxml-0.7.1-py2.py3-none-any.whl (25 kB)
Collecting mistune<2,>=0.8.1
  Downloading mistune-0.8.4-py2.py3-none-any.whl (16 kB)
Collecting nbclient<0.6.0,>=0.5.0
  Downloading nbclient-0.5.3-py3-none-any.whl (82 kB)
     |████████████████████████████████| 82 kB 591 kB/s 
Collecting wcwidth
  Downloading wcwidth-0.2.5-py2.py3-none-any.whl (30 kB)
Collecting jedi>=0.16
  Downloading jedi-0.18.0-py2.py3-none-any.whl (1.4 MB)
     |████████████████████████████████| 1.4 MB 42.8 MB/s 
Collecting decorator
  Downloading decorator-5.0.7-py3-none-any.whl (8.8 kB)
Collecting backcall
  Downloading backcall-0.2.0-py2.py3-none-any.whl (11 kB)
Requirement already satisfied: setuptools>=18.5 in /usr/lib/python3/dist-packages (from ipython->jupyter-console->jupyter) (45.2.0)
Collecting pickleshare
  Downloading pickleshare-0.7.5-py2.py3-none-any.whl (6.9 kB)
Requirement already satisfied: pexpect>4.3; sys_platform != "win32" in /usr/lib/python3/dist-packages (from ipython->jupyter-console->jupyter) (4.6.0)
Collecting python-dateutil>=2.1
  Downloading python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
     |████████████████████████████████| 227 kB 34.9 MB/s 
Collecting cffi>=1.0.0
  Downloading cffi-1.14.5-cp38-cp38-manylinux1_x86_64.whl (411 kB)
     |████████████████████████████████| 411 kB 26.6 MB/s 
Requirement already satisfied: six in /usr/lib/python3/dist-packages (from argon2-cffi->notebook->jupyter) (1.14.0)
Requirement already satisfied: jsonschema!=2.5.0,>=2.4 in /usr/lib/python3/dist-packages (from nbformat->notebook->jupyter) (3.2.0)
Collecting ptyprocess; os_name != "nt"
  Downloading ptyprocess-0.7.0-py2.py3-none-any.whl (13 kB)
Collecting packaging
  Downloading packaging-20.9-py2.py3-none-any.whl (40 kB)
     |████████████████████████████████| 40 kB 3.7 MB/s 
Collecting webencodings
  Downloading webencodings-0.5.1-py2.py3-none-any.whl (11 kB)
Collecting nest-asyncio
  Downloading nest_asyncio-1.5.1-py3-none-any.whl (5.0 kB)
Collecting async-generator
  Downloading async_generator-1.10-py3-none-any.whl (18 kB)
Collecting parso<0.9.0,>=0.8.0
  Downloading parso-0.8.2-py2.py3-none-any.whl (94 kB)
     |████████████████████████████████| 94 kB 1.9 MB/s 
Collecting pycparser
  Downloading pycparser-2.20-py2.py3-none-any.whl (112 kB)
     |████████████████████████████████| 112 kB 45.4 MB/s 
Collecting pyparsing>=2.0.2
  Downloading pyparsing-2.4.7-py2.py3-none-any.whl (67 kB)
     |████████████████████████████████| 67 kB 3.4 MB/s 
Building wheels for collected packages: pandocfilters
  Building wheel for pandocfilters (setup.py) ... done
  Created wheel for pandocfilters: filename=pandocfilters-1.4.3-py3-none-any.whl size=7991 sha256=50b25bc216562c2dc2d6183ef0f3e19a5fa775463342a482c98c025199b007e5
  Stored in directory: /home/thierry/.cache/pip/wheels/fc/39/52/8d6f3cec1cca4ceb44d658427c35711b19d89dbc4914af657f
Successfully built pandocfilters
Installing collected packages: wcwidth, prompt-toolkit, ipython-genutils, traitlets, parso, jedi, decorator, backcall, pygments, pickleshare, ipython, tornado, python-dateutil, jupyter-core, pyzmq, jupyter-client, ipykernel, jupyter-console, qtpy, qtconsole, pycparser, cffi, argon2-cffi, nbformat, prometheus-client, Send2Trash, ptyprocess, terminado, jupyterlab-pygments, pyparsing, packaging, webencodings, bleach, pandocfilters, testpath, defusedxml, mistune, nest-asyncio, async-generator, nbclient, nbconvert, notebook, jupyterlab-widgets, widgetsnbextension, ipywidgets, jupyter
  WARNING: The script pygmentize is installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts iptest, iptest3, ipython and ipython3 are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts jupyter, jupyter-migrate and jupyter-troubleshoot are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts jupyter-kernel, jupyter-kernelspec and jupyter-run are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script jupyter-console is installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script jupyter-trust is installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script jupyter-nbconvert is installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts jupyter-bundlerextension, jupyter-nbextension, jupyter-notebook and jupyter-serverextension are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed Send2Trash-1.5.0 argon2-cffi-20.1.0 async-generator-1.10 backcall-0.2.0 bleach-3.3.0 cffi-1.14.5 decorator-5.0.7 defusedxml-0.7.1 ipykernel-5.5.3 ipython-7.22.0 ipython-genutils-0.2.0 ipywidgets-7.6.3 jedi-0.18.0 jupyter-1.0.0 jupyter-client-6.1.12 jupyter-console-6.4.0 jupyter-core-4.7.1 jupyterlab-pygments-0.1.2 jupyterlab-widgets-1.0.0 mistune-0.8.4 nbclient-0.5.3 nbconvert-6.0.7 nbformat-5.1.3 nest-asyncio-1.5.1 notebook-6.3.0 packaging-20.9 pandocfilters-1.4.3 parso-0.8.2 pickleshare-0.7.5 prometheus-client-0.10.1 prompt-toolkit-3.0.18 ptyprocess-0.7.0 pycparser-2.20 pygments-2.8.1 pyparsing-2.4.7 python-dateutil-2.8.1 pyzmq-22.0.3 qtconsole-5.0.3 qtpy-1.9.0 terminado-0.9.4 testpath-0.4.4 tornado-6.1 traitlets-5.0.5 wcwidth-0.2.5 webencodings-0.5.1 widgetsnbextension-3.5.1


thierry@TCAILLEAU-02:~$ pip3 install nbdev
Collecting nbdev
  Downloading nbdev-1.1.14-py3-none-any.whl (46 kB)
     |████████████████████████████████| 46 kB 1.4 MB/s 
Requirement already satisfied: pyyaml in /usr/lib/python3/dist-packages (from nbdev) (5.3.1)
Requirement already satisfied: jupyter in ./.local/lib/python3.8/site-packages (from nbdev) (1.0.0)
Requirement already satisfied: nbformat>=4.4.0 in ./.local/lib/python3.8/site-packages (from nbdev) (5.1.3)
Collecting nbconvert<6
  Downloading nbconvert-5.6.1-py2.py3-none-any.whl (455 kB)
     |████████████████████████████████| 455 kB 18.5 MB/s 
Requirement already satisfied: ipykernel in ./.local/lib/python3.8/site-packages (from nbdev) (5.5.3)
Collecting fastcore>=1.3.19
  Downloading fastcore-1.3.19-py3-none-any.whl (53 kB)
     |████████████████████████████████| 53 kB 774 kB/s 
Collecting ghapi
  Downloading ghapi-0.1.16-py3-none-any.whl (49 kB)
     |████████████████████████████████| 49 kB 3.8 MB/s 
Collecting fastrelease
  Downloading fastrelease-0.1.11-py3-none-any.whl (16 kB)
Requirement already satisfied: pip in /usr/lib/python3/dist-packages (from nbdev) (20.0.2)
Requirement already satisfied: jupyter-client<=6.1.12 in ./.local/lib/python3.8/site-packages (from nbdev) (6.1.12)
Requirement already satisfied: packaging in ./.local/lib/python3.8/site-packages (from nbdev) (20.9)
Requirement already satisfied: qtconsole in ./.local/lib/python3.8/site-packages (from jupyter->nbdev) (5.0.3)
Requirement already satisfied: ipywidgets in ./.local/lib/python3.8/site-packages (from jupyter->nbdev) (7.6.3)
Requirement already satisfied: jupyter-console in ./.local/lib/python3.8/site-packages (from jupyter->nbdev) (6.4.0)
Requirement already satisfied: notebook in ./.local/lib/python3.8/site-packages (from jupyter->nbdev) (6.3.0)
Requirement already satisfied: ipython-genutils in ./.local/lib/python3.8/site-packages (from nbformat>=4.4.0->nbdev) (0.2.0)
Requirement already satisfied: jupyter-core in ./.local/lib/python3.8/site-packages (from nbformat>=4.4.0->nbdev) (4.7.1)
Requirement already satisfied: jsonschema!=2.5.0,>=2.4 in /usr/lib/python3/dist-packages (from nbformat>=4.4.0->nbdev) (3.2.0)
Requirement already satisfied: traitlets>=4.1 in ./.local/lib/python3.8/site-packages (from nbformat>=4.4.0->nbdev) (5.0.5)
Requirement already satisfied: pygments in ./.local/lib/python3.8/site-packages (from nbconvert<6->nbdev) (2.8.1)
Requirement already satisfied: bleach in ./.local/lib/python3.8/site-packages (from nbconvert<6->nbdev) (3.3.0)
Requirement already satisfied: pandocfilters>=1.4.1 in ./.local/lib/python3.8/site-packages (from nbconvert<6->nbdev) (1.4.3)
Requirement already satisfied: jinja2>=2.4 in /usr/lib/python3/dist-packages (from nbconvert<6->nbdev) (2.10.1)
Requirement already satisfied: defusedxml in ./.local/lib/python3.8/site-packages (from nbconvert<6->nbdev) (0.7.1)
Requirement already satisfied: testpath in ./.local/lib/python3.8/site-packages (from nbconvert<6->nbdev) (0.4.4)
Requirement already satisfied: entrypoints>=0.2.2 in /usr/lib/python3/dist-packages (from nbconvert<6->nbdev) (0.3)
Requirement already satisfied: mistune<2,>=0.8.1 in ./.local/lib/python3.8/site-packages (from nbconvert<6->nbdev) (0.8.4)
Requirement already satisfied: ipython>=5.0.0 in ./.local/lib/python3.8/site-packages (from ipykernel->nbdev) (7.22.0)
Requirement already satisfied: tornado>=4.2 in ./.local/lib/python3.8/site-packages (from ipykernel->nbdev) (6.1)
Requirement already satisfied: pyzmq>=13 in ./.local/lib/python3.8/site-packages (from jupyter-client<=6.1.12->nbdev) (22.0.3)
Requirement already satisfied: python-dateutil>=2.1 in ./.local/lib/python3.8/site-packages (from jupyter-client<=6.1.12->nbdev) (2.8.1)
Requirement already satisfied: pyparsing>=2.0.2 in ./.local/lib/python3.8/site-packages (from packaging->nbdev) (2.4.7)
Requirement already satisfied: qtpy in ./.local/lib/python3.8/site-packages (from qtconsole->jupyter->nbdev) (1.9.0)
Requirement already satisfied: jupyterlab-widgets>=1.0.0; python_version >= "3.6" in ./.local/lib/python3.8/site-packages (from ipywidgets->jupyter->nbdev) (1.0.0)
Requirement already satisfied: widgetsnbextension~=3.5.0 in ./.local/lib/python3.8/site-packages (from ipywidgets->jupyter->nbdev) (3.5.1)
Requirement already satisfied: prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0 in ./.local/lib/python3.8/site-packages (from jupyter-console->jupyter->nbdev) (3.0.18)
Requirement already satisfied: argon2-cffi in ./.local/lib/python3.8/site-packages (from notebook->jupyter->nbdev) (20.1.0)
Requirement already satisfied: Send2Trash>=1.5.0 in ./.local/lib/python3.8/site-packages (from notebook->jupyter->nbdev) (1.5.0)
Requirement already satisfied: terminado>=0.8.3 in ./.local/lib/python3.8/site-packages (from notebook->jupyter->nbdev) (0.9.4)
Requirement already satisfied: prometheus-client in ./.local/lib/python3.8/site-packages (from notebook->jupyter->nbdev) (0.10.1)
Requirement already satisfied: webencodings in ./.local/lib/python3.8/site-packages (from bleach->nbconvert<6->nbdev) (0.5.1)
Requirement already satisfied: six>=1.9.0 in /usr/lib/python3/dist-packages (from bleach->nbconvert<6->nbdev) (1.14.0)
Requirement already satisfied: jedi>=0.16 in ./.local/lib/python3.8/site-packages (from ipython>=5.0.0->ipykernel->nbdev) (0.18.0)
Requirement already satisfied: pexpect>4.3; sys_platform != "win32" in /usr/lib/python3/dist-packages (from ipython>=5.0.0->ipykernel->nbdev) (4.6.0)
Requirement already satisfied: setuptools>=18.5 in /usr/lib/python3/dist-packages (from ipython>=5.0.0->ipykernel->nbdev) (45.2.0)
Requirement already satisfied: backcall in ./.local/lib/python3.8/site-packages (from ipython>=5.0.0->ipykernel->nbdev) (0.2.0)
Requirement already satisfied: pickleshare in ./.local/lib/python3.8/site-packages (from ipython>=5.0.0->ipykernel->nbdev) (0.7.5)
Requirement already satisfied: decorator in ./.local/lib/python3.8/site-packages (from ipython>=5.0.0->ipykernel->nbdev) (5.0.7)
Requirement already satisfied: wcwidth in ./.local/lib/python3.8/site-packages (from prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0->jupyter-console->jupyter->nbdev) (0.2.5)
Requirement already satisfied: cffi>=1.0.0 in ./.local/lib/python3.8/site-packages (from argon2-cffi->notebook->jupyter->nbdev) (1.14.5)
Requirement already satisfied: ptyprocess; os_name != "nt" in ./.local/lib/python3.8/site-packages (from terminado>=0.8.3->notebook->jupyter->nbdev) (0.7.0)
Requirement already satisfied: parso<0.9.0,>=0.8.0 in ./.local/lib/python3.8/site-packages (from jedi>=0.16->ipython>=5.0.0->ipykernel->nbdev) (0.8.2)
Requirement already satisfied: pycparser in ./.local/lib/python3.8/site-packages (from cffi>=1.0.0->argon2-cffi->notebook->jupyter->nbdev) (2.20)
Installing collected packages: nbconvert, fastcore, ghapi, fastrelease, nbdev
  Attempting uninstall: nbconvert
    Found existing installation: nbconvert 6.0.7
    Uninstalling nbconvert-6.0.7:
      Successfully uninstalled nbconvert-6.0.7
  WARNING: The script jupyter-nbconvert is installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts completion-ghapi, gh-create-workflow, ghapi, ghpath and ghraw are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts fastrelease, fastrelease_bump_version, fastrelease_changelog, fastrelease_conda_package and fastrelease_release are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts nbdev_build_docs, nbdev_build_lib, nbdev_bump_version, nbdev_clean_nbs, nbdev_detach, nbdev_diff_nbs, nbdev_fix_merge, nbdev_install_git_hooks, nbdev_nb2md, nbdev_new, nbdev_read_nbs, nbdev_test_nbs, nbdev_trust_nbs and nbdev_update_lib are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed fastcore-1.3.19 fastrelease-0.1.11 ghapi-0.1.16 nbconvert-5.6.1 nbdev-1.1.14
thierry@TCAILLEAU-02:~$ 
-----------

thierry@TCAILLEAU-02:~$ pip3 install gh-cli
Collecting gh-cli
  Downloading gh-cli-0.1.b.tar.gz (25 kB)
Collecting github3.py>=0.2
  Downloading github3.py-2.0.0-py2.py3-none-any.whl (148 kB)
     |████████████████████████████████| 148 kB 18.9 MB/s 
Requirement already satisfied: python-dateutil>=2.6.0 in ./.local/lib/python3.8/site-packages (from github3.py>=0.2->gh-cli) (2.8.1)
Collecting jwcrypto>=0.5.0
  Downloading jwcrypto-0.8-py2.py3-none-any.whl (79 kB)
     |████████████████████████████████| 79 kB 5.2 MB/s 
Requirement already satisfied: requests>=2.18 in /usr/lib/python3/dist-packages (from github3.py>=0.2->gh-cli) (2.22.0)
Collecting uritemplate>=3.0.0
  Downloading uritemplate-3.0.1-py2.py3-none-any.whl (15 kB)
Requirement already satisfied: six>=1.5 in /usr/lib/python3/dist-packages (from python-dateutil>=2.6.0->github3.py>=0.2->gh-cli) (1.14.0)
Requirement already satisfied: cryptography>=2.3 in /usr/lib/python3/dist-packages (from jwcrypto>=0.5.0->github3.py>=0.2->gh-cli) (2.8)
Building wheels for collected packages: gh-cli
  Building wheel for gh-cli (setup.py) ... done
  Created wheel for gh-cli: filename=gh_cli-0.1b0-py3-none-any.whl size=29822 sha256=9f9044c471dc67a9d048ac6ea34ce86f87a824bbfdf539791f92f636b35eb98f
  Stored in directory: /home/thierry/.cache/pip/wheels/24/d2/c5/e52bab4b20cbc4d50b17f18f282dadfd4330c3ef8af7631bc5
Successfully built gh-cli
Installing collected packages: jwcrypto, uritemplate, github3.py, gh-cli
  WARNING: The scripts gh and gh-3.8 are installed in '/home/thierry/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed gh-cli-0.1b0 github3.py-2.0.0 jwcrypto-0.8 uritemplate-3.0.1
thierry@TCAILLEAU-02:~$ gh repo create

Command 'gh' not found, but can be installed with:

sudo apt install gitsome

thierry@TCAILLEAU-02:~$ gh

Command 'gh' not found, but can be installed with:

sudo apt install gitsome

thierry@TCAILLEAU-02:~$ sudo apt install gitsome
[sudo] password for thierry: 
Reading package lists... Done


Cloning "CailleauThierry/nbdev_wsl2" using vscode embedded clone from github option instead > that worked!


thierry@TCAILLEAU-02:~/nbdev_wsl2$ git config --list --show-origin
file:.git/config        core.repositoryformatversion=0
file:.git/config        core.filemode=true
file:.git/config        core.bare=false
file:.git/config        core.logallrefupdates=true
file:.git/config        remote.origin.url=https://github.com/CailleauThierry/nbdev_wsl2.git
file:.git/config        remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
file:.git/config        branch.master.remote=origin
file:.git/config        branch.master.merge=refs/heads/master
thierry@TCAILLEAU-02:~/nbdev_wsl2$ git config --global user.name "Thierry Cailleau"
thierry@TCAILLEAU-02:~/nbdev_wsl2$ git config --global user.email tcailleau@yahoo.com
thierry@TCAILLEAU-02:~/nbdev_wsl2$ git config --global core.editor code
thierry@TCAILLEAU-02:~/nbdev_wsl2$ code
code 1.55.2

Usage: code [options][paths...]

To read from stdin, append '-' (e.g. 'ps aux | grep code | code -')

Options
  -d --diff <file> <file>           Compare two files with each other.
  -a --add <folder>                 Add folder(s) to the last active window.
  -g --goto <file:line[:character]> Open a file at the path on the specified line and character position.
  -n --new-window                   Force to open a new window.
  -r --reuse-window                 Force to open a file or folder in an already opened window.
  -w --wait                         Wait for the files to be closed before returning.
  -h --help                         Print usage.

Extensions Management
  --list-extensions                                           List the installed extensions.
  --show-versions                                             Show versions of installed extensions, when using --list-extensions.
  --category                                                  Filters installed extensions by provided category, when using --list-extensions.
  --install-extension <extension-id[@version] | path-to-vsix> Installs or updates the extension. The identifier of an extension is always `${publisher}.${name}`. Use `--force` argument to update to latest version.
                                                              To install a specific version provide `@${version}`. For example: 'vscode.csharp@1.2.3'.
  --uninstall-extension <extension-id>                        Uninstalls an extension.

Troubleshooting
  -v --version Print version.
  -s --status  Print process usage and diagnostics information.

thierry@TCAILLEAU-02:~/nbdev_wsl2$ vscode
vscode: command not found
thierry@TCAILLEAU-02:~/nbdev_wsl2$ code -v
1.55.2
3c4e3df9e89829dce27b7b5c24508306b151f30d
x64
thierry@TCAILLEAU-02:~/nbdev_wsl2$ nbdev_install_git_hooks
Executing: git config --local include.path ../.gitconfig
Success: hooks are installed and repo's .gitconfig is now trusted
thierry@TCAILLEAU-02:~/nbdev_wsl2$ 

```
---------------------------------------------------------------------------
StdinNotImplementedError                  Traceback (most recent call last)
<ipython-input-6-d65081672e04> in <module>
      2     localVariable = input()
      3     print(localVariable)
----> 4 test_input()

<ipython-input-6-d65081672e04> in test_input()
      1 def test_input():
----> 2     localVariable = input()
      3     print(localVariable)
      4 test_input()

/opt/hostedtoolcache/Python/3.6.13/x64/lib/python3.6/site-packages/ipykernel/kernelbase.py in raw_input(self, prompt)
    844         if not self._allow_stdin:
    845             raise StdinNotImplementedError(
--> 846                 "raw_input was called, but this frontend does not support input requests."
    847             )
    848         return self._input_request(str(prompt),

StdinNotImplementedError: raw_input was called, but this frontend does not support input requests.
StdinNotImplementedError: raw_input was called, but this frontend does not support input requests.

Traceback (most recent call last):
  File "/opt/hostedtoolcache/Python/3.6.13/x64/bin/nbdev_test_nbs", line 8, in <module>
    sys.exit(nbdev_test_nbs())
  File "/opt/hostedtoolcache/Python/3.6.13/x64/lib/python3.6/site-packages/fastcore/script.py", line 105, in _f
    tfunc(**merge(args, args_from_prog(func, xtra)))
  File "/opt/hostedtoolcache/Python/3.6.13/x64/lib/python3.6/site-packages/nbdev/test.py", line 120, in nbdev_test_nbs
    raise Exception(msg + '\n'.join([f.name for p,f in zip(passed,files) if not p]))
Exception: The following notebooks failed:
00_core.ipynb
Error: Process completed with exit code 1.
```


      File "<ipython-input-2-e0d3cf7b6ae0>", line 1
        ---------------------------------------------------------------------------
                                                                                   ^
    SyntaxError: invalid syntax


