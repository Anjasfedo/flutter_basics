# flutter_basics

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

flutter is widget on widget

MaterialWidget can contain Scaffold that a widget use as skeleton of app, it has white black widget.
those two is skeleton of app


flutter work with widget, its widget over widget over widget,

every widget has arguments, and if we used arguments we need to pass another widget as arguments.

widget use pascal case
argument contain widget with colon (:)

use constant with const on every arguments
used only for first child widget from the parent widget, to avoid use 2 times const, because we only need to use it once for every arguments

use comma (,) on every end of bracket (`)`)

if we change something on MyApp, we need to do restart, not only hot reload to get the changes

stateless widget mean the screen will not change
so we need to statefull widget

and use setState to change variable

use currentIndex arguments to show the active bottomNavigationBar

int use lowercase, not as String

to create vertical widgets, we can use Column widget with children of list
maximum size of column is follow its childs. to make the column take all screen we can use SizedBox widget to wrap it, and use width arguments
to get maximum with as width arguments, we use double.infinity, that will surely take max width as we have

if we use row/columnt, it gonna fill the width/height on it

