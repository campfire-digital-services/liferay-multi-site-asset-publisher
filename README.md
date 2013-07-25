# Liferay Multisite Asset Publisher

*liferay-multi-site-asset-publisher*

This project provides a Liferay Portal plugin to source the content for the asset publisher from all the available sites and the organizations.


## Supported Products

* Liferay Portal 6.1 CE GA2 (6.1.1+)
* Liferay Portal 6.1 EE GA2 (6.1.20+)


## Downloads

The latest release is available from [SourceForge - Liferay Multi Site Asset Publisher](https://sourceforge.net/projects/permeance-apps/files/liferay-multi-site-asset-publisher/releases) "SourceForge - Liferay Multi Site Asset Publisher").


## Usage

### Configuring Asset Publisher without this plugin
* Add the Asset Publisher Portlet.
* Click Configuration on the right top of the asset publisher portlet.
* Under Scope tab, we could see only Liferay and Global sites are available
![Asset Publisher Configuration without this plugin](/docs/images/liferay-multi-site-asset-publisher-without-hook.png "Asset Publisher Configuration without Plugin")

### Configuring Asset Publisher with this Plugin
* Add the Asset Publisher Portlet.
* Click Configuration on the right top of the asset publisher portlet.
* Under Scope tab, we could see all the available sites and organizations.
![Asset Publisher Configuration with this plugin](/docs/images/liferay-multi-site-asset-publisher-with-hook.png "Asset Publisher Configuration with Plugin")

** All Available Sites


![Asset Publisher Configuration - all available sites](/docs/images/liferay-multi-site-asset-publisher-sites-available.png "Asset Publisher Configuration - all available sites")


** All Available Organizations

![Asset Publisher Configuration - all available organizations](/docs/images/liferay-multi-site-asset-publisher-org.png "Asset Publisher Configuration - all available organizations")


## Building

Step 1. Checkout source from GitHub project

    % git clone https://github.com/permeance/liferay-multi-site-asset-publisher

Step 2. Build and package

    % mvn -U clean package

This will build "liferay-multi-site-asset-publisher-hook-A.B.C.war" in the targets folder.

NOTE: You will require JDK 1.6+ and Maven 3.


## Plugin Security

This plugin comes with the PACL Security Manager disabled. 
However the list of PACL requirements to run this plugin in secure mode is available (commented out) in WEB-INF/liferay-plugin-package.properties. You can uncomment those entries to run the plugin in PACL secure mode.


## Installation

### Liferay Portal + Apache Tomcat Bundle

* Deploy "liferay-multi-site-asset-publisher-hook-A.B.C.war" to "LIFERAY_HOME/deploy" folder.


## Project Team

* Rajaraman Kannan- kannan.raman@permeance.com.au
