[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3f8e27ab77d341e8a87ec3f9a4cb7f0c)](https://www.codacy.com/app/shiyanf/node-ibmapm?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=IBM-APM/node-ibmapm&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.org/IBM-APM/node-ibmapm.svg?branch=master)](https://travis-ci.org/IBM-APM/node-ibmapm)
[![codebeat badge](https://codebeat.co/badges/f7a857b8-a6c0-49e9-994d-1c1cc10a37f9)](https://codebeat.co/projects/github-com-ibm-apm-node-ibmapm-master)
[![codecov](https://codecov.io/gh/IBM-APM/node-ibmapm/branch/master/graph/badge.svg)](https://codecov.io/gh/IBM-APM/node-ibmapm)
Table of Contents
=================
- [Table of Contents](#table-of-contents)
    - [Overview](#overview)
    - [Downloading the latest ibmapm package](#downloading-the-latest-ibmapm-package)    
    - [Configuring Node.js application monitoring using the Cloud APM v8 server](#configuring-nodejs-application-monitoring-using-the-cloud-apm-v8-server)

## Overview
The Node.js data collector can provide you with visibility and control of your Node.js applications, and help you ensure optimal performance and efficient use of resources. You can reduce and prevent application crashes and slowdowns around the clock, as the data collector assists you in detecting, diagnosing and isolating performance issues.

The Node.js data collector helps you to manage the performance and availability of the following:

- Node.js applications in IBM Cloud Private
- Node.js applications in IBM Cloud (aka Bluemix)
- Local Node.js applications

This data collector can be configured to connect to the IBM Cloud Application Performance Management (Cloud APM v8) server.

## Downloading the latest ibmapm package
To get the up-to-date ibmapm package, which is a required dependency that you need for Node.js application monitoring, go to https://rtpgsa.ibm.com/projects/i/itm_db2_agent/nodejs/cloudnative/NPMCD/latest/.

This package is for internal testing.



## Configuring Node.js application monitoring using the Cloud APM v8 server
You can use the Node.js data collector, which is delivered in the Cloud APM v8 product, to monitor your Liberty applications running locally, in IBM Cloud, or in IBM Cloud Private. The data collector is configured to connect to the Cloud APM v8 server.

Different procedures apply depending on whether you are using Cloud APM (SaaS) or Cloud APM, Private (on-premises).

- If you are a Cloud APM (SaaS) user, complete the following procedures:
> - [Configuring the data collector for IBM Cloud applications](https://www.ibm.com/support/knowledgecenter/SSMKFH/com.ibm.apmaas.doc/install/bluemix_nodejs_config_dc.htm)
> - [Configuring the data collector for local applications](readme-topics/local-nodejs-apm-saas.md)
> - [Configuring method trace and transaction tracking](readme-topics/nodejsdc_mt_tt.md)

- If you are a Cloud APM, Private (on-premises) user, complete the following procedures:
> - [Configuring the data collector for Bluemix applications](https://www.ibm.com/support/knowledgecenter/SSHLNR_8.1.4/com.ibm.pm.doc/install/bluemix_nodejs_config_dc.htm)
> - [Configuring the data collector for local applications](readme-topics/local-nodejs-apm-onprem.md)
> - [Configuring the data collector for applications in IBM Cloud Private](readme-topics/nodejsdc_icp_apm_server.md)
> - [Configuring method trace and transaction tracking](readme-topics/nodejsdc_mt_tt.md)

You can also use the supported variables to change the default behavior of data collection. For more information, see [Advanced configuration](readme-topics/nodejs_dc_advanced_config.md).

