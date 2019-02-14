FROM centos:7
LABEL maintainers="ZC"
LABEL description="XSKY ISCSI CSI Plugin"

COPY xsky-iscsiplugin /xsky-iscsiplugin
COPY csi /etc/logrotate.d/csi
RUN chmod +x /xsky-iscsiplugin
ENTRYPOINT ["/xsky-iscsiplugin"]
