========================================================================

Manifest for repo tools

February 2018
========================================================================


Contents
========

Contains default.xml manifest for repo tools, for fetch all cloudwpa sources

Requirements
========
You need to install git and repo tool first.
More info regarding repo tool can be found https://source.android.com/setup/develop/repo



Overview
========

For fetching project automatically , please use repo tool.

repo init -u https://github.com/intel/cloudwpa-manifest
repo sync


After running repo tool the following repo's will be fetched.

https://github.com/intel/cloudwpa-hostapd
https://github.com/intel/cloudwpa-pf_init
https://github.com/intel/cloudwpa-rwpa_dp
https://github.com/intel/cloudwpa-scripts
https://github.com/intel/cloudwpa-sim
https://github.com/intel/cloudwpa-ap

Note:
================
You can download all repos manually by rinning git :
git clone https://github.com/intel/cloudwpa-hostapd  cloudwpa/hostapd
git clone https://github.com/intel/cloudwpa-pf_init  cloudwpa/pf_init
git clone https://github.com/intel/cloudwpa-rwpa_dp cloudwpa/rwpa_dp
git clone https://github.com/intel/cloudwpa-scripts cloudwpa/scripts
git clone https://github.com/intel/cloudwpa-sim cloudwpa/sim
git clone https://github.com/intel/cloudwpa-ap cloudwpa/ap


Legal Disclaimer
================

THIS SOFTWARE IS PROVIDED BY INTEL"AS IS". NO LICENSE, EXPRESS OR
IMPLIED, BY ESTOPPEL OR OTHERWISE, TO ANY INTELLECTUAL PROPERTY RIGHTS
ARE GRANTED THROUGH USE. EXCEPT AS PROVIDED IN INTEL'S TERMS AND
CONDITIONS OF SALE, INTEL ASSUMES NO LIABILITY WHATSOEVER AND INTEL
DISCLAIMS ANY EXPRESS OR IMPLIED WARRANTY, RELATING TO SALE AND/OR
USE OF INTEL PRODUCTS INCLUDING LIABILITY OR WARRANTIES RELATING TO
FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR INFRINGEMENT
OF ANY PATENT, COPYRIGHT OR OTHER INTELLECTUAL PROPERTY RIGHT.

