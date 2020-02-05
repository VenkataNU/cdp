### Tags
Please use the following tags:

Tag Key : enddate  
Tag Value: mmddyyyy (such as 05272019) .

Tag Key: dept .
Tag Value: ps . 

Tag Key: hours_of_operation .   
Tag Value: 24x7 (business_hours, weekend_shutdown, 24x7) . 

Tag Key: enddate_override . 
Tag Value: permanent (or short phrase such as 'demo for customer on dec 6th'..Any value in this tag will cause the enddate filter to exclude this resource from termination. Please get VP dept approval for this exception, it will be included in a routine exception report to each VP dept head.) . 

Tag Key: owner . 
Tag Value: username (okta username such as sdean) . 

Tag Key: project . 
Tag Value: fedex (customer name, project name, or PS project number, etc, or can use 'personal development')
R&D Department's additional 'project' tagging syntax (all lower case and no periods or special characters AND MUST use only the tags shown below under tag value):   

Tag Key: project . 
Tag Value: cdh62 (dwx, mlx, cdsw, cdh6, cdh62, cdh63, cdh, hdp, hdf, cdf, cdp, altus, opssvcs, smartsense, impala, hive, upstream, hbase, cloudbreak, metron) . 

```
enddate : mmddyyyy
dept: ps
hours_of_operation : 24x7 
owner : vudamala
project : training
project : cdp ```
