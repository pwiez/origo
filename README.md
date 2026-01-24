# Origo

An iOS application built with SwiftUI designed for collecting and managing records (fichas) related to professions. The app allows users to create detailed entries including artifacts, photos, audio recordings, and geolocation data, with support for filtering and exporting records.

## Features

- **Record Management**: Create and manage profession-related records with unique artifacts.
- **Media Integration**: Capture and attach photos and audio recordings to records.
- **Geolocation**: Use Google Maps integration to associate locations with records.
- **Filtering System**: Filter records by export status, presence of images/audio, and recency.
- **Onboarding**: Guided onboarding experience for new users.
- **Data Persistence**: Utilizes SwiftData for local data storage.
- **Export Functionality**: Mark and export records as needed.

## Tech Stack

- **SwiftUI**: Modern UI framework for building the interface.
- **SwiftData**: For data modeling and persistence.
- **Google Maps SDK**: For geolocation and mapping features.
- **MijickCamera**: For camera functionality.
- **Xcode**: Development environment for iOS.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/pwiez/professions-challenge.git
   ```

2. Open the project in Xcode:
   ```
   open professions-challenge.xcodeproj
   ```

3. Set up Google Maps API Key:
   - Obtain a Google Maps API key from the [Google Cloud Console](https://console.cloud.google.com/).
   - Add the API key to the `Info.plist` file or set the environment variable `GOOGLE_MAPS_API_KEY`.

4. Build and run the app on a simulator or device.

## Usage

- Launch the app and complete the onboarding process.
- Tap "Cadastrar ficha" to create a new record.
- Add details, photos, audio, and location information.
- Use filters to organize and view your records.
- Export records as needed.

## Models

The app uses several data models:
- `RecordModel`: Main record entity with name, creation date, artifact, media, and location.
- `ArtifactModel`: Contains location, artifact data, and details.
- `AudioModel`: For audio recordings.
- `CapturedImageModel`: For photos.
- `MapMarkerModel`: For geolocation markers.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.
