# Frigate verify RTSP feed from camera

Video LAN Client supports RTSP feeds.  Just past the url...

rtsp://{USER}:{PASSWORD}@192.168.4.55:554/Streaming/Channels/101

# Timezone
This needs to be set up properly on each camera. Just log into the camera using a web browser and the
RTSP username, password.

# Docker Compose

frigate,mqtt & home assistent - all share the same bridged network.
The docker service name *is* the hostname to refer to. Don't use localhost...

HACS - https://hacs.xyz/docs/configuration/basic

Blueprint - https://www.home-assistant.io/docs/automation/using_blueprints/

          - https://docs.frigate.video/guides/ha_notifications/
