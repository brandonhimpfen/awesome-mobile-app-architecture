# Awesome Mobile App Architecture [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of architectural patterns, frameworks, tools, and resources for designing scalable, maintainable, and testable mobile applications across iOS, Android, and cross-platform environments.

## Contents

- [Core Architectural Patterns](#core-architectural-patterns)
- [Modern Mobile Architectures](#modern-mobile-architectures)
- [State Management](#state-management)
- [Modularization & Scalability](#modularization--scalability)
- [Data Layer & Domain Design](#data-layer--domain-design)
- [Navigation & Flow](#navigation--flow)
- [Dependency Injection](#dependency-injection)
- [Offline-First & Sync](#offline-first--sync)
- [Testing Architecture](#testing-architecture)
- [Reference Implementations](#reference-implementations)
- [Learning & Resources](#learning--resources)

## Core Architectural Patterns

Foundational patterns used in mobile application design.

- MVC (Model-View-Controller) — Traditional pattern separating UI, logic, and data.
- MVP (Model-View-Presenter) — Separation of concerns with presenter handling logic.
- MVVM (Model-View-ViewModel) — Common pattern for binding UI to state.
- MVI (Model-View-Intent) — Unidirectional data flow architecture.
- Clean Architecture — Layered architecture separating domain, data, and presentation.

## Modern Mobile Architectures

Framework-driven and ecosystem-specific architectural approaches.

- [Android Architecture Components](https://developer.android.com/topic/architecture) — Lifecycle-aware components for Android apps.
- [Jetpack Compose Architecture](https://developer.android.com/jetpack/compose/architecture) — Recommended architecture for Compose apps.
- [SwiftUI Architecture](https://developer.apple.com/documentation/swiftui/) — Declarative UI with state-driven design.
- [The Composable Architecture (TCA)](https://github.com/pointfreeco/swift-composable-architecture) — Predictable state management and architecture for Swift apps.
- [Redux Architecture](https://redux.js.org/) — Unidirectional data flow used in cross-platform apps.

## State Management

Patterns and libraries for managing application state.

- State containers — Centralized state management systems.
- Observable patterns — Reactive updates to UI based on state changes.
- Redux — Predictable state container pattern.
- Bloc (Flutter) — Stream-based state management.
- MobX — Reactive state management library.

## Modularization & Scalability

Strategies for structuring large and scalable mobile codebases.

- Feature-based modularization — Splitting code by features or domains.
- Layered modules — Separation of UI, domain, and data layers.
- Dynamic feature modules — On-demand feature loading (Android).
- Micro-app architecture — Independent modules combined into a single app.
- Code sharing strategies — Shared logic across platforms.

## Data Layer & Domain Design

Designing robust data handling and domain logic.

- Repository pattern — Abstraction layer for data sources.
- Use cases / interactors — Encapsulating business logic.
- Domain-driven design (DDD) — Modeling domain logic explicitly.
- Data mapping — Transforming API models to domain models.
- Caching strategies — Managing local and remote data consistency.

## Navigation & Flow

Managing screen transitions and application flow.

- Navigation components — Structured navigation systems.
- Coordinator pattern (iOS) — Managing navigation outside view controllers.
- Navigation graphs (Android) — Declarative navigation structure.
- Deep linking — Handling external entry points into the app.
- State-driven navigation — UI flow based on application state.

## Dependency Injection

Managing dependencies and improving testability.

- [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) — Dependency injection for Android.
- [Dagger](https://dagger.dev/) — Compile-time dependency injection framework.
- [Koin](https://insert-koin.io/) — Lightweight dependency injection for Kotlin.
- [Swinject](https://github.com/Swinject/Swinject) — Dependency injection framework for Swift.
- Service locators — Alternative pattern for managing dependencies.

## Offline-First & Sync

Designing apps that work reliably with intermittent connectivity.

- Offline-first architecture — Prioritizing local data before remote.
- Sync strategies — Conflict resolution and data synchronization.
- Event sourcing — Tracking changes as events.
- Background processing — Handling updates and sync in the background.
- Queue-based updates — Managing network requests and retries.

## Testing Architecture

Structuring applications for effective testing.

- Testable architecture — Separation of concerns enabling unit testing.
- Dependency injection — Enabling mock dependencies.
- Unit testing — Testing business logic in isolation.
- Integration testing — Testing interactions between layers.
- UI testing — Validating user interface behavior.

## Reference Implementations

Example projects and repositories demonstrating best practices.

- [Android Now in Android](https://github.com/android/nowinandroid) — Modern Android app architecture by Google.
- [ios-clean-architecture](https://github.com/kudoleh/iOS-Clean-Architecture-MVVM) — Example of Clean Architecture with MVVM.
- [Flutter Architecture Samples](https://github.com/brianegan/flutter_architecture_samples) — Comparison of architecture patterns in Flutter.
- [TCA Examples](https://github.com/pointfreeco/swift-composable-architecture/tree/main/Examples) — Sample implementations using TCA.

## Learning & Resources

Educational materials and references for mobile architecture.

- [Android Guide to App Architecture](https://developer.android.com/topic/architecture) — Official Android architecture guidance.
- [Apple Developer Documentation](https://developer.apple.com/documentation/) — Documentation for iOS architecture patterns.
- [Clean Architecture by Robert C. Martin](https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/) — Foundational book on software architecture.
- [Refactoring Guru](https://refactoring.guru/) — Design patterns and architecture explanations.
- [Point-Free](https://www.pointfree.co/) — Advanced Swift and architecture concepts.

## Related Awesome Lists

- [Awesome Mobile Development](https://github.com/brandonhimpfen/awesome-mobile-development) — Tools and frameworks for mobile apps.
- [Awesome iOS Development](https://github.com/brandonhimpfen/awesome-ios-development) — iOS tools and resources.
- [Awesome Android Development](https://github.com/brandonhimpfen/awesome-android-development) — Android tools and resources.
- [Awesome Software Architecture](https://github.com/brandonhimpfen/awesome-software-architecture) — General architecture patterns and tools.
  
## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
You can tune link checking behavior in `lychee.toml`.

Automated checks: link checking (PR + weekly), duplicate URL detection, and a lightweight Awesome List lint.
