# Release notes for Workflow **Sync_PVI_to_Policy_Mappings**
### written by:   Markus Nikulski
### e-mail:       mnikulski@extremenetworks.com
### date:         11. February 2025

| Build | Description |
| ------------- | ------- |
|24.10.13.5v344|*new features*<br>	• <br><br>*maintenance*<br>	• add worflow messages to provide more details about the status and result<br><br>*fixed issues*<br>	• LOG formating issue in 'update_Policy_Mappings'|
|24.10.13.5v342|*new features*<br>	• add non VLAN/I-SID support, no VLAN Islands required anymore<br>	• remove Debug LOG form user input dialog, keep it true by default<br><br>*maintenance*<br>	• optimise common rutines using copression, fix issue with version tracking<br>	• cleanup debug messages across the workflow<br>	• dump emc_vars to debug folder<br>	• update documentation<br><br>*fixed issues*<br>	• compare existing policy mappings with indetned config faild if policy mapping are empty|
|24.10.13.5v319|*new features*<br>	• support now multible NAC engine groups<br>	• enable/disable enforec AC<br><br>*maintenance*<br>	• expand Debug LOG messages<br><br>*fixed issues*<br>	• none|
|24.10.11.15v311|*new features*<br>	• add multicast support<br>	• enable/disable enforec NAC<br><br>*maintenance*<br>	• expand Debug LOG messages<br>	• update documentation<br><br>*fixed issues*<br>	• default NAC Radius Config Attribute support multiple records comma-separated<br>	• enforcement fails under some circumstances<br>	• empty VLAN Policy location causes issues<br>	• private VLAN support<br>	• multiple VLAN, I-SID bindis (REGEX issue in update Policy Mappings)<br>	• I-SID name not working|
|