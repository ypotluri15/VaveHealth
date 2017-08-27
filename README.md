
1.Clone ionic  git project 
	https://github.com/ypotluri15/VaveHealth.git
2.Run the following commands :
	$ ionic cordova platform add ios
	$ ionic cordova run ios

2.Open App.xcworkspace (this file is created in the same folder as the commands are run) 
3.App will be launched in xcode. Once the project is indexed , Run 
	Product > Clean

5.Development profile is required to build the App on a real device.
	go to Xcode > accounts > Add Apple account > 
		select personal team > manage certificates > add new 
		> click + > select iOS Development (make sure the certificate is exported and added to Apple account)

4.Product > Build   (Target  Dev enabled Phone)
5.Product > Run

6. Go to Xcode > preferences > locations
	copy the derived data path ( needed for Appium Test cases)


