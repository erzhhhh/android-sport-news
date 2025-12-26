# Sport News

Simple sports-news demo app — built mainly for practicing networking, list rendering, and clean architecture basics.

## What it does

* Fetches the latest sports news from a public API
* Displays articles in a scrollable list
* Opens details when you tap an item
* Shows loading/error states gracefully

Great as a small practice project and portfolio example.

## Tech stack

* **Kotlin**
* **Android Jetpack** components
* **RecyclerView**
* **ViewModel + LiveData**
* **Retrofit** for HTTP calls
* **Coroutines** for async work
* **Glide** (if images are present)

## Getting started

1. Clone the repo
2. Open in Android Studio
3. Sync Gradle
4. Run on device/emulator — that’s it 🚀


## Project structure (high level)

```
app/
 ├─ data/        # network & models
 ├─ ui/          # activities / fragments / adapters
 └─ viewmodel/   # presentation logic
```

## Possible improvements

* Add search & filters
* Pagination / infinite scroll
* Dark mode support
* Unit tests for ViewModels & repository
* Pull-to-refresh

## Why this project exists

Short, realistic example of how to fetch data from an API and present it cleanly — without unnecessary complexity.

