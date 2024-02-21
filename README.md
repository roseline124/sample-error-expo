# expo error sample

- run `npx expo prebuild`
- Then you encounter a problem.

```
[!] Invalid `Podfile` file: cannot load such file -- {project_path}/node_modules/@react-native-community/cli-platform-ios/native_modules.rb

#  from {project_path}/ios/Podfile:2
#  -------------------------------------------
#  require File.join(File.dirname(`node --print "require.resolve('expo/package.json')"`), "scripts/autolinking")
>  require File.join(File.dirname(`node --print "require.resolve('react-native/package.json')"`), "scripts/react_native_pods")
#
#  -------------------------------------------
```
