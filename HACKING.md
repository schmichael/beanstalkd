beanstalkd is comprised of a number of C sources files and a Makefile to
compile them. A make implementation and C compiler are the only prerequisites.

Server implementation:

* conn.c - Conn handling code
* dat.h - Defines data types and functions
* file.c
* heap.c
* job.c
* main.c
* net.c
* primes.c
* prot.c
* serv.c
* time.c
* tube.c
* util.c
* walg.c

OS specific code:

* darwin.c
* freebsd.c
* linux.c
* ms.c

Test files:

* heap-test.c
* integ-test.c
* job-test.c
* util-test.c

Misc.:

* sd-daemon.c - systemd specific code
* vers.c - Version declaration updated by Makefile/vers.sh
