# mobile-view
android studio
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content" >


        <ImageView
            android:id="@+id/profile"
            android:layout_width="180dp"
            android:layout_height="180dp"
            android:layout_gravity="center"
            android:layout_marginTop="5dp"
            android:src="@drawable/desk" />
        <TextView
            android:id="@+id/titleText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_toRightOf="@+id/profile"
            android:text="sireesha"
            android:layout_marginBottom="10sp"
            android:textColor= "#03A9F4"
            android:layout_gravity="center"
            android:layout_marginTop="10dp"
            android:textSize="30sp"
            />

        <TextView
            android:id="@+id/mailText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_toRightOf="@+id/profile"
            android:layout_below="@+id/titleText"
            android:layout_gravity="center"
            android:text="sireesha@gmail.com"
            android:layout_marginBottom="10sp"
            android:layout_marginTop="10sp"
            android:textColor="#222222"
            android:textSize="24sp" />
        <TextView
            android:id="@+id/numberText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_toRightOf="@+id/profile"
            android:layout_below="@+id/mailText"
            android:layout_gravity="center"
            android:text="1234567890"
            android:textColor="#222222"
            android:textSize="25sp" />


    </RelativeLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="center">
        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="class"
            android:textColor= "#222222"
            android:layout_gravity="center"
            android:textSize="25sp"
            android:layout_marginTop="20sp"
            android:layout_marginRight="10"
            />

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:text="course"
            android:textColor="#222222"
            android:textSize="25sp"
            android:layout_marginTop="20sp"
            android:layout_marginRight="10"
            />
        <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:text="rollno"
        android:textColor="#222222"
        android:textSize="25sp"
            android:layout_marginTop="20sp"
            android:layout_marginRight="10"
        />

    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <ImageButton
        android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:layout_marginTop="20sp"
            android:background="@drawable/twitter"
            android:layout_marginRight="4sp">

        </ImageButton>
        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:layout_marginTop="20sp"
            android:background="@drawable/instagram"
            android:layout_marginRight="4sp">

        </ImageButton>
        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:layout_marginTop="20sp"
            android:background="@drawable/fb"
            android:layout_marginRight="4sp">

        </ImageButton>
        <ImageButton
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:layout_weight="1dp"
            android:layout_marginTop="20sp"
            android:background="@drawable/linkdin">

        </ImageButton>


    </LinearLayout>



