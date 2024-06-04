Son 8.5 GB y esta generando estos errores,

cjpel@asus-rog-nse MINGW64 /d/GitHub/202401_RealidadMixta_ProyectoFinal (main)
$ git push origin
Enumerating objects: 51681, done.152), 16 MB | 0 B/s
Counting objects: 100% (51679/51679), done.
Delta compression using up to 20 threads
Compressing objects: 100% (24698/24698), done.
fatal: protocol error: bad line length 16384B | 75.41 MiB/s
send-pack: unexpected disconnect while reading sideband packet
error: failed to push some refs to 'https://github.com/cpelaezp/202401_RealidadMixta_ProyectoFinal.git'

cjpel@asus-rog-nse MINGW64 /d/GitHub/202401_RealidadMixta_ProyectoFinal (main)
$ git config --global http.postBuffer 52428800

cjpel@asus-rog-nse MINGW64 /d/GitHub/202401_RealidadMixta_ProyectoFinal (main)
$ git push origin
Uploading LFS objects: 100% (152/152), 16 MB | 0 B/s, done.
Enumerating objects: 51681, done.
Counting objects: 100% (51679/51679), done.
Delta compression using up to 20 threads
Compressing objects: 100% (24698/24698), done.
error: RPC failed; HTTP 500 curl 22 The requested URL returned error: 500
send-pack: unexpected disconnect while reading sideband packet
Writing objects: 100% (51675/51675), 8.73 GiB | 12.23 MiB/s, done.
Total 51675 (delta 26592), reused 51669 (delta 26588), pack-reused 0
fatal: the remote end hung up unexpectedly
Everything up-to-date
