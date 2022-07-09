# WzSayEz

## About the Project

The WzSayEz app aims to provide Singaporeans greater flexibility in planning their destinations, by providing live parking availability data and routing from current location to selected carpark.

## Inspiration
Many a time, many Singaporeans, just like us, do feel the urge to recycle and help the environment out. With so much help given to conventional recycling ways, recycling of **electronics** are often left out, or unknown to many.

## What it does
App to allow users to recycle any items, with a map of **all** e-recycling bins integrated into it. Users are able to send in their photos/pictures to be stored in our database, and be awarded points when they are approved by the system administrators.

## How we built it
Using Flutter, which is a cross-platform app development tool, we built the app with dart as the main programming language used.

## Challenges we ran into
Incomplete/ missing data from API Requests.
Problems with CSV format.
Reducing the loading time for markers to be drawn on the map.

## Accomplishments that we're proud of
Reducing the loading time for markers to be shown on the map, from over a minute to instantaneously, but precomputing the data once beforehand.
## What we learned

Reducing lag time by precomputing certain values once at the start.


## Getting Started (Setup)

### Prerequisites

To test the app, you will need to have the Flutter SDK, an Android Virtual Device (AVD) and Android Studio installed on your machine.

Follow the instructions at https://docs.flutter.dev/get-started/install, https://developer.android.com/studio and https://developer.android.com/studio/run/managing-avds to get it set up.

### Installation

1. Clone the repo `git clone https://git@github.com:maxangyuejun/LifeHack22.git`

2. In your chosen IDE, get all the dependencies using `flutter pub get` in the terminal in your IDE

3. Start your preferred AVD on your machine through Android Emulator. Set the current location on the AVD to somewhere within Singapore.

4. Run the app using `flutter run` in the terminal in your IDE
