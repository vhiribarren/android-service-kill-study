# Tutorial - Effect on killing a service in Android

This is the code base used in the blog post [Effect of swiping an Android app in recent app list](http://workshop.alea.net/post/2016/06/android-service-kill/).

It contains several Android sub app:

- **app-notsticky**: service launched in `START_NOT_STICKY` mode
- **app-sticky**: service launched in `START_STICKY` mode
- **app-foreground**: service launched with `startForeground`
