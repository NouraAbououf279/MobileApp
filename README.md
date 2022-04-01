# MobileApp
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity3"
    android:background="@drawable/bk">


    <LinearLayout
        android:layout_width="415dp"
        android:layout_height="725dp"
        android:orientation="vertical"
        android:paddingLeft="24dp"
        android:paddingTop="56dp"
        android:paddingRight="24dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        tools:ignore="MissingConstraints">

        <TextView
            android:layout_width="380dp"
            android:layout_height="70dp"
            android:layout_gravity="center_horizontal"
            android:layout_marginLeft="7dp"
            android:layout_marginTop="15dp"
            android:text="Create An Account"
            android:textAppearance="@style/TextAppearance.AppCompat.Body2"
            android:textColor="#FFFFFF"
            android:textSize="38dp"
            android:textStyle="bold"
            android:typeface="serif" />

        <EditText
            android:id="@+id/input_name"
            android:layout_width="157dp"
            android:layout_height="58dp"
            android:layout_marginTop="60dp"
            android:background="#F5F5F5"
            android:hint="Username"
            android:inputType="textEmailAddress"
            android:paddingLeft="10dp"
            android:textSize="15dp" />

        <EditText
            android:id="@+id/input_psw"
            android:layout_width="175dp"
            android:layout_height="56dp"
            android:background="#F5F5F5"
            android:hint="Password"
            android:inputType="textEmailAddress"
            android:paddingLeft="10dp"
            android:textSize="15dp"
            tools:ignore="MissingConstraints"
            tools:layout_editor_absoluteX="187dp"
            tools:layout_editor_absoluteY="217dp"
            android:layout_marginLeft="180dp"
            android:layout_marginTop="-58dp"/>

        <EditText
            android:id="@+id/input_password"
            android:layout_width="355dp"
            android:layout_height="56dp"
            android:layout_marginTop="15dp"
            android:background="#F5F5F5"
            android:hint="Email"
            android:inputType="textPassword"
            android:paddingLeft="20dp"
            android:textSize="15dp"/>

        <EditText
            android:id="@+id/input_address"
            android:layout_width="355dp"
            android:layout_height="56dp"
            android:layout_marginTop="15dp"
            android:background="#F5F5F5"
            android:hint="Address"
            android:inputType="textPassword"
            android:paddingLeft="20dp"
            android:textSize="15dp"/>

        <EditText
            android:id="@+id/input_no"
            android:layout_width="355dp"
            android:layout_height="56dp"
            android:layout_marginTop="15dp"
            android:background="#F5F5F5"
            android:hint="Mobile no."
            android:inputType="textPassword"
            android:paddingLeft="20dp"
            android:textSize="15dp"/>

        <Button
            android:layout_width="217dp"
            android:layout_height="66dp"
            android:layout_marginLeft="72dp"
            android:layout_marginTop="60dp"
            android:text="Sign up"
            android:textAppearance="@style/TextAppearance.AppCompat.Display3"
            android:textSize="25dp"
            app:backgroundTint="#CCAD8A"
            app:cornerRadius="@android:dimen/thumbnail_width"
            app:iconTint="#716D6D" />

        <TextView
            android:id="@+id/psw"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="50dp"
            android:gravity="center"
            android:text="Or sign up with"
            android:textColor="#131313"
            android:textSize="18dip"
            android:textStyle="bold" />

        <ImageView
            android:id="@+id/imageView3"
            android:layout_width="wrap_content"
            android:layout_height="39dp"
            android:paddingLeft="160dp"
            app:srcCompat="@drawable/fb" />

        <ImageView
            android:id="@+id/imageView5"
            android:layout_width="208dp"
            android:layout_height="41dp"
            app:srcCompat="@drawable/gg"
            android:layout_marginTop="-40dp"
            android:paddingLeft="100dp"
            />


    </LinearLayout>

</androidx.constraintlayout.widget.ConstraintLayout>
