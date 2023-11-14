# AppDistribution

App Distribution to Firebase App Distribution

1)Please note your project is need signed.Means if you create release apk then that apk is signed apk
2)In build.gradle->
	firebaseAppDistribution {
                appId = "1:337904067089:android:571e21533be9cb685247b0"
                artifactType="APK"
                releaseNotesFile="releasenotes.txt"
                testers="vishnu@adyamconsultant.com"
            }

3)When your App Id is reciceve? ->
	when you connect your android project to firebase project then go to firebase console and go to your project setting that page you recicve the APP ID 

4)Command to execute to upload the APK To Firebase App Distribution
	 ./gradlew clean
	 ./gradlew assembleRelease appDistributionUploadRelease

  5)Install Firebase CLI
  https://youtu.be/gptBM2CPMQs?si=gde3Wq8UL8k2wkuf
