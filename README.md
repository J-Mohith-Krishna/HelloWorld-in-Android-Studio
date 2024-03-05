# HelloWorld-in-Android-Studio
## Description-
  This code creates a simple Android app with a TextView displaying "Hello, World!" and a Button. When the button is clicked, the text in the TextView changes to "Hello, Kotlin!".
## Explanation-
  -Package Imports: The import statements at the beginning of the code import necessary packages from the Android SDK.
  
  -MainActivity Class: MainActivity is a subclass of AppCompatActivity, which is a base class for activities that use the support library action bar features. In Android, an activity is a single, focused thing that the user can do.
  
  -Override onCreate() Function: The onCreate() function is an override function provided by the AppCompatActivity class. It is called when the activity is starting. Here, we override it to perform our initialization tasks.
  
  -super.onCreate(savedInstanceState): This line calls the superclass implementation of the onCreate() method. It is necessary to include this call to ensure that the activity lifecycle is properly managed by the Android system.
  
  -setContentView(): This method sets the layout for the activity from the XML layout resource file named activity_main. In Android, UI layouts are defined using XML files.
  
  -findViewById(): This method finds the TextView with the id "textView" defined in the layout file. It returns a reference to the TextView object.
  
  -textView.text = "Hello, World!": This line sets the text of the TextView to "Hello, World!" using Kotlin's property syntax. In Kotlin, TextView's text property can be directly assigned a value.
