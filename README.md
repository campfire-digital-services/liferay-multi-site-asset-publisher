# Liferay Multisite Asset Publisher

*liferay-multi-site-asset-publisher*

This project provides a Liferay Portal plugin to source the content for the asset publisher from all the available sites and the organizations.


## Supported Products

* Liferay Portal 6.1 CE GA2 (6.1.1+)
* Liferay Portal 6.1 EE GA2 (6.1.20+)


## Downloads

The latest release is available from [SourceForge - Liferay Multi Site Asset Publisher](https://sourceforge.net/projects/permeance-apps/files/liferay-multi-site-asset-publisher/releases) "SourceForge - Liferay Multi Site Asset Publisher").


## Usage

## Building

Step 1. Checkout source from GitHub project

    % git clone https://github.com/permeance/liferay-multi-site-asset-publisher

Step 2. Build and package

    % mvn -U clean package

This will build "liferay-multi-site-asset-publisher-hook-A.B.C.war" in the targets folder.

NOTE: You will require JDK 1.6+ and Maven 3.


## Installation

### Liferay Portal + Apache Tomcat Bundle

* Deploy "liferay-multi-site-asset-publisher-hook-A.B.C.war" to "LIFERAY_HOME/deploy" folder.


## Project Team

* Rajaraman Kannan- kannan.raman@permeance.com.au
