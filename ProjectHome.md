<font color='red'><b>jSQL Injection project has <a href='https://github.com/ron190/jsql-injection'>moved</a>, jSQL alpha v0.6 is now available on <a href='https://github.com/ron190/jsql-injection/releases'>Github</a>.</b></font>
<br>
<br>
<b>Description</b>

<b>jSQL Injection</b> is a lightweight application used to find database information from a distant server.<br>
jSQL is <b>free</b>, open source and cross-platform (Windows, Linux, Mac OS X, Solaris).<br>
<br>
<hr />
<br>
<b>Screenshot of alpha v0.6</b><br>
<br>
<a href='https://sites.google.com/site/jsqlinjection/home/images/alpha-v0.6.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/alpha-v0.6-mini.png' /></a><br>
<br>
<b>jSQL Injection change log</b>

<b>alpha-v0.6</b><code>  Speed x 2 (no more hex encoding), 10 db vendors supported: MySQL Oracle MSSQLServer PostgreSQL DB2 Firebird Informix Ingres MaxDb Sybase. JUnit tests, log4j, i18n integration and more.</code><br>
<br>
<b>Coming...</b><code>  JUnit tests with Hibernate, Github issues with OAuth, i18n arabic russian chinese integration, database vendors: SQLite Access MSDE MariaDB Derby 4D Cassandra Teradata CUBRID HSQLDB.</code>
<br>
<br>
<hr />

<b>Screenshots</b>

<a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-database.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-database-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-admin.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-admin-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-file.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-file-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-webshell.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-webshell-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-sqlshell.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-sqlshell-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-upload.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-upload-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-bruteforce.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-bruteforce-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-coder.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201309272136-screenshot-coder-mini.png' /></a>
<br><br>
<hr />

<img src='https://sites.google.com/site/jsqlinjection/home/images/kali_favicon.png' /> jSQL is part of <a href='http://www.kali.org/'>Kali Linux</a>, the official penetration distribution. jSQL is also included in <a href='http://www.parrotsec.org/tools/tools-web/'>Parrot Security OS</a>, <a href='http://tools.pentestbox.com/'>PentestBox</a>, <a href='http://www.blackhat-sec.com/'>Black Hat Sec</a>, <a href='https://archassault.org/'>ArchAssault Project</a>, <a href='http://www.blackarch.org/'>BlackArch Linux</a> and <a href='http://cyborg.ztrela.com/'>Cyborg Hawk Linux</a>.<br>
<hr />

<br>
<b>jSQL Injection change log</b>

<b>v0.5</b><code>  SQL shell, Uploader.</code><br>
<b>v0.4</b><code>  Admin page search, Brute force (md5 mysql...), Decoder (decode encode base64 hex md5...).</code><br>
<b>v0.3</b><code>  Distant file reader, Webshell drop, Terminal for webshell commands, Configuration backup, Update checker.</code><br>
<b>v0.2</b><code>  Time based algorithm, Multi-thread control (start pause resume stop), Shows URL calls.</code><br>
<b>v0.1</b><code>  -</code><br>
<b>v0.0</b><code>  Methods GET / POST / header / cookie, Algorithms Normal / Error / Blind, Automatic best algorithm selection, Progression bars, Simple evasion, Proxy setting, Supports MySQL.</code><br>

<br>
<font color='#008000' face='courier new'><b>+--------------+</b></font><br>
<font color='#008000' face='courier new'><b>| Contributors |</b></font><br>
<font color='#008000' face='courier new'><b>+--------------+</b></font><br>
There is a lot of work to do if you want to contribute.<br>
Examples of features to include in next releases:<br>

<ol><li><code>Add support for another database provider like </code><font color='#800000' face='courier new'><u>Oracle</u></font><code> and </code><font color='#800000' face='courier new'><u>SQL Server</u></font><code>,</code><br>
</li><li><code>Support </code><font color='#800000' face='courier new'><u>command line execution</u></font><code> and batch processing,</code><br>
</li><li><code>Internationalization </code><font color='#800000' face='courier new'><u>i18n</u></font><code> in Arabic, Hindi, Chinese, Russian, French, German and Japanese,</code><br>
</li><li><code>Find vulnerable targets from </code><font color='#800000' face='courier new'><u>dork list</u></font><code>,</code><br>
</li><li><code>Create </code><font color='#800000' face='courier new'><u>JUnit testing</u></font><code> to avoid regressions,</code><br>
</li><li><code>Improve </code><font color='#800000' face='courier new'><u>code design</u></font><code> and </code><font color='#800000' face='courier new'><u>pattern</u></font><code>,</code><br>
</li><li><code>Enhance injection functionalities like evasion and speed,</code><br>
</li><li><code>Write documentation: wiki, tutorial, video.</code></li></ol>

