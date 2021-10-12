Flussonic Import and export m3u playlist</br>

This script will work on Debian, Ubuntu, CentOS and probably other distros
of the same families, although no support is offered for them. </br>

This is a shell script under GNU GPL version 3.0 or above
Copyright (C) 2017 LinuxHelps project.</br>
Feedback/comment/suggestions : https://slaserx.dev/</br>
Author Ivan Bachvarov a.k.a SlaSerX</br>


flussonic_to_m3u.sh </br>
Usage: ./flussonic_to_m3u.sh FLUSSONIC_IP:PORT USER:PASS [PROTOCOL]</br>
Supported protocols: hls, dash, video, mono, mpegts</br>

Examples:</br>
./flussonic_to_m3u.sh 127.0.0.1 flussonic:letmein!</br>
./flussonic_to_m3u.sh 127.0.0.1:8080 flussonic:letmein! mpegts</br>
./flussonic_to_m3u.sh flussonic.myhost.com admin:mypassword hls</br>
./flussonic_to_m3u.sh flussonic.myhost.com admin:mypassword dash</br>



m3u_to_flussonic.py </br>
Usage: ./m3u_to_flussonic.py /path/to/playlist.m3u</br>
or: ./m3u_to_flussonic.py http://11.22.33.44/path/to/playlist.m3u</br>

Download: https://slaserx.dev/shop/index.php?rp=/store/software</br>
