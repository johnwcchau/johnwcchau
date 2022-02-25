john_at_harmon.hk

### 220225 **Fck react-native**

_Learn once, write anywhere_ ???

Really?

Today spending hours on installing and configuring react-native to run a simple project, so many errors

kinder know why, react-native is a framework building on some other framework, and without stable apis between all of them errors can be expected, and that's why I hate using something like this, tried a year ago and gave up because of errors.

#### What errors?
following tutorials and RN told me to use expo, well, set it up, got versioning problem with auth0, expo using 0.64.3 while auth0 >0.65, oK...

try to use my install of AndroidStudio, gradle, jdk, ... spending an hour on those

how about Windows Metro? Was using VS2017, too old? go VS2022, probably too new as giving error around XAML compiling, so gave up

No worry go back to android, compile and the template worked! hurray, now time for auth0

copy and paste and test, well it works! now customization time...

Oops:
```
Error: ENOENT: no such file or directory, open 'X:\data\codes\Auth0\http:\localhost:8081\index.bundle?platform=android&dev=true&minify=false&app=com.auth0&modulesOnly=false&runModule=true'
```
Google for that, no much result, tried all, clear cache, npm install, restart machine... ok enough, fck u, let me create a new project.
