# jtapi-legacy-openshift
OpenShift Twitter API based on Java, a fork from mariotaku:jtapi-legacy

How to deploy
=====

###OpenShift

1. Create an application on OpenShift, Choose **Tomcat 7**
2. Fork this repo
3. Change ````OVERRIDE_APP_HOST```` to your domain (like ````jtapi.rhcloud.com````) in ````jtapi-legacy-openshift/src/main/webapp/WEB-INF/jtapi.properties````, commit and push.
3. Paste URL into **Source Code** in OpenShift configuration page
4. Click **Create Application**
5. Done!
