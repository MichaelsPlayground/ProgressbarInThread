# Progressbar in Thread

Source: https://o7planning.org/12745/android-progressbar

In this example, I'm going to create 2 horizontal ProgressBar(s).
The first ProgressBar is put in Determinate mode. It displays a process which the percentage of complete work is indicated.
The second ProgressBar is put in Indeterminate mode. It will show a progress for which you cannot know the percentage of completed work.

In this example, I'm using Thread to do the work, downloading a file, or updating the records in the database, for example. 
Then I use Handler to update information in the interface.

**Spinning Wheel ProgressBar Styles Example**

Below are the Spinning Wheel ProgressBar illustrations with different Style(s).

style="@android:style/Widget.DeviceDefault.Light.ProgressBar.Small"  

style="@android:style/Widget.DeviceDefault.Light.ProgressBar.Small.Inverse"

style="@android:style/Widget.DeviceDefault.Light.ProgressBar.Large"

style="@android:style/Widget.DeviceDefault.Light.ProgressBar.Large.Inverse"

style="@android:style/Widget.ProgressBar.Large"

style="@android:style/Widget.ProgressBar.Large.Inverse"

There are a few Style(s) with different names but you will find it difficult to see the difference in terms of interface. 

Such as: Widget.ProgressBar.Large & Widget.ProgressBar.Large.Inverse.

Widget.ProgressBar.Large: Intended to be used to place on a dark background.

Widget.ProgressBar.Large.Inverse: Intended to be used to place on a light background.

Note that you will not spot the difference when the application is running on Android Emulator. 

However, you can perceive the difference only when the application is running on the well-displayed devices.

**Horizontal ProgressBar Styles**

style="?android:attr/progressBarStyleHorizontal" (Default of Horizontal ProgressBar)

style="@android:style/Widget.DeviceDefault.Light.ProgressBar.Horizontal"

style="@android:style/Widget.DeviceDefault.ProgressBar.Horizontal"

style="@android:style/Widget.Holo.Light.ProgressBar.Horizontal"  

style="@android:style/Widget.Material.Light.ProgressBar.Horizontal"

style="@android:style/Widget.Holo.ProgressBar.Horizontal"  

style="@android:style/Widget.Material.Light.ProgressBar.Horizontal"  

style="@android:style/Widget.ProgressBar.Horizontal"

