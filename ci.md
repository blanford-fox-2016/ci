# tamatamvan
https://travis-ci.org/tamatamvan/tamvan-travis-ci-test

### Raw Log
```
Using worker: worker-linux-docker-b5fece4d.prod.travis-ci.org:travis-linux-5

Build system information
Build language: node_js
Build group: stable
Build dist: precise
Build id: 174115770
Job id: 174115771
travis-build version: 628c8d2e6
Build image provisioning date and time
Thu Feb  5 15:09:33 UTC 2015
Operating System Details
Distributor ID:	Ubuntu
Description:	Ubuntu 12.04.5 LTS
Release:	12.04
Codename:	precise
Linux Version
3.13.0-29-generic
Cookbooks Version
a68419e https://github.com/travis-ci/travis-cookbooks/tree/a68419e
GCC version
gcc (Ubuntu/Linaro 4.6.3-1ubuntu5) 4.6.3
Copyright (C) 2011 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

LLVM version
clang version 3.4 (tags/RELEASE_34/final)
Target: x86_64-unknown-linux-gnu
Thread model: posix
Pre-installed Ruby versions
ruby-1.9.3-p551
Pre-installed Node.js versions
v0.10.36
Pre-installed Go versions
1.4.1
Redis version
redis-server 2.8.19
riak version
2.0.2
MongoDB version
MongoDB 2.4.12
CouchDB version
couchdb 1.6.1
Neo4j version
1.9.4
RabbitMQ Version
3.4.3
ElasticSearch version
1.4.0
Installed Sphinx versions
2.0.10
2.1.9
2.2.6
Default Sphinx version
2.2.6
Installed Firefox version
firefox 31.0esr
PhantomJS version
1.9.8
ant -version
Apache Ant(TM) version 1.8.2 compiled on December 3 2011
mvn -version
Apache Maven 3.2.5 (12a6b3acb947671f09b81f49094c53f426d8cea1; 2014-12-14T17:29:23+00:00)
Maven home: /usr/local/maven
Java version: 1.7.0_76, vendor: Oracle Corporation
Java home: /usr/lib/jvm/java-7-oracle/jre
Default locale: en_US, platform encoding: ANSI_X3.4-1968
OS name: "linux", version: "3.13.0-29-generic", arch: "amd64", family: "unix"

$ export DEBIAN_FRONTEND=noninteractive
W: Size of file /var/lib/apt/lists/us.archive.ubuntu.com_ubuntu_dists_precise-updates_restricted_binary-amd64_Packages.gz is not what the server reported 19576 20785
W: Size of file /var/lib/apt/lists/us.archive.ubuntu.com_ubuntu_dists_precise-updates_restricted_binary-i386_Packages.gz is not what the server reported 19521 20707
W: Size of file /var/lib/apt/lists/us.archive.ubuntu.com_ubuntu_dists_precise-backports_multiverse_source_Sources.gz is not what the server reported 5886 5888
W: Size of file /var/lib/apt/lists/ppa.launchpad.net_travis-ci_zero-mq_ubuntu_dists_precise_main_binary-amd64_Packages.gz is not what the server reported 832 1195
W: Size of file /var/lib/apt/lists/ppa.launchpad.net_ubuntugis_ppa_ubuntu_dists_precise_main_binary-amd64_Packages.gz is not what the server reported 33653 36677
W: Size of file /var/lib/apt/lists/ppa.launchpad.net_ubuntugis_ppa_ubuntu_dists_precise_main_binary-i386_Packages.gz is not what the server reported 33699 36733
W: Size of file /var/lib/apt/lists/security.ubuntu.com_ubuntu_dists_precise-security_restricted_binary-amd64_Packages.gz is not what the server reported 13782 14904
W: Size of file /var/lib/apt/lists/security.ubuntu.com_ubuntu_dists_precise-security_restricted_binary-i386_Packages.gz is not what the server reported 13751 14885
Reading package lists...
Building dependency tree...
Reading state information...
The following extra packages will be installed:
  libc-bin libc-dev-bin libc6-dev
Suggested packages:
  glibc-doc
The following packages will be upgraded:
  libc-bin libc-dev-bin libc6 libc6-dev
4 upgraded, 0 newly installed, 0 to remove and 246 not upgraded.
Need to get 8,840 kB of archives.
After this operation, 14.3 kB disk space will be freed.
Get:1 http://us.archive.ubuntu.com/ubuntu/ precise-updates/main libc6-dev amd64 2.15-0ubuntu10.15 [2,943 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ precise-updates/main libc-dev-bin amd64 2.15-0ubuntu10.15 [84.7 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu/ precise-updates/main libc-bin amd64 2.15-0ubuntu10.15 [1,177 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu/ precise-updates/main libc6 amd64 2.15-0ubuntu10.15 [4,636 kB]
Fetched 8,840 kB in 0s (38.3 MB/s)
Preconfiguring packages ...
(Reading database ... 69991 files and directories currently installed.)
Preparing to replace libc6-dev 2.15-0ubuntu10.10 (using .../libc6-dev_2.15-0ubuntu10.15_amd64.deb) ...
Unpacking replacement libc6-dev ...
Preparing to replace libc-dev-bin 2.15-0ubuntu10.10 (using .../libc-dev-bin_2.15-0ubuntu10.15_amd64.deb) ...
Unpacking replacement libc-dev-bin ...
Preparing to replace libc-bin 2.15-0ubuntu10.10 (using .../libc-bin_2.15-0ubuntu10.15_amd64.deb) ...
Unpacking replacement libc-bin ...
Processing triggers for man-db ...
Setting up libc-bin (2.15-0ubuntu10.15) ...
(Reading database ... 69990 files and directories currently installed.)
Preparing to replace libc6 2.15-0ubuntu10.10 (using .../libc6_2.15-0ubuntu10.15_amd64.deb) ...
Unpacking replacement libc6 ...
Setting up libc6 (2.15-0ubuntu10.15) ...
Setting up libc-dev-bin (2.15-0ubuntu10.15) ...
Setting up libc6-dev (2.15-0ubuntu10.15) ...
Processing triggers for libc-bin ...
ldconfig deferred processing now taking place
$ git clone --depth=50 --branch=master https://github.com/tamatamvan/tamvan-travis-ci-test.git tamatamvan/tamvan-travis-ci-test
Cloning into 'tamatamvan/tamvan-travis-ci-test'...
remote: Counting objects: 15, done.
remote: Compressing objects: 100% (13/13), done.
remote: Total 15 (delta 2), reused 10 (delta 1), pack-reused 0
Unpacking objects: 100% (15/15), done.
Checking connectivity... done.

$ cd tamatamvan/tamvan-travis-ci-test
$ git checkout -qf c038aaab81f56a96dedbcd8e3240cc67a8d39469

This job is running on container-based infrastructure, which does not allow use of 'sudo', setuid and setguid executables.
If you require sudo, add 'sudo: required' to your .travis.yml
See https://docs.travis-ci.com/user/workers/container-based-infrastructure/ for details.
Updating nvm to v0.32.0
$ nvm install 6
######################################################################## 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v6.9.1 (npm v3.10.8)

Starting with io.js 3 and Node.js 4, building native extensions requires C++11-compatible compiler, which seems unavailable on this VM. Please read https://docs.travis-ci.com/user/languages/javascript-with-nodejs#Node.js-v4-(or-io.js-v3)-compiler-requirements.
$ node --version
v6.9.1
$ npm --version
3.10.8
$ nvm --version
0.32.0
$ npm install
testing-everything@1.0.0 /home/travis/build/tamatamvan/tamvan-travis-ci-test
├─┬ chai@3.5.0
│ ├── assertion-error@1.0.2
│ ├─┬ deep-eql@0.1.3
│ │ └── type-detect@0.1.1
│ └── type-detect@1.0.0
└─┬ mocha@3.1.2
  ├── browser-stdout@1.3.0
  ├─┬ commander@2.9.0
  │ └── graceful-readlink@1.0.1
  ├─┬ debug@2.2.0
  │ └── ms@0.7.1
  ├── diff@1.4.0
  ├── escape-string-regexp@1.0.5
  ├─┬ glob@7.0.5
  │ ├── fs.realpath@1.0.0
  │ ├─┬ inflight@1.0.6
  │ │ └── wrappy@1.0.2
  │ ├── inherits@2.0.3
  │ ├─┬ minimatch@3.0.3
  │ │ └─┬ brace-expansion@1.1.6
  │ │   ├── balanced-match@0.4.2
  │ │   └── concat-map@0.0.1
  │ ├── once@1.4.0
  │ └── path-is-absolute@1.0.1
  ├── growl@1.9.2
  ├── json3@3.3.2
  ├─┬ lodash.create@3.1.1
  │ ├─┬ lodash._baseassign@3.2.0
  │ │ ├── lodash._basecopy@3.0.1
  │ │ └─┬ lodash.keys@3.1.2
  │ │   ├── lodash._getnative@3.9.1
  │ │   ├── lodash.isarguments@3.1.0
  │ │   └── lodash.isarray@3.0.4
  │ ├── lodash._basecreate@3.0.3
  │ └── lodash._isiterateecall@3.0.9
  ├─┬ mkdirp@0.5.1
  │ └── minimist@0.0.8
  └─┬ supports-color@3.1.2
    └── has-flag@1.0.0


$ npm install

$ npm i -g mocha
/home/travis/.nvm/versions/node/v6.9.1/bin/mocha -> /home/travis/.nvm/versions/node/v6.9.1/lib/node_modules/mocha/bin/mocha
/home/travis/.nvm/versions/node/v6.9.1/bin/_mocha -> /home/travis/.nvm/versions/node/v6.9.1/lib/node_modules/mocha/bin/_mocha
/home/travis/.nvm/versions/node/v6.9.1/lib
└─┬ mocha@3.1.2
  ├── browser-stdout@1.3.0
  ├─┬ commander@2.9.0
  │ └── graceful-readlink@1.0.1
  ├─┬ debug@2.2.0
  │ └── ms@0.7.1
  ├── diff@1.4.0
  ├── escape-string-regexp@1.0.5
  ├─┬ glob@7.0.5
  │ ├── fs.realpath@1.0.0
  │ ├─┬ inflight@1.0.6
  │ │ └── wrappy@1.0.2
  │ ├── inherits@2.0.3
  │ ├─┬ minimatch@3.0.3
  │ │ └─┬ brace-expansion@1.1.6
  │ │   ├── balanced-match@0.4.2
  │ │   └── concat-map@0.0.1
  │ ├── once@1.4.0
  │ └── path-is-absolute@1.0.1
  ├── growl@1.9.2
  ├── json3@3.3.2
  ├─┬ lodash.create@3.1.1
  │ ├─┬ lodash._baseassign@3.2.0
  │ │ ├── lodash._basecopy@3.0.1
  │ │ └─┬ lodash.keys@3.1.2
  │ │   ├── lodash._getnative@3.9.1
  │ │   ├── lodash.isarguments@3.1.0
  │ │   └── lodash.isarray@3.0.4
  │ ├── lodash._basecreate@3.0.3
  │ └── lodash._isiterateecall@3.0.9
  ├─┬ mkdirp@0.5.1
  │ └── minimist@0.0.8
  └─┬ supports-color@3.1.2
    └── has-flag@1.0.0


$ mocha


  add function will return the sum result of both parameter
    ✓ should sum first parameter and second parameter
    ✓ should give message that add function need 2 number as parameters
    ✓ should give message that the function need 2 parameters
    ✓ should give message that the function need 2 parameters


  4 passing (11ms)



The command "mocha" exited with 0.

Done. Your build exited with 0.
```
