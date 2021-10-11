# Flussonic Import and export m3u playlist

# This script will work on Debian, Ubuntu, CentOS and probably other distros
# of the same families, although no support is offered for them. 

# This is a shell script under GNU GPL version 3.0 or above
# Copyright (C) 2017 LinuxHelps project.
# Feedback/comment/suggestions : https://slaserx.dev/
# Author Ivan Bachvarov a.k.a SlaSerX


flussonic_to_m3u.sh 
Usage: ./flussonic_to_m3u.sh FLUSSONIC_IP:PORT USER:PASS [PROTOCOL]
Supported protocols: hls, dash, video, mono, mpegts

Examples:
./flussonic_to_m3u.sh 127.0.0.1 flussonic:letmein!
./flussonic_to_m3u.sh 127.0.0.1:8080 flussonic:letmein! mpegts
./flussonic_to_m3u.sh flussonic.myhost.com admin:mypassword hls
./flussonic_to_m3u.sh flussonic.myhost.com admin:mypassword dash



m3u_to_flussonic.py 
Usage: ./m3u_to_flussonic.py /path/to/playlist.m3u
or: ./m3u_to_flussonic.py http://11.22.33.44/path/to/playlist.m3u

Download: https://slaserx.dev/shop/index.php?rp=/store/software
