FROM debian:11
RUN apt-get update && apt-get -y install cron perl perl-cross-debian libdbd-mysql-perl
CMD ["/usr/sbin/cron"]
