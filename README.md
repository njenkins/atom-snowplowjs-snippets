# Snowplow javascript tracker snippets for Atom

[![Build Status](https://travis-ci.org/njenkins/atom-snowplowjs-snippets.svg?branch=master)](https://travis-ci.org/njenkins/atom-snowplowjs-snippets)

Snippets for working with the [Snowplow Javascript Tracker](http://snowplowanalytics.com/) within [Atom](http://atom.io)

## Supported methods
* enableActivityTracking
* newTracker
* setCustomUrl
* setReferrerUrl
* setUserId
* setUserIdFromCookie
* setUserIdFromLocation
* setUserIdFromReferrer
* trackPageView
* trackSocialInteraction
* trackStructEvent
* trackUnstructEvent


## Enable
### enableActivityTracking
#### [spenableact]
```js
${1:snowplow_name_here}(\'enableActivityTracking\', ${2:minimumVisitLength}, ${3:heartBeat});$0
```

## New
### newTracker
#### [spnew]
```js
${1:snowplow_name_here}(\'newTracker\', ${2:trackerNamespace}, ${3:collectorEndpoint}, ${4:argmap});$0
```

## Set
### setCustomUrl
#### [spsetcustomurl]
```js
```

### setReferrerUrl
#### [spsetreferrerurl]
```js
```

### setUserId
#### [spsetuid]
```js
```

### setUserIdFromCookie
#### [spsetuidfromcookie]
```js
```

### setUserIdFromLocation
#### [spsetuidfromloc]
```js
```

### setUserIdFromReferrer
#### [spsetuidfromref]
```js
```

## Track
### trackPageView
#### [sptrackpage]
```js
```

### trackSocialInteraction
#### [sptracksocial]
```js
```

### trackStructEvent
#### [sptrackstruct]
```js
```

### trackUnstructEvent
#### [sptrackunstruct]
```js
```
