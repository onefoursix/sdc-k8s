FROM streamsets/datacollector:3.10.1
RUN sudo chgrp -R 0 /etc/sdc /logs /data /resources /opt/streamsets-datacollector-3.10.1  && sudo chmod -R g=u /etc/sdc /logs /data /resources /opt/streamsets-datacollector-3.10.1 
RUN sudo sed -i 's/http.realm.file.permission.check=true/http.realm.file.permission.check=false/' /etc/sdc/sdc.properties
