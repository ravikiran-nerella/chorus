FROM querqy/smui:3.6.1

# This is a temporary shim to allow us to write to /usr/bin/solr/preliveCore/conf
# since the user running SMUI is smui.
USER root
RUN chmod -R 0777 /usr
