Hari Sekhon's Ambari Blueprint Samples
======================================

### PyTools ```ambari_blueprints.py``` templates ###

Generated by the ```ambari_blueprints.py``` tool found in the top level of this repo from various generic test clusters.

Beware the default password is set to ```test``` - must modify ```hostmappings*.json``` to set a real password.

Also note that the high degree of variation in cluster topologies when combined with the large number of components especially in multi-HA deployments makes this less portable than you would expect and should not be taken as-is for production - you should hire an experienced Hadoop expert.

Ambari Blueprints are very raw and there are lots of things that can go wrong with them even if they submit correctly to Ambari they can fail half way through cluster deployment. There are thousands of lines of optional json configuration settings that may need to be added/tweaked, which have been omitted here to try to keep things as a generic base.

Some features will not work in different versions of Ambari < 2.1.0 (HA, host predicates/counts) or require extra configuration eg. for various services HA deployments. You must read all the Ambari documentation thoroughly.

##### I am not supporting these Blueprints, please do not raise issues for this part of the repo. #####

This is only for my own usage and reference for modification to my clients needs while consulting.