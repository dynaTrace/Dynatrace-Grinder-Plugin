<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Grinder Plugin</title>
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
                <h1>Grinder Plugin</h1>
    <div class="section-2"  id="93520396_GrinderPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/93520396/grinder-logo.png" alt="images_community/download/attachments/93520396/grinder-logo.png" class="" />
            </p>
    <p>
The Grinder plugin queries performance values while executing a test.<br/>The plugin uses Grinder's REST Interface to query the following metrics:    </p>
<ol class=" "><li class=" ">    <p>
Total Response Time    </p>
</li><li class=" ">    <p>
Number of Tests Executed    </p>
</li><li class=" ">    <p>
Number of Errors    </p>
</li><li class=" ">    <p>
Total Standard Deviation    </p>
</li><li class=" ">    <p>
Total TPS    </p>
</li><li class=" ">    <p>
Total Peak TPS    </p>
</li></ol>    </div>
    <div class="section-2"  id="93520396_GrinderPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Files    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_94404609_1_org.measuredprogress.dynatrace.plugin.monitor.GrinderPlugin_1.0.0.jar">org.measuredprogress.dynatrace.plugin.monitor.GrinderPlugin_1.0.0.jar</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Marc Holden (Holden.Marc@measuredprogress.org)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.1+    </p>
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
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2012-09-04 Initial Release    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="93520396_GrinderPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server via the dynaTrace Server Settings menu -&gt; Plugins -&gt; Install Plugin. For details how to do this please refer to the <a href="https://apmcommunity.compuware.com/community/display/DOCDT42/Plugins">dynaTrace documentation</a>.    </p>
    </div>
    <div class="section-2"  id="93520396_GrinderPlugin-Configuration"  >
        <h2>Configuration</h2>
    <p>
This plugin talks to the Grinder Console running on a miminium version of 3.10 (Grinder 3.10 is the first Grinder release with REST API).    </p>
    <p>
Once you have the plugin installed you can create a new monitor as shown in the following screenshots:    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/93520396/Configure_3.png" alt="images_community/download/attachments/93520396/Configure_3.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/93520396/Configure_2.png" alt="images_community/download/attachments/93520396/Configure_2.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/93520396/Configure_1.png" alt="images_community/download/attachments/93520396/Configure_1.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="93520396_GrinderPlugin-Results"  >
        <h2>Results</h2>
    <p>
The following screenshot shows a dashboard displaying some of the measures queried by the monitor:    </p>
    <p>
            <img src="images_community/download/attachments/93520396/Results.png" alt="images_community/download/attachments/93520396/Results.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="93520396_GrinderPlugin-FeedbackandComments"  >
        <h2>Feedback and Comments</h2>
    <p>
Please use the <a href="https://community/display/DTFORUM/Community+Plugins+and+Extensions">Community Plugins and Extensions</a> to discuss feedback and questions    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>