centos-kdb
==========

32bit [KDB](http://kx.com/kdb-plus.php), installed inside centos.

Credit for all the hard work goes to [Jasraj](https://github.com/jasraj), for building an [RPM installer](https://github.com/jasraj/q-build).

###Running the image

`sudo docker run -i -t richardgill/centos-kdb bash -l`

`-l` is required in order to put q on the path.
