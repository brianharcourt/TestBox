
[![Build Status](https://travis-ci.org/Ortus-Solutions/TestBox.svg?branch=development)](https://travis-ci.org/Ortus-Solutions/TestBox)

```
  _____         _   ____            
 |_   _|__  ___| |_| __ )  _____  __
   | |/ _ \/ __| __|  _ \ / _ \ \/ /
   | |  __/\__ \ |_| |_) | (_) >  < 
   |_|\___||___/\__|____/ \___/_/\_\
```

TestBox is a Behavior Driven Development (BDD) and Test Driven Development (TDD) framework for ColdFusion (CFML). It also includes mocking and stubbing capabilities via its internal MockBox library.

## LICENSE

Apache License, Version 2.0.

## IMPORTANT LINKS

Source

- https://github.com/Ortus-Solutions/TestBox

Bug Tracking

- https://ortussolutions.atlassian.net/browse/TESTBOX

Support Forum

- https://groups.google.com/a/ortussolutions.com/forum/#!forum/testbox

Documentation

- https://testbox.ortusbooks.com
- https://testbox.ortusbooks.com/content/primers/bdd/index.html
- https://testbox.ortusbooks.com/content/primers/xunit/index.html

Official Site

- https://www.ortussolutions.com/products/testbox

## SYSTEM REQUIREMENTS

- Lucee 4.5+ (xUnit + BDD)
- ColdFusion 11+ (xUnit + BDD)

## TESTBOX INSTALLATION
You can visit the TestBox documentation page to view all of its features and 
capabilities.  To install TestBox just drop it in your web root as `/testbox` or
create a mapping in your CFML administrator or `Application.cfc` that points to the
directory you installed TestBox and create the mapping `/testbox` that points to it.

You can also use [CommandBox](https://www.ortussolutions.com/products/commandbox) to install and leverage TestBox for commandline executions, test generations, watchers and much more:

**Stable Release**

`box install testbox`

**Bleeding Edge Release**

`box install testbox@be`

Bleeding edge builds are updated automatically as code is committed.

********************************************************************************
Copyright Since 2005 by Luis Majano and Ortus Solutions, Corp

www.ortussolutions.com
********************************************************************************
