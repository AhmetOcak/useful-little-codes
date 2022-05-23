# useful-little-codes
code pieces that may be useful to you 

işinize yarayabilecek kod parçaları 

<br/>

Date -> 2021-12-04
```dart
  String todaysDate() {
    return DateTime.now().toString().substring(0, 10);
  }
```
<br/>
<br/>

Time -> 11:19:58
```dart
  String todaysTime() {
    return DateTime.now().toString().substring(11, 19);
  }
```
<br/>
<br/>

PM - AM
```dart
  String checkPmOrAm(int hour) {
    if (hour >= 12) {
      return 'PM';
    } else {
      return 'AM';
    }
  }
```
<br/>
<br/>

Time Stamp -> readTimestamp(1638766677) => 07:57
```dart
  String readTimestamp(int timestamp) {
    var date = DateTime.fromMillisecondsSinceEpoch(timestamp * 1000);

    return date.toString().substring(11, 16);
  }
```
<br/>
<br/>

Kotlin -> overlapping status bar problem fix
```kotlin
android:fitsSystemWindows="true"
```

<br/>
<br/>

Kotlin -> keyboard problem fix
```kotlin
android:windowSoftInputMode="adjustResize"
```

<br/>
<br/>

Kotlin -> TextInputLayout border color
```Kotlin
<color name="mtrl_textinput_default_box_stroke_color">Your Color</color>
```
