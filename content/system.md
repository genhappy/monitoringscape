---
title: System Monitoring
slug: system-monitoring
weight: 3
type: section
---

For most operations teams, system monitoring tools constitute the **central hub of visibility** into the status of their production environments. Use these tools to detect and investigate **hardware**, **network** and **software** problems. This is a broad definition that captures many flavors of tools, and thorough research is required before adopting a tool for production use.

System monitoring tools frequently employ a **plugin architecture**, making it easy to monitor the health of various types of infrastructure. Note that often **breadth comes at the expense of depth**: as your company grows, you will likely choose to adopt additional tools from other categories to augment your system monitoring solution.

## Common Features

* Status dashboard (i.e. "red/yellow/green" infrastructure overview )
* Alerting via email, sms, etc.
* Agents for periodical execution of health checks
* Built-in collectors for servers & networks
* Plugin architecture that supports many types of infrastructure
* Check hierarchy / dependency mapping

## Tool Overview
{{% tools %}}
  {{% tool system Boundary        boundary "http://www.boundary.com"        ""          2011                "SaaS" %}}
  {{% tool system Centreon   centreon "https://www.centreon.com"         ""          2003                "On Prem" %}}
  {{% tool system collectd    collectd    "https://collectd.org/"       "Open Source, Collection only" 2005     "On Prem" no-screenshot %}}
  {{% tool system CopperEgg   copperegg "http://copperegg.com/"         ""          2010                "SaaS" %}}
  {{% tool system Datadog     datadog "https://www.datadoghq.com/"      ""          2010                "SaaS" %}}
  {{% tool system "Dataloop.io" dataloop "https://www.dataloop.io/"      ""          2014                "SaaS" %}}
  {{% tool system Ganglia     ganglia "http://ganglia.info/"            "Open Source"    2001     "On Prem" %}}
   {{% tool system Happy Apps "https://www.happyapps.io/"      ""          2015                "SaaS" %}}
  {{% tool system Icinga      icinga "https://www.icinga.org/"          "Open Source, Forked from Nagios" 2009       "On Prem" %}}
  {{% tool system LogicMonitor   logicmonitor "http://www.logicmonitor.com/" ""          2009     "SaaS" %}}
  {{% tool system Munin     munin "http://munin-monitoring.org/"           "Open Source"    2006     "On Prem" %}}
  {{% tool system Nagios    nagios "https://www.nagios.org/"  "Open Source"     1999      "On Prem" %}}
  {{% tool system OpenNMS   opennms "http://www.opennms.org/"  "Open Source"    2000     "On Prem" %}}
  {{% tool system OpsView   opsview "http://www.opsview.com/"  "Open Source, Forked from Nagios"    2003    "On Prem" %}}
  {{% tool system PRTG      prtg "https://www.paessler.com/prtg"  ""    1997    "On Prem" %}}
  {{% tool system Scout     scout "https://scoutapp.com/"  ""    2008    "SaaS" %}}
  {{% tool system Sensu     sensu "https://sensuapp.org/"  "Open Source"    2011    "On Prem" %}}
  {{% tool system ServerDensity   serverdensity "https://www.serverdensity.com/"  "Server monitoring only"    2013    "SaaS" %}}
  {{% tool system statsd   statsd "https://github.com/etsy/statsd"  "Open Source, Collection Only"         2012    "On Prem" no-screenshot %}}
  {{% tool system Zabbix   zabbix "http://www.zabbix.com/"  "Open Source"    1998    "On Prem" %}}
  {{% tool system Zenoss   zenoss "http://www.zenoss.com/"  "Open Source"    2002    "On Prem" %}}
{{% /tools %}}
