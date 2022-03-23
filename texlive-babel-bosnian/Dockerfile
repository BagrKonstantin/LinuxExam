FROM rosalab/rosa2021.1
RUN dnf install -y dnf-utils
RUN yum-config-manager --add-repo \
http://abf-downloads.rosalinux.ru/bagrkonstantin_personal/repository/rosa2021.1/x86_64/main/release/
RUN dnf install --nogpgcheck -y texlive-babel-bosnian
ENTRYPOINT rpm -q texlive-babel-bosnian