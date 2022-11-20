FROM debian:11
RUN apt-get update && apt-get -y install \
	perl perl-cross-debian apache2 libapache2-mod-perl2 libdbd-mysql-perl \
	libapache2-mod-perl2 libapache2-reload-perl libapache-admin-config-perl libapache-htpasswd-perl \
	libapache-logformat-compiler-perl libapache-session-browseable-perl libapache-session-perl libapache-session-wrapper-perl libapache-sessionx-perl \
	samba
	# smbclient cifs-utils
	# gcc build-essential autoconf automake libtool gdb \

CMD ["/usr/sbin/apache2"]
