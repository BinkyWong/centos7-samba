# centos7-samba

This will enable a quick samba share for windows users to use.

To build:

  git clone https://github.com/BinkyWong/centos7-samba.git

  cd centos7-samba

  docker build -t centos7-samba .

To run:

  docker run -d -p 445:445 -p 137:137 -p 138:138 -p 139:139 -v /srv:/srv centos7-samba


