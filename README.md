## Start with command:

docker run -d --name mattermost --restart always \
  -v <mattermost-config-folder-with-config.json-in-it>:/mattermost/config \
  -v <mattermost-data-folder>:/mattermost/data \
  -v <mattermost-logs-folder>:/mattermost/logs \
  lynxsolutions/docker-mattermost:latest
