FROM jenkins/jenkins:lts

# Install required Jenkins plugins
RUN /usr/local/bin/install-plugins.sh ssh-slaves \
    && /usr/local/bin/install-plugins.sh matrix-auth \
    && /usr/local/bin/install-plugins.sh prometheus \
    && /usr/local/bin/install-plugins.sh authorize-project \
    && /usr/local/bin/install-plugins.sh credentials-binding \
    && /usr/local/bin/install-plugins.sh docker-workflow \
    && /usr/local/bin/install-plugins.sh kubernetes \
    && /usr/local/bin/install-plugins.sh sonar \
    && /usr/local/bin/install-plugins.sh hashicorp-vault-plugin \
    && /usr/local/bin/install-plugins.sh blueocean
