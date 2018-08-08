# StepViewLibrary

This library allows to use Material steppers inside Android applications.

# Paste this in build.gradle:  
   * compile 'com.paxcel.stepview:stepview:1.0.5'
   
   ![step view1](https://user-images.githubusercontent.com/15032532/43827485-8cdeabf6-9b17-11e8-998f-e992492c2764.png)
![step view2](https://user-images.githubusercontent.com/15032532/43827489-8e17f3d8-9b17-11e8-9eef-3af5ea1734fd.png)
   
   
      <com.paxcel.stepview.StepView
            android:id="@+id/stepperView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            app:noOfSteps="6"
            app:stepTextSize="12"
            app:separatorWidth="60"
            app:separatorHeight="3"
            app:separatorColor="@color/colorPrimary"
            app:selectedTextColor="@android:color/white"
            app:unSelectedTextColor="@color/colorPrimary"
            app:selectedBackground="@drawable/bg_circle_blue_solid"
            app:unSelectedBackground="@drawable/bg_circle_blue"
            />
            
