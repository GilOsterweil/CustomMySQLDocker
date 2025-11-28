FROM dbeaver/cloudbeaver:latest
RUN mkdir -p /opt/cloudbeaver/workspace
COPY datasources.json /opt/cloudbeaver/workspace/datasources.json
RUN chown -R dbeaver:dbeaver /opt/cloudbeaver/workspace
