1
# debian.sh --arch 'arm64' out/
26.78 MB
2
ENV HTTPD_PREFIX=/usr/local/apache2
0 B
3
ENV PATH=/usr/local/apache2/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
0 B
4
RUN /bin/sh -c mkdir -p
146 B
5
WORKDIR /usr/local/apache2
32 B
6
RUN /bin/sh -c set -eux;
3.84 MB
7
ENV HTTPD_VERSION=2.4.64
0 B
8
ENV HTTPD_SHA256=120b35a2ebf264f277e20f9a94f870f2063342fbff0861404660d7dd0ab1ac29
0 B
9
ENV HTTPD_PATCHES=
0 B
10
RUN /bin/sh -c set -eux;
24.85 MB
11
STOPSIGNAL SIGWINCH
0 B
12
COPY httpd-foreground /usr/local/bin/ # buildkit
291 B
13
EXPOSE map[80/tcp:{}]
0 B
14
CMD ["httpd-foreground"]
0 B
15
WORKDIR /usr/local/apache2/htdocs
32 B
16
COPY index.html . # buildkit
311 B
17
COPY about.html . # buildkit
313 B
