# CucumberBDD_June2021
CucumberBDD Framework_June2021
#Fix code in mac
cmd+a to select all code option+cmd+L
#Fix code in Windows
CMD+A CTL+I
#How to execute test in CMD
/Users/jannatulnayeem/
cd Documents/QA_Automation/GitProject/CucumberBDD_June2021/
mvn verify -Denv=qa -Dbrowser=ff -Dcucumber.filter.tags="@login"
mvn verify -Denv=qa -Dbrowser=ch -Dcucumber.filter.tags="@signup"