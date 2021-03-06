# api-platform-test-user

[![Build Status](https://travis-ci.org/hmrc/api-platform-test-user.svg)](https://travis-ci.org/hmrc/api-platform-test-user) [ ![Download](https://api.bintray.com/packages/hmrc/releases/api-platform-test-user/images/download.svg) ](https://bintray.com/hmrc/releases/api-platform-test-user/_latestVersion)

This is the backend microservice for the creation of test users in the API Platform for the External Test Environment.
Test users and organisations are stored in mongo.

It exposes two endpoints as documented on the [developer sandbox]().

### Running tests

Unit and integration tests can be run with the following bash script:

    ./run_all_tests.sh

Note that integration tests require a running version of Mongo 3.2, listening on localhost:27017. A simple way to achieve this
is to run with a docker image:

    docker run -p 27017:27017 --name mongo -d mongo:3.2

### License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html")

