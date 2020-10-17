<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <LinearLayout
        android:background="#FFD740"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:gravity="center"
        android:orientation="vertical">

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="80dp"
            android:layout_marginBottom="20dp"
            android:src="@drawable/pric" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="30dp"
            android:textStyle="bold"
            android:text="Login" />

        <EditText
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:layout_marginBottom="5dp"
            android:hint="Email"
            android:inputType="textEmailAddress"
            android:textColorHint="	#000000"
            android:drawableStart="@drawable/per"/>

        <EditText
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:layout_marginBottom="15dp"
            android:hint="Password"
            android:inputType="textPassword"
            android:textColorHint="	#000000"
            android:drawableStart="@drawable/key"/>

        <Button
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:gravity="center"
            android:text="Masuk"
            android:layout_marginBottom="10dp"/>
        <Button
            android:id="@+id/txtRegistrasi"
            android:layout_width="match_parent"
            android:layout_height="40dp"
            android:text="Registrasi"
            android:textStyle="bold"
            android:gravity="center"/>
    </LinearLayout>

</androidx.constraintlayout.widget.ConstraintLayout>
