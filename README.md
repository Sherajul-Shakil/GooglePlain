# google_plain

A completely Responsive Google Clone- Works on Android, iOS & Web! 

## Features
- Responsive Google UI
- Fetches Results from Google's Custom Search API
- Pagination

## Installation
After cloning this repository, migrate to ```google-plain``` folder. Then, follow the following steps:
- Enable Google Custom Search and get API Key(Google Console)
- Get the Context Key
- Replace the keys in ```config/api_keys.dart```
Then run the following commands to run your app:
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator)
  flutter run
  flutter run -d chrome --web-renderer html (to see the best output)
```
    
## Important Links
~~~
Google Developer Console - https://console.cloud.google.com/apis/dashboard?project=durable-boulder-343013
Google Custom Search API - https://developers.google.com/custom-search/v1/overview
Context Key - https://cse.google.com/cse/create/new?pli=1&authuser=1
~~~