<h1 align="center">Scrobblenaut</h1>

<div align="center">
Just a Last.FM API Wrapper for Dart.
A package to interact with the official 

[Last.FM API](https://last.fm/api/).

[![Dart Version](https://img.shields.io/badge/Dart-2.7.2-blue.svg?style=flat-square&logo=dart)](https://dart.dev)
[![Build Status](https://img.shields.io/travis/Nebulino/Scrobblenaut/master?style=flat-square&logo=travis)](https://travis-ci.org/github/Nebulino/Scrobblenaut)
[![Last.FM](https://img.shields.io/badge/API-v.2.0-00aced.svg?style=flat-square&logo=last.fm)](https://www.last.fm/api/)
[![Nebulino](https://img.shields.io/badge/💬%20Telegram-Nebulino-blue.svg?style=flat-square)](https://t.me/Nebulino/)

</div>

## Disclaimer

I'm doing it just for fun, so... use at your own risk.

I hope it will become something great.

^-^
## Usage

First build the .g files for Serializable (if you clone the repo):

```pub run build_runner build```

A simple usage example:

```dart
import 'package:scrobblenaut/scrobblenaut.dart';

// A simple example...
// For more, check the example folder.
void main() async {
  final lastFMAuth = await LastFM.noAuth(apiKey: APIValues.API);
  final scrobblenaut = Scrobblenaut(lastFM: lastFMAuth);
  
  // Start using the Wrapper...
}

```

## Get Scrobblenaut

Add Scrobblenaut dependency on `pubspec.yaml`:

From GitHub:
```yaml
dependencies:
  scrobblenaut:
    git: https://github.com/Nebulino/Scrobblenaut.git
      ref: branch-name
```

From pub.dev:

##### Coming soon... I hope...

## Features and bugs

#### For the documentation:
For now, You have to download the repo and run *dartdoc* on the console,
on the root of the package.

#### WARNING 
Not all methods are available. Check the release page to check which one are.

There's 2 type of usage:
- with authentication;
- without authentication.

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/Nebulino/Scrobblenaut/issues

##### Copyright © 2020 Nebulino
