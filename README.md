# myFlix

Run your own personal web streaming site. Written in Erlang for performance on the ChicagoBoss framework.

## Usage

* Copy over the src files.
* [See here](https://github.com/ChicagoBoss/ChicagoBoss/wiki/Quickstart)
* edit boss.config for your database and network interface binding needs.

By default it uses in-memory "mock" db you'll want to use an adapter to setup a persistant database for productions I use the bossDB postgrel adaptor and it was simple.

### To do

I accidentally deleted all the css/html templates when I was moving to CB from node.js so alot to do.

### History

* 2014 PHP - cluttered but working
* 2015 Python - Okay performance automatically parsed videos from my anal directory heirachy.
* 2016 Node.js - For some reason I wanted a single page application
* 2018 Erlang baby. I have a raspberry pi server setup and Node was turning into a sluggish faff as the SPA used serverside rendering for the MCV. Works suprisingly well against expectations.
