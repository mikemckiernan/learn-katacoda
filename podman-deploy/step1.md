View the container images available.

`podman images`{{execute}}

<pre class=file>
REPOSITORY              TAG      IMAGE ID       CREATED        SIZE
localhost/rhel8-httpd   latest   c12e3720df7b   43 hours ago   499 MB

</pre>

There is one container available in the local (localhost) repository, 
*rhel8-httpd*.  If there were multiple updated iterations of the conatiner 
available, you would use the *IMAGE ID* to work with those that are not 
tagged as *latest*.  Also, from this list you are able to see the size, on 
disk, of the container image. 