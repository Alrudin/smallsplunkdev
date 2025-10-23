# smallsplunkdev

Start by running docker compose up
If you want to install an app, download from splunkbase.splunk.com
then put it in the public folder, you can now install it by adding it to the line 

SPLUNK_APPS_URL=http://web/splunk-add-on-for-microsoft-visual-studio-code_013.tgz,http://web/splunk-add-on-for-unix-and-linux_1010.tgz

If you don't have a dev license comment out the line

SPLUNK_LICENSE_URI=http://web/Splunk.License

You need to add splunk password