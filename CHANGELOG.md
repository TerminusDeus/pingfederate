
# 0.3.1
- removed java from cookbook. a little too cumbersome to use the cookbooks to you just need to ensure it is installed and update the attribute, `['pingfed']['java_home']`

# 0.3.0
- move install into a resource
- added `console_instance.rb` and `engine_instance.rb` to allow for clustering
- added new exceptions to `port_open?`

# 0.2.0
- upgrade pingfed 9.2.2
- change long wait to wait that port is open
- fixed restart issue with systemd

# 0.1.3
- Added sleep 2 minutes at first install for API calls to respond
- Added recipe oauth_settings to create configurations via API calls

# 0.1.2
- Added systemd support