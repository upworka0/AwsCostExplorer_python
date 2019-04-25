AWS Cost Explorer report Python
===============================

The purpose of this project is to get cost usage data from AWS costexplorer api using python.


How to run:
------------

Configure AWS credentials, SES_REGION, SES_FROM:
    
    aws configure 
    

Run following commands:

    $ python cost_report_script.py --months <month> --SES_SEND <to_email>
    
    Example 
    $ python cost_report_script.py --months 6 --SES_SEND test@mail.com 
    