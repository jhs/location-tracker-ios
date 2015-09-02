# iOS Location Tracker

The iOS Location Tracker is a demo iOS application which records a device's location and saves this information to the IBM Cloud, with offline support.

## Objective

Basically this is simply converting the web application of the same name into an iOS app, using [Cloudant Sync].

Also, excluding Cordova, this is my first native iOS app project and my first Swift project. Wish me luck!

## Plan

1. Ship a Swift "Hello World"
  * Code in this Git project
  * Documentation for how to build it yourself
1. Get [Cloudant Sync] compiled in but inert
  1. Figure out [CocoaPods]
  1. Determine whether to track [CocoaPods in Git]
1. Determine integration with [Node.js project][tracker-nodejs], if any
  * Run a Node.js API server?
  * Use Bradley's upcoming API server?
1. Determine integration with [CouchApp project][tracker-couch], if any
1. I have not thought any further ahead.

[CocoaPods]: https://cocoapods.org/
[CocoaPods in Git]: http://guides.cocoapods.org/using/using-cocoapods.html#should-i-check-the-pods-directory-into-source-control
[Cloudant Sync]: https://github.com/cloudant/CDTDatastore#readme
[tracker-nodejs]: https://github.com/cloudant-labs/location-tracker-nodejs
[tracker-couch]: https://github.com/cloudant-labs/location-tracker-couchapp
