---

copyright:
  years: 2018, 2019
lastupdated: "2018-04-02"

keywords: provision, sgx, provision server Intel SGX architecture, Intel SGX architecture

subcollection: bare-metal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# Provisioning a bare metal server with Intel Software Guard Extension architecture
{: #bm-server-provision-sgx}

1. Use the procedure: [Building a custom bare metal server](/docs/bare-metal?topic=bare-metal-ordering-baremetal-server).
* Select the following options on the order form:

|Section|Option to select|
|------|------|
|Server|Single processor,<br> Intel Xeon E3-1270 v6 with Storage up to four drives|
|Image|Windows Server 2016 Standard Edition (64 bit)<br>Windows Server 2016 Standard Edition (64 bit)<br> Windows Server 2016 Datacenter Edition (64 bit) <br>CentOS 7.x (64 bit) <br>Ubuntu Linux 16.04 LTS Xenial Xerus (64 bit)<br>- CentOS 7.x (64 bit) <br>Red Hat Enterprise Linux 7.x (64 bit) (per-processor licensing)|
|Image Add-ons|Software Guard Extensions|
