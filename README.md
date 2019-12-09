[![GitHub license](https://img.shields.io/github/license/kate-orlova/azure-logs-tricks.svg)](https://github.com/kate-orlova/azure-logs-tricks/blob/master/LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/kate-orlova/azure-logs-tricks.svg?style=flat)

# Azure Logs Tricks

Azure Logs tricks are a set of useful scripts written in Kusto Query Language (KQL) to query the Azure log databases. Scripts are grouped into folders based on the specific functionality and table name in Azure Logs:
* **requests**
   * calculate the total number of different / long or specific requests count and with average duration within a custom time range or for the last 24 hours by default and present results in table / chart view;
   * get the top 10 failed requests;
   * get the amount of requests from the top 10 countries;
   * get the request count trend within a custom time range;
   * get the response time trend within a custom time range;
   * get the failed requests and calculate a number of impacted users within a custom time range;
* **pageViews**
   * get top 10 slowest pages within a custom time range in table / chart view;
   * get the page views trend within a custom time range;
* **exceptions**
    * get the exceptions causing failures within a custom time range;
* **dependencies**
    * get the top 10 failing dependencies within a custom time range;
* **performanceCounters**
    * get the max number of requests a second within the last 24 hours to apps;

# Contribution
Hope you found these KQL scripts helpful, your contributions and suggestions will be very much appreciated. Please submit a pull request.

# License
Azure Logs tricks are released under the MIT license what means that you can modify and use it how you want even for commercial use. Please give this repository a star if you like any of KQL tricks and your experience was positive.
