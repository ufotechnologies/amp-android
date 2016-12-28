# Amp: A crowdsourcing Android app using libspotify

## Features

* Integration with [libspotify](https://developer.spotify.com/technologies/libspotify/) 12.1.51 (deprecated)
* Stream playback to Chromecast with [libFLAC](https://xiph.org/flac/api/)
* Low-latency playback with [OpenSL ES](https://developer.android.com/ndk/guides/audio/opensl-for-android.html)
* Integration with [Slack RTM API](https://api.slack.com/rtm)
* Integration with [Twitter Streaming API](https://dev.twitter.com/streaming/overview)
* Integration with [Google CSE API](https://developers.google.com/custom-search/json-api/v1/overview) for spelling correction
* Post to an Amp URL
* Create [Spotify tracksets](https://developer.spotify.com/technologies/widgets/spotify-play-button/)

## Remarks

* You need to be a Spotify Premium user
* It will not work on x86 Android since there is no libspotify released for that platform

## Check spelling with Google's Custom Search Engine API

This approach for spelling correction doesn't always return results, however because Google's results are based on popular terms it works well for correcting the spelling of popular music.

Create your [Custom Search Engine](https://www.google.com/cse/) configured to [Search the entire web](https://support.google.com/customsearch/answer/2631040?hl=en) and get your [Search engine ID](https://support.google.com/customsearch/answer/2649143?hl=en). Keys for the API can be obtained from your [Google Developers Console](https://console.developers.google.com/).

## Roadmap

##### v1.1.x:

* Android TV support
* Receiver improvements
* User-interface improvements

##### v1.2.x:

* Spotify-style lockscreen
* Bluetooth album artwork
* Media button events
* User-interface improvements

##### v1.3.x:

* Slack interactive messages

##### v1.4.x:

* Spotify Radio fallback

##### v2.0.x:

* DJ mode
* Advanced playback controls

## Feedback

Please file feedback about missing features or bugs over at our [issue tracker](https://github.com/ufotechnologies/amp-android/issues), making sure you search for existing issues and adding your voice to those rather than duplicating.

## Changelog

* [Releases](https://github.com/ufotechnologies/amp-android/releases)

## References

* Spotify's [PsyOnSpotify](https://github.com/spotify/psyonspotify) hackweek project
* Al Rayhan's [Dark Material UI Design](https://dribbble.com/shots/2355418-Dark-Material-UI-Design)
* Chris Banes' [Cheesesquare](https://github.com/chrisbanes/cheesesquare)
* Gianluca Segato's [Creating a Login Screen Using TextInputLayout](https://code.tutsplus.com/tutorials/creating-a-login-screen-using-textinputlayout--cms-24168)
* Gianluca Segato's [How to Use FontAwesome in an Android App](https://code.tutsplus.com/tutorials/how-to-use-fontawesome-in-an-android-app--cms-24167)
* Ashraff Hathibelagal's [Getting Started With RecyclerView and CardView on Android](https://code.tutsplus.com/tutorials/getting-started-with-recyclerview-and-cardview-on-android--cms-23465)
* Bashar Labadi's [Android RecyclerView - Adding Empty View](http://blabadi.blogspot.ca/2014/12/android-recyclerview-adding-empty-view.html)
* Jakob Ulbrich's [Building an Android Settings Screen](https://medium.com/@JakobUlbrich/building-a-settings-screen-for-android-part-1-5959aa49337c)
* Gil Vegliach's [A library that draws transparent text in a TextView](http://gilvegliach.it/?id=3)
* Michael Evans' [ColorArt: A Library to Do iTunes 11-style Color Matching for Android](http://michaelevans.org/blog/2013/12/12/colorart-a-library-to-do-itunes-11-style-color-matching-for-android/)
* Patrick Schroen's [Android port](https://github.com/pschroen/slack-api-android) of allbegray's Java [slack-api](https://github.com/allbegray/slack-api)
* Code samples for [Android NDK](https://github.com/googlesamples/android-ndk)
* Code samples for [Google Cast v3](https://github.com/googlecast)
* Android Developers [Managing Audio Focus](https://developer.android.com/training/managing-audio/audio-focus.html)
* Android Developers [Keeping the Device Awake](https://developer.android.com/training/scheduling/wakelock.html)

## Links

* [Website](https://ufo.ai/amp/)
* [Privacy policy](https://ufo.ai/amp/privacy/)
* [Open source licenses](https://ufo.ai/amp/licenses/)
