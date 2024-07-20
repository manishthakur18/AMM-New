### Instruction

Replace the API Key field with your own key, for key visit [newsapi.org](https://themoviedb.org) and create your id.

```
  |-- lib
  |  |-- global
  |      |-- global.dart

```

```dart
    final String apikey = "YOUR_KEY";
```

## Features

- Dark Mode
- Multi Language Support [ English, हिंदी, मराठी, ಕನ್ನಡ ]
- Share News Card As Image
- Offline Read
- Watermark on shared news card
- Webview

### ScreenShots

|                                                    Dscover                                                     |                                                    Feed                                                    |                                                    Settings                                                    |                                              Language Support                                              |
| :------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/discover.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/feed.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/settings.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/language.png?raw=true)|

|                                                    Search                                                     |                                                    Dark Mode                                                    |                                                    Dark Mode                                                    |                                              Watermark                                              |
| :------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/search.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/darkmode.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/darkmode1.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/watermark.png?raw=true) |

|                                                    Bookmark                                                     |                                                    Loading                                                    |                                                    Web Screen                                                    |                                              Share                                              |
| :------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/bookmarks.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/loading.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/web.png?raw=true) | ![](https://github.com/imSanjaySoni/Inshorts-Clone-The-News-App/blob/master/screenshots/share.png?raw=true) |


## Packages Used

- flutter_bloc & Dio : for http Request Handling.
- Provider : for State Management.
- Hive : for Local Strorage Management.
- esys_flutter_share : for Sharing News card.
- webview_flutter : web view inside the app.
- auto_route : Page Routing.
- photo_view : gives extra features like image scaling.
