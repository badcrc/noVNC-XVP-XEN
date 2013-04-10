## noVNC: HTML5 VNC Client


### About this fork

This is just a quick hack for being able to connect to a <a href="http://www.xvpsource.org/">xvp</a> proxy running in multiplexing mode. It tries to emulate what the Java xvpviewer does.

Like with the xvpviewer you need a new param for connecting which is the pool and the vm-id (or the named, depends on you xvp deployment): "PoolName:11223344-5566-7788-99aa-bbccddeeffgg" and pass it to the connect function of the public api of noVNC, the changes are in the rfb.js files.