<br>
Other upcoming tasks:<br>
<code>+ Upload via temporary table and 'into dumpfile' [inj]</code><br>
<code>+ Netcat connection (upload server) [dev]</code><br>
<code>+ Manual injection for advanced users [inj]</code><br>
<code>+ Controlling all running tasks in same panel [gui]</code><br>
<code># Shrink / optimize runnable jar with </code><a href='http://proguard.sourceforge.net'>ProGuard</a><code> [dev]</code><br>
<code># Inlude Strategy Pattern: GET / POST / header / cookie [design]</code><br>
<code># Inlude Command Pattern: expand terminal functionalities [design]</code><br>
<code># Increase speed (non encoding pass): 50% faster [inj]</code><br>
<code># Unit testing with </code><a href='http://junit.org'>JUnit</a><code>: GET / POST / header / cookie, Normal / Error / Blind / Time [dev]</code><br>
<code># Provide Continuous Integration with </code><a href='http://hudson-ci.org'>Hudson</a> / <a href='http://jenkins-ci.org'>Jenkins</a><code> [dev]</code><br>
<code># Code Quality improvement with </code><a href='http://www.sonarqube.org/'>SonarQube</a> / <a href='http://checkstyle.sourceforge.net/'>Checkstyle</a><code> passes [dev]</code><br>
<code># Compare functionalities with other tools [dev]</code><br>
<br>
<hr />

<br>
<b>Installation</b>

Apart from installing Java, there is no installation. Download the .jar file and voilà.<br>
So, install <a href='http://java.com'>java</a> then download <a href='http://code.google.com/p/jsql-injection/downloads/list'>the latest jSQL executable</a> and double click on the .jar file to open the main window (or you may type in a terminal: <code>java -jar jsql-injection-v0.5.jar</code>, or right click on file, choose "Open with..." and select "Java(TM) Platform SE binary").<br>
<br>
<b>Forum</b>

You can request features and discuss about algorithm, programming and functionality in the <a href='https://groups.google.com/forum/?fromgroups#!forum/jsql-injection'>forum</a>.<br>
<br>
<b>Injection and local test</b>

Running injection requires the URL of a local or distant server, and the name of parameter to inject.<br>
For a local test, you can save the following PHP code into file 'simulate_get.php' and move it to the root folder of your web server (e.g /www), then use <code>http://127.0.0.1/simulate_get.php?lib=</code> in jSQL, and finally click Connect to read the local database:<br>
<pre><code>&lt;?php<br>
    mysql_connect("localhost", "root", "");<br>
    mysql_select_db("mysql");<br>
<br>
    $result = mysql_query("SELECT * FROM user where user = " . $_GET['lib']) # time based<br>
        or die( mysql_error() ); # error based<br>
<br>
    if( mysql_num_rows($result) !== 0 ) echo " something "; # blind<br>
<br>
    while( $row = mysql_fetch_array($result, MYSQL_NUM) )<br>
        echo join(',',$row); # normal<br>
?&gt;<br>
</code></pre>

<b>Programming</b>

Source code can be read and downloaded from the Google Git <a href='http://code.google.com/p/jsql-injection/source/browse/src/com/jsql/#jsql%2Fmvc%2Fmodel'>repository</a>.<br>
Tools used during development are w7 jre7 eclipse egit easyphp notepad++ virtualbox googlecode github.<br>
<br>
<u>Screenshot</u>: jSQL on Linux, Mac OS X and Solaris<br>
<br>
<a href='https://sites.google.com/site/jsqlinjection/home/images/201303101445-screenshot-linux.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201303101445-screenshot-linux-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201303101445-screenshot-mac-os-x.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201303101445-screenshot-mac-os-x-mini.png' /></a> <a href='https://sites.google.com/site/jsqlinjection/home/images/201303240622-screenshot-solaris.png'><img src='https://sites.google.com/site/jsqlinjection/home/images/201303240622-screenshot-solaris-mini.png' /></a>
<br><br>
<hr />
<b><u>Your support is important</u></b><br>
Support the development of jSQL, you can do any (or all) of the following:<br>
- Spread the word,<br>
- Fork the project and contribute on Github,<br>
- Star the project homepage or the download page (the star is displayed if you have logged previously into your Google account),<br>
- Become a member of jSQL group,<br>
- Post a comment in the forum or by email.<i><br></i><br>
<hr />
<br>
<b>Disclaimer</b><br>
Attacking web-server is illegal without prior mutual consent. The end user is responsible and obeys all applicable laws.<br>
Developers assume no liability and are not responsible for any misuse or damage caused by this program.