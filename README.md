<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto">
    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"

    <ImageView
        android:id="@+id/watch"
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:src="@drawable/watch2"
        tools:layout_editor_absoluteX="211dp"
        tools:layout_editor_absoluteY="106dp">

    </ImageView>

    <TextView
        android:id="@+id/clock"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="watch"
        android:textColor="@color/black"
        android:textSize="30dp"
        tools:layout_editor_absoluteX="92dp"
        tools:layout_editor_absoluteY="123dp">

    </TextView>

    <TextView
        android:id="@+id/company"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_torightOf="@+id/clock"
        android:text="titan"
        android:textColor="@color/black"
        android:textSize="25dp"
        tools:layout_editor_absoluteX="107dp"
        tools:layout_editor_absoluteY="172dp">

    </TextView>


</androidx.constraintlayout.widget.ConstraintLayout>
