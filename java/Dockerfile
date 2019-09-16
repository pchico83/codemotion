FROM amd64/busybox:1.30.0-glibc as busybox
FROM pchico83/jib

COPY --from=busybox /bin/busybox /busybox/busybox
RUN ["/busybox/busybox", "--install", "/bin"]
