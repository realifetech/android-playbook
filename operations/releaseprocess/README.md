# Release process

## CircleCI integration
On every push of code our CI will create a build
For the release process we will trigger a build job from master using a set of params that provides a specific flavour and build type as "release"

## Submission materials
This is usual a duty of out PMO for the specific flavour, but it always has the version number, the "what's new" text plus all the changes regarding the store presence, like images text hi-res icon ect.

## Requests for submission
Requests to submit an app for Google Playstore review must come via the **Request Android Submission** workflow in the **app-releases** Slack channel:  
<p align="center">
    <img src="request-android-submission.png">
</p>

## Releasing to the :earth_africa:
Requests to release an app that have been approved by Google should come via the **app-releases** Slack channel.  
We should respond to them using the **Document Android Release** workflow, checking off the items as we complete them. Details on each item can be found below.  
<p align="center">
    <img src="document-android-release.png">
</p>

## Timings:
**CircleCI:** ~20 minutes  
**Play Store processing:** ~48 hours for upgrade , up to 7 days for a new app  
**Play Store time:** ~1 day
