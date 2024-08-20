# Project 2 - *SimpleTweet*

**SimpleTweet** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **8** hours spent in total

## User Stories

- [X] User can **compose and post a new tweet**
- [X] User can click a “Compose” icon in the Action Bar on the top right
- [X] User can then enter a new tweet and post this to twitter
- [X] User is taken back to home timeline with **new tweet visible** in timeline
- [X] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
- [X] User can **see a counter with total number of characters left for tweet** on compose tweet page
- [X] User can click links in tweets launch the web browser 
- [X] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
  - [x] User is displayed the username, name, and body for each tweet
  - [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/dkimjpg/SimpleTweet/blob/master/walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
<img src='https://github.com/dkimjpg/SimpleTweet/blob/master/walkthrough%20part%202.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

- startActivityForResult is deprecated, but the video walkthroughs used it because they were filmed before its deprecation. It would be best to update the video walkthroughs.
- Migrating the API from v1 to v1.1 was the main issue I encountered while building the app, but I managed to get that issue resolved by changing the URL from api.twitter.com/1/1 to api.twitter.com/1.1


## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2022] [David Kim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
