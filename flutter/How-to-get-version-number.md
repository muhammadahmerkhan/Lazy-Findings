# Displaying Version and Build Number in your app

Sometimes we need version and build number of the app in our mobile drawer or side menu for review in Google play store or Apple app store, but How can we acheieve that:
Here's a very minimal way to do so :
You can use package_info_plus: ^8.0.0 from pub dev and use it in your Function as :
```
PackageInfo _packageInfo = await PackageInfo.fromPlatform();
```
And create a function in your app like :

![Screenshot 2024-06-03 110940](https://github.com/muhammadahmerkhan/Lazy-Findings/assets/169340386/9455eb97-ff07-4b7f-ad59-2605de2d5e6d)


