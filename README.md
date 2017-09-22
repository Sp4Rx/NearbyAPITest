# NearbyAPITest

This is a test project for Google's [Nearby](https://developers.google.com/nearby/messages/android/get-started) API

## Config

Generate your API key from [Google Developers Console](https://console.developers.google.com/flows/enableapi?apiid=copresence&keyType=CLIENT_SIDE_ANDROID&reusekey=true).
Then, configure your manifest with the API Key generated in the previous step:


    manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.google.sample.app" >
    <application ...>
        <meta-data
            android:name="com.google.android.nearby.messages.API_KEY"
            android:value="API_KEY" />
        <activity>
        ...
        </activity>
    </application>
    </manifest>

## Output
Check Log to see published messages from nearby devices , using this app.
