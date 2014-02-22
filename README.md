DFO_data
========

Data Source:

This dataset was assembled from multiple pulls of data from DFO's online registry of licences and vessels.
http://www-ops2.pac.dfo-mpo.gc.ca/vrnd-rneb/index-eng.cfm?pg=LicReportSelect



Column headers:

Date - month and year of data download from DFO listings (precise 2012 date is unknown, 2013 was done Dec 6)
Licence - full licence identifier code
LicType - licence letter code (see note below)
LicNum - licence serial number
LicYear - licence year - corresponds to year of fishing season when record is updated
Area - fishing area licence is permitted to fish
Option - further details on fishing restrictions (optional)
Quota - maximum harvest, if relevant (optional)
MVL - maximum vessel length, in meters (optional, only available for vessel-based licences)
Status - status of licence renewal
Name - full name of licence owner
LastName - last name of licence owner, generally a redundant/useless column
Vessel - vessel name (optional, only available for vessel-based licences)
VRN - vessel registration number (optional, only available for vessel-based licences)
OAL - overall vessel length, in meters - actual length of vessel fishing this licence, should be < MVL (optional)

Licence letter codes: http://www.pac.dfo-mpo.gc.ca/fm-gp/licence-permis/lpc-eng.html
