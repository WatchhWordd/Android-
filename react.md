* Props属性
* State
* 集成native app
1. mkdir android/app/src/main/assets  
2. 生成index.android.bundle   
   react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res  
3. rect-native run-android
