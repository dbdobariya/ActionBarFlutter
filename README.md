# ActionBarFlutter
You can use the actions-Property from AppBar to put in some options in your toolbar. Here is an example

As you know that every component in flutter is a widget so Appbar is also a widget that contains the toolbar in flutter application. In Android we use different toolbar like android default toolbar, material toolbar and many more but in flutter there is a widget appbar that auto fixed toolbar at the top of the screen.
In Appbar we create different toolbar widgets like menu button, actions, icon buttons and many more. So, In this article we’ll covered some basic functionality of Appbar.

# 1) Play with back button.
When we created app bar, It shows back button by default enable Like this.

AppBar(
  title: Text("Hello Appbar"),
)

If you want to remove this then add this property in your AppBar widget

automaticallyImplyLeading: false

# 2) Create menu button.
Flutter allow you to create menu or leading button in Appbar. Usually we create menu button manually in android but in flutter we create menu or leading button using a single Appbar properties. Just add below code in your Appbar widget to create customize leading button. It is located on the left side of the Appbar.

AppBar(
  title: Text("Hello Appbar"),
  leading: Icon(
    Icons.menu,
  ),
);



