# cupertino

A new Flutter project that have the ios look and feel.

Note:

* It uses cupertino layout instead of the material layout
* This shows using abstract class to defines the styles for reuse.
* This is the MVC model app.
* app_state_model.dart handles the business logic, and use ChangeNotifierProvider see  https://pub.dev/documentation/provider/latest/provider/ChangeNotifierProvider-class.html
   It extends from foundation.ChangeNotifier
* products_repository.dart is a temporary listing.  A real application would use a database to store the info.
* main.dart calls builder: (context) => AppStateModel()..loadProducts(),   instead of model: model, changed code.
* Product_List_Tab uses CustomScrollsView, and sets the length value to semanticChildCount property
* SilverSafeArea.  https://api.flutter.dev/flutter/widgets/SliverSafeArea-class.html
* CupertinoTabScaffold defines the layout in CupertinoStoreHomePage
* images comes from the package shrine_images
* shopping_cart_tab.dart looks different from the sample. What is scoped_model.dart?   https://pub.dev/packages/scoped_model


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
