# JDK
https://www.oracle.com/technetwork/java/javase/downloads/index.html

# 앱 생성
```
$ react-native init admob
```

# babel install
```
$ npm add @babel/runtime
```

# react-native-admob
https://www.npmjs.com/package/react-native-admob

## install
```
$ npm install react-native-admob@next -S
$ react-native link
```

# CocoaPods
https://guides.cocoapods.org/using/getting-started

## install
```
$ sudo gem install cocoapods
```

## profile
```
$ vi ~/.profile

export GEM_HOME=$HOME/.gem
export PATH=$GEM_HOME/bin:$PATH
```

# Import the Mobile Ads SDK
https://developers.google.com/admob/ios/quick-start#import_the_mobile_ads_sdk

```
$ cd ios && pod init
$ vi Podfile
```

## Podfile example
```
target 'admob' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  # Pods for admob
  pod 'Google-Mobile-Ads-SDK'

  target 'admob-tvOSTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'admobTests' do
    inherit! :search_paths
    # Pods for testing
  end

end
```

## Pod install
```
$ pod install --repo-update
```

# Usage
## iOS
```
$ yarn start
$ react-native run-ios
```

## AOS
```
$ yarn start
$ android adv
$ react-native run-android
```
