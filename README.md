# scrumlab_flutter_tindercard

[![Pub](https://img.shields.io/pub/v/scrumlab_flutter_tindercard.svg?color=%233CB371)](https://pub.dartlang.org/packages/scrumlab_flutter_tindercard)
[![Closed](https://img.shields.io/github/issues-closed-raw/scrum-lab/scrumlab_flutter_tindercard.svg?color=%23FF69B4)](https://github.com/scrum-lab/scrumlab_flutter_tindercard/issues?q=is%3Aissue+is%3Aclosed)

Tinder/TanTan Card Widget.

## Screenshots

![screenshot](./assets/example_tindercard.gif)

## Getting Started

1. Depend on it by adding this to your pubspec.yaml file: ```scrumlab_flutter_tindercard: ^x.x.x```

2. Import it: ```import 'package:scrumlab_flutter_tindercard.dart'```

3. Add TinderSwapCard in your widget layout and write the single card layout builder you need, then you get a Tinder(探探) like swap card widget!

4. Use `CardSwipeCompleteCallback` for the swiped orientation and index!

5. Use `CardController` to trigger swap from outside. Init a CardController as param for widget, and invoke method `triggerLeft/Right` of your `CardController` to trigger swipe!

6. Use `CardDragUpdateCallback` to get swiping card's detail.

## Example
[See Here](./example/example/lib)

## Async Example
[See Here](./example/async_data/lib)
