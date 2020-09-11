# Version History

## [1.0.0-alpha2](https://www.github.com/bcoe/functions-framework-dotnet-test/compare/v1.0.0-alpha1...v1.0.0-alpha2) (2020-09-11)


### Features

* added an amazing new feature (it is a newline) ([c965946](https://www.github.com/bcoe/functions-framework-dotnet-test/commit/c96594613c01103aec006a4a271f6db819b27eb6))

## 1.0.0-alpha1 (2020-09-11)


### Features

* initial generation of library ([6095193](https://www.github.com/bcoe/functions-framework-dotnet-test/commit/6095193e268082b6757625d4aefa3eb49992ccab))

## 1.0.0-alpha08 (released 2020-07-07)

- Added an in-memory logger provider to the test server
- Moved the event data classes out of the Functions Framework into
  `Google.Events.*`. We have a dependency on `Google.Events` but
  not on any specific serialization strategy.
- Changed the shape of the PubSub CloudEvent data to match the event
  on Cloud Run. (The message is wrapped in another class that will
  eventually contain the subscription name.)
- Separated out the bucket name (source) and object name (subject) for
  storage CloudEvents.

## 1.0.0-alpha07 (released 2020-06-02)

Latest version available when deploying to Google Cloud Functions
(`gcloud functions deploy`) became available via a restricted public
alpha.
