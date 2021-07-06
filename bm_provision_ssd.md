---

copyright:
  years: 2017, 2021
lastupdated: "2021-07-06"

keywords: provision Intel Optane compatible bare metal server, Intel Optane, optane

subcollection: bare-metal

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .note}

# Provisioning an Intel Optane-compatible bare metal server
{: #bm-provision-optane-server}

To provision a bare metal server with an Intel&reg; Optane drive, follow these steps:
1. Use the procedure: [Building a custom bare metal server](/docs/bare-metal?topic=bare-metal-ordering-baremetal-server).
* Select the following options on the order form:

| Section | Option to select |
|------|------|
|Region-Data Center|To use the Intel&reg; Optane drive, select one of the following data centers:<br>Europe - AMS03, FRA02, LON02, OSL01<br>NA South DAL09, DAL10, DAL12<br>Asia-Pacific - MEL01<br>NA East - MON01, TOR01, WDC04<br>NA West - SJC03<br>|
|Server|1. Select **All servers**<br>2. Select *Dual processors*<br>3. Select one of the following servers<br>Intel&reg; Xeon 4110, up to 12 drives<br>Intel&reg; Xeon 5120  with up to 12 drives<br>Intel&reg; Xeon 6140  with up to 12 drives|
|Operating system|For Intel&reg;-provided Optane drivers the following operating systems are certified by Intel&reg;:<br>Windows Server 2016 (all Editions)<br>Windows Server 2012 R2 (all Editions)<br><br>For In-box, open source, non-Intel&reg; drivers, compatibility, and functionality is validated but not certified:<br>Red Hat Enterprise Linux&reg; 7.x (64 bit)<br>Red Hat Enterprise Linux&reg; 6.x (64 bit).
|Image Add-ons| Select an Intel&reg; Optane drive for either or both the first and second PCIe Components.|

<caption>Table 1. Provisioning an Intel&reg; Optane-compatible bare metal server</caption>

