<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Google Analytics FastPack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Google Analytics FastPack</h1>
    <div class="section-2"  id="35323942_GoogleAnalyticsFastPack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/35323942/icon.png" alt="images_community/download/attachments/35323942/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
    </p>
    <p>
The dynaTrace FastPack for Google Analytics enables easy out-of-the-box monitoring of Google Analytics Data in your dynaTrace Environment. It allows you to correlate Analytics Data with Application Performance and Infrastructure Data. The FastPack consists of a custom Monitor, a sample System Profile and a Dashboard.    </p>
    </div>
    <div class="section-2"  id="35323942_GoogleAnalyticsFastPack-FastPackDetails"  >
        <h2>Fast Pack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Google Analytics FastPack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
3.5    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace software    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Community Supported </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_35487748_1_GoogleAnalytics_SystemProfile_and_Dashboard.zip">System Profile and Dashboards </a><br/><a href="attachments_34996231_1_com.dynatrace.diagnostics.plugin.GoogleAnalytics_1.0.0.jar">Plugin Page</a> (<a href="https://community/display/DL/Google+Analytics+Monitor+Plugin">Plugin Page</a>)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="35323942_GoogleAnalyticsFastPack-GoogleAnalyticsDashboard"  >
        <h2>Google Analytics Dashboard</h2>
    <p>
            <img src="images_community/download/attachments/35323942/GADashboard.PNG" alt="images_community/download/attachments/35323942/GADashboard.PNG" class="" />
            </p>
    <p>
The Google Analytics Dashboard visualizes data retrieved through the Google Analytics Monitor plugin.    </p>
<ul class=" "><li class=" ">    <p>
Top Chart: Total Page Views that came from how many Visitors and how many of these were New Visitors    </p>
</li><li class=" ">    <p>
Middle Chart: Total Visitors and how many of them Bounced off the page    </p>
</li><li class=" ">    <p>
Bottom Chart: Total Time on Site    </p>
</li></ul>    <p>
This dashboard assists you analyzing your Google Analytics Data    </p>
    </div>
    <div class="section-2"  id="35323942_GoogleAnalyticsFastPack-GoogleAnalyticsMonitor"  >
        <h2>Google Analytics Monitor</h2>
    <p>
The Google Analytics Monitor plugin enables querying values from any website monitored with Google Analytics.The plugin retrieves values such as PageViews, Vistors, New Visitors, Bounces, Exits, Time on Page and Time on Site. This plugin allows you to view and correlate these values with application or infrastructure measures collected by dynaTrace.<br/>Correlating these values allows you to answer questions like: Is the Bounce Rate going up because I have a problem on my landing pages? Do my PageViews go down because of slow performance transactions?    </p>
    <p>
The monitor requires the following configuration settings:    </p>
<ul class=" "><li class=" ">    <p>
Google Account Name: The Google Account that has access to Google Analytics Data    </p>
</li><li class=" ">    <p>
Google Account Password: The Google Account password    </p>
</li><li class=" ">    <p>
Website: The website that you want to monitor. You can monitor multiple websites with a single Google account. Default is to monitor the first registered website    </p>
</li><li class=" ">    <p>
Return Last Data Entry: If true - the last full data entry value is returned as result. If false - the delta value to the previous retrieved value is returned. The Delta allows you to get metrics as they come in. Google provides data as granular as one hour. If you specify Last Data Entry you will always get the current total number of the current hour.    </p>
</li><li class=" ">    <p>
Include Hours: If true - the plugin retrieves values with hourly granularity. This setting only has an impact if you specify Return Last Data Entry = true.    </p>
</li><li class=" ">    <p>
Log Detailed Analytics Data: if true - the monitor will log all retrieved measures from the Google API to the monitor log    </p>
</li></ul>    </div>
    <div class="section-2"  id="35323942_GoogleAnalyticsFastPack-FastPackInformation"  >
        <h2>FastPack Information</h2>
    <p>
The Google Analytics FastPack contains everything to get started with getting your Analytics Data to dynaTrace.    </p>
<ul class=" "><li class=" ">    <p>
A system profile with preconfigured monitor setup to execute every 10 minutes    </p>
</li><li class=" ">    <p>
Google Analytics Dashboard that shows all Google Analytics data    </p>
</li><li class=" ">    <p>
The Google Analytics Monitor Plugin    </p>
</li></ul>    </div>
    <div class="section-2"  id="35323942_GoogleAnalyticsFastPack-Installation"  >
        <h2>Installation</h2>
<ol class=" "><li class=" ">    <p>
Download and import the Dashboards and the System Profile on your dynaTrace Server    </p>
</li><li class=" ">    <p>
Download and import the Monitor Plugin to your dynaTrace Server    </p>
</li></ol>    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>