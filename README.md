# MobileApp<?xml version="1.0" encoding="utf-8"?>

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity3">

    <Button
        android:id="@+id/button_main3"
        android:layout_width="72dp"
        android:layout_height="53dp"
        android:layout_marginRight="16dp"
        android:layout_marginBottom="656dp"
        android:backgroundTint="#B72B63"
        android:text="skip"
        app:cornerRadius="120dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toRightOf="parent" />

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="439dp"
        android:layout_height="412dp"
        app:srcCompat="@drawable/image_6"
        tools:layout_editor_absoluteX="-14dp"
        tools:layout_editor_absoluteY="22dp"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/text_header2"
        android:layout_width="276dp"
        android:layout_height="136dp"
        android:layout_marginStart="36dp"
        android:layout_marginTop="412dp"
        android:text="Quick, Fresh &amp; Delicious Bakery"
        android:textAppearance="@style/TextAppearance.AppCompat.Medium"
        android:textColor="@color/black"
        android:textSize="85px"
        android:textStyle="bold"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/text_header"
        android:layout_width="230dp"
        android:layout_height="59dp"
        android:layout_marginStart="36dp"
        android:layout_marginTop="504dp"
        android:text="Made by hand from scratch with love"
        android:textAppearance="@style/TextAppearance.AppCompat.Medium"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button_main2"
        android:layout_width="121dp"
        android:layout_height="55dp"
        android:layout_marginRight="240dp"
        android:layout_marginBottom="60dp"
        android:backgroundTint="#B72B63"
        android:text="Sign up"
        app:cornerRadius="@android:dimen/thumbnail_width"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toRightOf="parent" />

    <Button
        android:id="@+id/button_main7"
        android:layout_width="121dp"
        android:layout_height="55dp"
        android:layout_marginRight="56dp"
        android:layout_marginBottom="60dp"
        android:backgroundTint="#B72B63"
        android:text="Sign up"
        app:cornerRadius="@android:dimen/thumbnail_width"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toRightOf="parent" />


</androidx.constraintlayout.widget.ConstraintLayout>
