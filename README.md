# -FLUTTER-useful-little-codes
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
