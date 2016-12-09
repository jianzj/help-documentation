---
layout: page
title: Customer 3.1.1 Point Release Notes
author: Leslie Lundquist
featured: true
dateAdded: December 16, 2016
tags: [release notes, 3.1.1]

---

### IBM Bluemix Private Cloud Customer

### Point Release 3.1.1

**December 16, 2016**


This 3.1.1 Point Release is created primarily to fix some bugs that were affecting a few of our customers. Here are the changes that may affect your customer experience:

 * Urban Code Deploy [UCD] Heat plug-in was made current for 3.1.1
 
 * Customer-facing RBAC documentation has been [updated](http://ibm-blue-box-help.github.io/help-documentation/keystone/Managing_Users_and_Projects/)
 
 * Curated image for CentOS 6.8: only 2.1G disk space was seen in VM while the flavor had 10G disk. Now corrected.
 
 * Windows images previously assumed that the hardware clock was set to the customer's local timezone instead of UTC. The defect is corrected, no workaround is needed for new VMs provisioned from the updated images. To fix older VMs, set the 'RealTimeIsUniversal' registry entry as documented here: http://ibm-blue-box-help.github.io/help-documentation/troubleshooting/FAQ_Working_with_Windows_Images/

 * Created a new document to assist with using Nova Metadata service [http://ibm-blue-box-help.github.io/help-documentation/nova/Metadata_service_FAQ/]9 http://ibm-blue-box-help.github.io/help-documentation/nova/Metadata_service_FAQ/)