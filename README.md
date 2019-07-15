# pkg_linker_cmd

How to use GNU/Linux-Libre:
  - install **mono**
  
compile
~~~bash 
pkg_linker_cmd/pkg_linker_cmd$ xbuild pkg_liker_cmd.sln
~~~

**cd pkg_linker_cmd/bin/Debug** fix permission exectuable in **bin/* to:
  - pkg.py
  - ps3xploit_rifgen_edatresign

then:
  - rebuild pkgcrypt.so from 'PS3xploit-resigner' if not works.
  - copy idps.hex and act.dat to **bin/** same level as **pkg.py** 
  - copy o link .pkg to **bin/Debug**
  - run **mono pkg_linker_cmd.exe**
  - if all works ok you must have **Package_List.pkg**

start a server in port 9080:
  - **python3 -m http.server 9080**
