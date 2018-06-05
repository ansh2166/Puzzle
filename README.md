### Puzzle V 1.0.0

This library allow you to create & play puzzles in android application.

### Screenshot

![Image](https://image.ibb.co/e64Z3T/Webp_net_resizeimage.png)

### Integration

Step 1.Add it in your root build.gradle at the end of repositories:
```java
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```
Step 2. Add the dependency
```java
dependencies {
  implementation 'com.github.rahulpareta:Puzzle:1.0.0'
}
```
### Usage
1. Add PuzzleView in your layout
```xml
<com.rp.puzzle.view.PuzzleView
    app:pv_borderSize="2"
    app:pv_borderColor="@color/colorPrimaryDark"
    android:id="@+id/puzzle_view"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_margin="10dp"/>
```
