Some Apps for owncloud
========

If anybody wants to stand in for the development of the app, feel free to use my code The upcoming release 2.5.1 of roundcube and storage charts 2 will be the last release. It takes to much time and money supporting this kind of development.

[![Build Status](https://martinreinhardt-online.de/jenkins/buildStatus/icon?job=OwnCloud_nightly)](https://martinreinhardt-online.de/jenkins/job/OwnCloud_nightly/)

In this repo you'll find apps and enhancements for owncloud. 

Feel free to donate

<a href='http://www.pledgie.com/campaigns/23447'><img alt='Click here to lend your support to: Owncloud Apps and make a donation at www.pledgie.com !' src='http://www.pledgie.com/campaigns/23447.png?skin_name=chrome' border='0' /></a>

Or via PayPal: 

<a target="_blank" href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2SAK2NYWB8QA2">
<img alt="" border="0" src="https://www.paypalobjects.com/de_DE/DE/i/btn/btn_donateCC_LG.gif"/>
</img></a>

## Apps

### Currently released
* [Roundcube](roundcube/README.md)
* [StorageCharts](storagecharts2/README.md)

### In Development
* [revealjs](revealjs/README.md)

## Development

see [Wiki](https://github.com/hypery2k/owncloud/wiki/Development-Setup) for details about the setup for development.
A Maven-Site is also [available](https://martinreinhardt-online.de/jenkins/job/OwnCloud_nightly/site/).

Nightly Builds are [available](https://martinreinhardt-online.de/jenkins/job/OwnCloud_nightly/). See the download last successfull artifacts in the middle of the screen

To run all unit tests execute

```mvn clean test```

To run only javascript test go to one module and execute

```grunt test```

For javascript unit test debugging execute:

```karma start src/test/webapp/karma.conf.js```
 
and point your browser to http://localhost:9080/
