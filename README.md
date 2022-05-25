# Nova-Activity-Indicator
The Nova Activity Indicator is a nodeJs script that monitors the Openstack nova project over a period of time and identifies the 12 most active modules within the nova subdirectory.

# Dependencies
To successfully run this script, it is recommended that nodejs v18.2.0 or higher is installed, otherwise the 'for await' functions that are used in this script which are not supported by earlier versions of node would throw errors.
<br><br>
Vs Code will also be required to run this script. The Octokit library would be needed. It can be installed using 'npm install octokit'. Finally, a github api key would be needed to make this script run. A Github Personal access token would do just fine.
