# GcmNetworkManager Quickstart [DEPRECATED]

**Last year, we announced Android Jetpack [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager/). WorkManager, the new job management system in Jetpack, incorporates the features of Firebase Job Dispatcher (FJD) and Android’s [JobScheduler](https://developer.android.com/reference/android/app/job/JobScheduler)
to provide a consistent job scheduling service back to api level 14 while
leveraging JobScheduler on newer devices. WorkManager works with or without
Google Play Services. WorkManager was first released to alpha in May 2018 and then went thru extensive iteration and improvement based on developer feedback including 10 alphas; it moved to beta on Dec 19, 2018, and was released to [stable](https://developer.android.com/jetpack/androidx/releases/work#1.0.0) on Mar 5, 2019. One thing the team has been discussing at some length is whether it would be better for developers in the long run if we create one holistic solution via WorkManager; where we can pool all of our efforts and also give developers a single unified recommended path?**

**After careful evaluation, the team has decided to focus all of our efforts on WorkManager and to deprecate GCMNetworkManager. We have modified our plans in direct response to developer feedback in order to make this as easy for you as possible. We know that managing background work is a critical part of your app and these changes impact you. We want to support you through this migration as much as we can by giving you as much advance notice as possible to make these changes. Firebase Job Dispatcher will be archived in github in about 1 year, on Apr 7, 2020. Apps should migrate to WorkManager or an alternative job management system before this date.**

**We are continuing to invest in and add new features to WorkManager and welcome any feedback or feature [requests](https://issuetracker.google.com/issues/newcomponent=409906&template=1094197).**

This sample demonstrates how to use the GcmNetworkManager API.

## Introduction

GcmNetworkManager can be used to reliably schedule network operations in your application based
on time, charging status, connectivity, and other variables.  GcmNetworkManager is similar to the
Android [JobScheduler](http://developer.android.com/reference/android/app/job/JobScheduler.html)
API which is available on all Android devices running Lollipop or higher, however GcmNetworkManager
is available on any device running Google Play Services.

For more information on GcmNetworkManager, visit:
https://developers.google.com/cloud-messaging/network-manager

## Prerequisites

In order to run this quickstart sample you will need:
 
  * Android Studio v1.4 or higher
  * An Android device with Google Play Services 8.3 or higher
  * A USB cable

## Getting Started

To run the quickstart application:
  
  * Import the project into Android Studio
  * Connect your Android device over USB, with USB debugging enabled
  * Click **Run** > **Run 'app'**
  
## Support

  * [GCM on Stack Overflow](http://stackoverflow.com/questions/tagged/google-cloud-messaging)
