# Replica-of-Zomato-splashscreen-signuppage

Created an app that shows SplashScreen of (Zomato App) and opens a signup page.

Learning : How to Display a SplashScreen on any app.
           Improved UI AND UX design.
           
learned how to use drawables
code:
 <com.google.android.material.textfield.TextInputLayout
        android:layout_width="match_parent"
        android:layout_height="60dp"
        app:startIconDrawable="@drawable/baseline_person_outline_24"
        app:helperText="Required"
        app:helperTextTextColor="@color/white"
        app:endIconMode="password_toggle"
        android:layout_margin="15dp">

        <com.google.android.material.textfield.TextInputEditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Password"
            android:textStyle="bold"
            android:textColor="@color/white"
            android:background="@drawable/greyback"
            android:fontFamily="monospace"

            />
    </com.google.android.material.textfield.TextInputLayout>
