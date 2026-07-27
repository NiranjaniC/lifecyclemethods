# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:

```
Program to print the text “Hello World”.
Developed by: Niranjani.C
Registeration Number : 212223220069

package com.example.test3;
import android.os.Bundle;
import android.widget.Toast;
import androidx.appcompat.app.AppCompatActivity;
public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(),"onCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart()
    {but cant able to get outut or instp and on destroy in pixel 9 devvice emuator guide me how to do

        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(),"onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart()
    {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(),"onRestart Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume()
    {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(),"onResume Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause()
    {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(),"onPause Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStop()
    {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(),"onStop Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy()
    {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(),"onDestroy Called", Toast.LENGTH_LONG);
        toast.show();
    }

}
```

## OUTPUT

<img width="1917" height="1020" alt="Screenshot 2026-07-22 195738" src="https://github.com/user-attachments/assets/0c7f8121-c974-43d0-b6e1-7dff4e9c75ad" />
<img width="1917" height="1022" alt="Screenshot 2026-07-22 195745" src="https://github.com/user-attachments/assets/49615c52-e0d5-40a9-a9ce-36f396cd7834" />
<img width="1913" height="1020" alt="Screenshot 2026-07-22 194938" src="https://github.com/user-attachments/assets/34abd2ea-2738-4ec5-811b-5feb26be8eee" />
<img width="1917" height="1007" alt="Screenshot 2026-07-27 134443" src="https://github.com/user-attachments/assets/48e29164-142e-44bd-8ae3-b9a473093036" />
<img width="1917" height="1016" alt="Screenshot 2026-07-27 131347" src="https://github.com/user-attachments/assets/19656d2a-69f1-46b9-8a5b-1456f2a05a49" />




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
