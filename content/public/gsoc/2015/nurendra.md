---
title: "Sentiment Analysis / Realtime Translation with Google Translate/Apertium"
---

### Projects

 - Realtime Translation using Google Translate
 - Realtime Translation using Apertium
 - Web application to compare statistics of Stock Price, TV Mentions and Twitter

### Technical Documentation

All the technical details are commented in the codes and the
documentation is available in the Readme's of their directories. The
variables, classes and other components of the code are named properly
in Camel Case for easier understanding of the code.  

 **Repositories:**

 * [https://github.com/Akirato/goslateTranslator](https://github.com/Akirato/goslateTranslator) - Google Translate Translator
 * [https://github.com/Akirato/apertiumTranslator](https://github.com/Akirato/apertiumTranslator) - Apertium Translator
 * [https://github.com/Akirato/sentimentAnalysisTool](https://github.com/Akirato/sentimentAnalysisTool) - Tool for Sentiment Analysis
 * [https://github.com/Akirato/statsChart](https://github.com/Akirato/statsChart) - The entire web application for statistics comparison
 * [https://github.com/Akirato/statsChart-backend](https://github.com/Akirato/statsChart-backend) - The backend of the statistics web application

### How to use?

#### Google Translate and Apertium Realtime Translation

The instruction to use the codes directly are given in the Readme of
the repositories. A sample of translator from English to Spanish
is available at
<http://gsocdev.ccextractor.org/~nurendra/translated/test2/tail.php>

#### Web Application for comparing Statistics

The application is presently hosted at
<https://95.211.109.210/statsChart/default/index>  It has been built
on Web2py framework.

 - Make a MySQL database called "statschart" and run the three scripts given in [https://github.com/Akirato/statsChart-backend](https://github.com/Akirato/statsChart-backend)
 - Download web2py from [http://web2py.com/init/default/download](http://web2py.com/init/default/download)
 - Clone [https://github.com/Akirato/statsChart](https://github.com/Akirato/statsChart) into web2py/applications/
 - Go to web2py/application/statsChart/models/db.py and connect your databases.
 - Run the web2py server.
 - The application should be hosted at <host-server>/statsChart/default/index

 **Deployment on a new server:**

 - Make a MySQL database on the server called "statschart" and run the three scripts given in [https://github.com/Akirato/statsChart-backend](https://github.com/Akirato/statsChart-backend)
 - Install and deploy web2py on a new server.
 - Several Deployment Recipes for common servers are given at [http://web2py.com/books/default/chapter/29/13/deployment-recipes](http://web2py.com/books/default/chapter/29/13/deployment-recipes)
 - After this is done, a web2py/ directory will be made in the server.
 - Clone [https://github.com/Akirato/statsChart](https://github.com/Akirato/statsChart) into web2py/applications/
 - Go to web2py/application/statsChart/models/db.py and connect your databases.
 - Run the web2py server.
 - The application should be hosted at <host-server>/statsChart/default/index

### How to evaluate?

#### Google Translate and Apertium Realtime Translation

Repositories of both the translators have methodAnalysis/analyse.py
file. Execute this file if the code is working properly. Also
English->Spanish realtime translation is available at
<http://gsocdev.ccextractor.org/~nurendra/translated/test2/tail.php>

#### Web Application for comparing Statistics

The web application is hosted on
<https://95.211.109.210/statsChart/default/index>  To look at the
entire code, go to <https://95.211.109.210/admin/default/index> Give the
password: "akirato123" and select "statsChart" to check the entire
code.

### Contribution to blog

The subtitles generated by CCExtractor can now be translated and be made
available to a larger audience due to the realtime translation tool.
The tool uses Google Translate and Apertium to provide online and
offline translation respectively. The Statistics website collects
data from Twitter using Twitter API, from TV advertisements using
CCExtractor and shows it effects on the Stock Price which are updated
using Google  Finance. This will be very useful for opinion
collection and looking at the effects of advertisements on Social
Media.
