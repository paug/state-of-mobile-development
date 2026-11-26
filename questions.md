# State of Mobile 2027 — Questionnaire

## About you

*A little context helps make the results more meaningful. No name or email required.*

### 1. Which best describes your primary role?

*Type: Single choice · ID: `role`*

- Mobile developer / engineer
- Full-stack / software developer
- Tech lead / architect
- Engineering manager
- QA / test engineer
- Student / learning
- Designer / product role
- Other

### 2. How long have you been developing mobile applications?

*Type: Single choice · ID: `experience`*

- Less than 1 year
- 1–2 years
- 3–5 years
- 6–10 years
- More than 10 years

### 3. Where are you primarily based?

*Type: Short text · ID: `country`*

**Guidance:** Country only; please do not enter your city or address.

*Free-text prompt:* e.g. France

### 4. How many engineers work on your main mobile product?

*Type: Single choice · ID: `mobile_team_size`*

- Just me
- 2–5
- 6–10
- 11–25
- 26–50
- 51+
- Not applicable

### 5. What industry is your main mobile product in?

*Type: Single choice · ID: `industry`*

- Finance / fintech
- E-commerce / retail
- Media / publishing
- Social / communications
- Health / wellbeing
- Travel / mobility
- Gaming / entertainment
- B2B / enterprise
- Education
- Developer tools
- Other
- Not applicable

## Platforms & frameworks

*Native and cross-platform answers live side by side. Think about your work over the past 12 months.*

### 6. Which platforms have you developed for in the past 12 months?

*Type: Multiple choice · ID: `platforms_used`*

- Android
- iOS / iPadOS
- Mobile web / PWA
- Wear OS
- watchOS
- Android TV / tvOS
- Automotive
- Spatial computing / XR
- Other

### 7. Which approaches have you used in the past 12 months?

*Type: Multiple choice · ID: `approaches_used`*

- Native Android
- Native iOS
- Flutter
- React Native
- Kotlin Multiplatform (shared logic)
- Compose Multiplatform (shared UI)
- Mobile web / PWA
- Ionic / Capacitor
- NativeScript
- .NET MAUI
- Unity / Unreal
- Other

### 8. What is the primary approach for your main mobile project?

*Type: Single choice · ID: `primary_approach`*

- Native Android
- Native iOS
- Flutter
- React Native
- Kotlin Multiplatform
- Compose Multiplatform
- Mobile web / PWA
- Ionic / Capacitor
- Other / mixed

### 9. How are the platforms of your main product implemented?

*Type: Single choice · ID: `app_strategy`*

- Separate native codebases
- Shared business logic with native UI
- Shared logic and UI
- Web-based / hybrid app
- Single platform only
- Other / not applicable

### 10. Approximately how much code is shared between platforms?

*Type: Single choice · ID: `code_shared`*

- None / 0%
- 1–25%
- 26–50%
- 51–75%
- 76–100%
- Not applicable / unsure

### 11. Tell us your experience with these technologies.

*Type: Experience matrix · ID: `framework_experience`*

**Guidance:** Optional per technology. For each one, indicate your exposure; for tools you have tried, tell us if you would use them again.

**Technologies:**

- Native Android
- Native iOS
- Flutter
- React Native
- Kotlin Multiplatform
- Compose Multiplatform
- Ionic / Capacitor
- .NET MAUI
- Mobile web / PWA

**Experience (one per technology):**

- Using in production
- Previously in production
- Only tried / explored
- Aware, not used
- Never heard of it

**Would you use it again?** *(Only if currently using in production, previously in production, or tried/explored.)*

- Yes
- Maybe / unsure
- No

### 12. Why was your primary approach chosen?

*Type: Multiple choice · ID: `approach_reasons`*

**Guidance:** Choose up to three.

**Maximum selections:** 3

- Developer experience
- Performance
- Native look and feel
- Team skills / hiring
- Code sharing
- Delivery speed / cost
- Existing codebase / company mandate
- Ecosystem / library availability
- Business requirements
- Other

### 13. Are you considering changing your main development approach?

*Type: Single choice · ID: `migration`*

- Yes, in the next 12 months
- Investigating options
- No plans to change
- Not sure

## Languages & stack

*The languages, UI systems and architectural approaches you use in real projects.*

### 14. Which programming languages do you use for mobile development?

*Type: Multiple choice · ID: `languages`*

- Kotlin
- Swift
- Java
- Objective-C
- Dart
- JavaScript
- TypeScript
- C#
- C / C++
- Rust
- Other

### 15. Which UI technologies do you currently work with?

*Type: Multiple choice · ID: `ui_stack`*

- Jetpack Compose
- Android Views / XML
- SwiftUI
- UIKit
- Flutter widgets
- React Native components
- Compose Multiplatform
- HTML / CSS / web views
- Other

### 16. Which patterns or architectural approaches do you use?

*Type: Multiple choice · ID: `architecture`*

- MVVM
- MVI / UDF
- MVC
- MVP / VIPER
- Clean Architecture
- Redux / Flux
- Modular architecture
- No explicit pattern
- Other

### 17. How does your main mobile app communicate with services?

*Type: Multiple choice · ID: `backend`*

- REST APIs
- GraphQL
- gRPC
- WebSockets / realtime
- Firebase services
- Supabase
- Locally only / offline
- Other

### 18. What do you use for persistent on-device data?

*Type: Multiple choice · ID: `local_data`*

- Room / SQLite
- Core Data / SwiftData
- Realm
- SQLDelight
- Key-value / preferences
- Browser storage / IndexedDB
- Custom / other
- No local storage

## Mobile capabilities

*Which platform features actually make their way into products?*

### 19. Which form factors do you actively develop for?

*Type: Multiple choice · ID: `device_types`*

- Phones
- Tablets / large screens
- Foldables
- Watches / wearables
- TVs
- Cars / in-vehicle
- XR / spatial devices
- Other

### 20. Which capabilities have you implemented or maintained in the past 12 months?

*Type: Multiple choice · ID: `device_apis`*

- Push notifications
- Background execution / tasks
- Camera / media
- Location / maps
- Bluetooth / BLE
- NFC / payments
- Biometrics / passkeys
- On-device ML
- On-device generative AI
- Accessibility APIs
- Widgets / live activities
- Deep linking / universal links
- Offline sync
- None of these

### 21. Which native capabilities are hardest to integrate or maintain?

*Type: Long text · ID: `api_pain`*

*Free-text prompt:* Optional: a concrete example helps. What made it difficult?

### 22. How do you test accessibility in your mobile apps?

*Type: Multiple choice · ID: `accessibility`*

- Manual accessibility review
- Screen reader testing
- Automated accessibility checks
- Testing with people with disabilities
- We plan to, but not yet
- Not currently addressed
- Not applicable

## Quality & delivery

*Tests, tooling, releases and everything that happens between a working build and a working app.*

### 23. Which types of automated testing do you use?

*Type: Multiple choice · ID: `testing_types`*

- Unit
- Integration
- UI / component
- End-to-end
- Screenshot / snapshot
- Performance
- Accessibility
- None

### 24. Which mobile testing tools do you use?

*Type: Multiple choice · ID: `testing_tools`*

- XCTest / XCUITest
- Espresso / UI Automator
- Robolectric
- Maestro
- Detox
- Appium
- Flutter test / integration_test
- Playwright / browser tests
- Other
- None

### 25. Which CI/CD systems do you use for mobile delivery?

*Type: Multiple choice · ID: `cicd`*

- GitHub Actions
- GitLab CI
- Bitrise
- Codemagic
- CircleCI
- Jenkins
- Xcode Cloud
- Azure DevOps
- Fastlane
- Other
- None

### 26. Which observability or crash tools do you use?

*Type: Multiple choice · ID: `monitoring`*

- Firebase Crashlytics
- Sentry
- Bugsnag
- Datadog
- New Relic
- App Store Connect / Play Console metrics
- Custom tooling
- None

### 27. How often does your main mobile product release?

*Type: Single choice · ID: `release_frequency`*

- Daily / multiple times a week
- Weekly
- Every 2 weeks
- Monthly
- Less than monthly
- Not in production

### 28. Where do you distribute your apps?

*Type: Multiple choice · ID: `distribution`*

- Apple App Store
- Google Play
- Alternative app stores
- Enterprise / private distribution
- Direct download / sideloading
- Web / PWA
- Not released yet

### 29. What causes the most friction in your mobile development workflow?

*Type: Multiple choice · ID: `pain_points`*

**Guidance:** Choose up to three.

**Maximum selections:** 3

- Build times
- IDE / editor tooling
- Debugging
- Dependencies and upgrades
- OS changes / fragmentation
- Device testing
- Flaky tests
- Performance / memory
- App signing / certificates
- App store reviews / policies
- Release automation
- Team coordination
- Other

## AI & what’s next

*How AI affects your work today, and what you expect to matter tomorrow.*

### 30. How often do you use AI tools when developing mobile apps?

*Type: Single choice · ID: `ai_frequency`*

- Multiple times a day
- Daily
- Weekly
- Rarely
- Never

### 31. Which AI development tools have you used?

*Type: Multiple choice · ID: `ai_tools`*

- GitHub Copilot
- ChatGPT
- Claude / Claude Code
- Gemini / Gemini in Android Studio
- Cursor
- Windsurf
- JetBrains AI / Junie
- Other
- None

### 32. Roughly what share of the code you write is AI-generated?

*Type: Single choice · ID: `ai_code_share`*

**Guidance:** Your perception, not a measured figure.

- 0%
- 1–10%
- 11–25%
- 26–50%
- 51–75%
- 75-99%
- 100%
- Not sure

### 33. Where is AI least reliable for mobile development?

*Type: Multiple choice · ID: `ai_unreliable`*

- Native APIs / OS compatibility
- UI implementation
- Concurrency / state
- Build configuration
- Cross-platform integration
- Debugging
- Automated tests
- Security / privacy
- Performance
- Not sure / not using AI

### 34. Have you integrated AI capabilities into a mobile product?

*Type: Multiple choice · ID: `ai_product`*

- Cloud-based generative AI
- On-device generative AI
- On-device ML (non-generative)
- Cloud ML (non-generative)
- Planning to
- No

### 35. Which topics are you most interested in exploring next?

*Type: Multiple choice · ID: `emerging`*

**Guidance:** Choose up to three.

**Maximum selections:** 3

- On-device AI
- AI-powered app features
- Kotlin Multiplatform
- Compose Multiplatform
- SwiftUI
- Flutter
- React Native
- Mobile web / PWAs
- XR / spatial computing
- Wearables
- Accessibility
- Privacy-preserving development
- Other

## Final thoughts

*The best insights often come from what developers say in their own words.*

### 36. What is the biggest challenge facing mobile developers today?

*Type: Long text · ID: `biggest_challenge`*

*Free-text prompt:* What do you wish the whole industry would fix?

### 37. What would you like Apple, Google or framework maintainers to improve?

*Type: Long text · ID: `platform_wishlist`*

*Free-text prompt:* Optional: tell us what would make your daily work better.

### 38. How did you find the length of this survey?

*Type: Single choice · ID: `survey_length`*

- Too short
- About right
- Slightly too long
- Much too long

### 39. What important mobile topics did we miss?

*Type: Long text · ID: `missing_topics`*

*Free-text prompt:* Help shape the next edition.

### Native Android

Shown for **Native Android**.

#### 1. What UI technology do you use most?

*Type: Single choice · ID: `and_ui`*

- Jetpack Compose
- Android Views / XML
- A mix of Compose and Views
- Other

#### 2. What is your main app’s minimum supported Android version?

*Type: Single choice · ID: `and_minsdk`*

- Android 8 or earlier
- Android 9–10
- Android 11–12
- Android 13–14
- Android 15+
- Unsure / not applicable

#### 3. What build setup does your team primarily use?

*Type: Single choice · ID: `and_build`*

- Gradle with Kotlin DSL
- Gradle with Groovy DSL
- Bazel / other
- Not sure

#### 4. What are your biggest Android-specific pain points?

*Type: Multiple choice · ID: `and_pain`*

**Maximum selections:** 3

- Gradle / build performance
- Android Studio
- Device / OEM fragmentation
- Background restrictions
- Play policies / distribution
- Compose UI / state
- Dependency upgrades
- Tests / emulators
- Other

#### 5. What would you most like the Android team to improve?

*Type: Long text · ID: `and_ask`*

*Free-text prompt:* Optional

### Native iOS

Shown for **Native iOS**.

#### 1. What UI technology do you use most?

*Type: Single choice · ID: `ios_ui`*

- SwiftUI
- UIKit
- A mix of SwiftUI and UIKit
- Other

#### 2. What is the minimum iOS version supported by your main app?

*Type: Single choice · ID: `ios_min`*

- iOS 16 or earlier
- iOS 17
- iOS 18
- iOS 26
- iOS 27 or later
- Unsure / not applicable

#### 3. Which concurrency or reactive tools do you use?

*Type: Multiple choice · ID: `ios_concurrency`*

- Swift async/await
- Swift actors
- Combine
- Grand Central Dispatch
- RxSwift
- Other

#### 4. What are your biggest iOS-specific pain points?

*Type: Multiple choice · ID: `ios_pain`*

**Maximum selections:** 3

- Xcode / builds
- SwiftUI limitations
- Swift language / tooling
- Signing / provisioning
- App Store review
- OS compatibility
- Tests / simulators
- Interoperability
- Other

#### 5. What would you most like the Apple developer tools team to improve?

*Type: Long text · ID: `ios_ask`*

*Free-text prompt:* Optional

### Flutter

Shown for **Flutter**.

#### 1. Which state management approaches do you use?

*Type: Multiple choice · ID: `fl_state`*

- Riverpod
- BLoC / Cubit
- Provider
- GetX
- MobX
- setState / built-in
- Other

#### 2. Which navigation approaches do you use?

*Type: Multiple choice · ID: `fl_nav`*

- go_router
- Navigator APIs
- auto_route
- GetX routing
- Other

#### 3. How often do you write native Android/iOS code or use platform channels?

*Type: Single choice · ID: `fl_native`*

- Very often
- Sometimes
- Rarely
- Never

#### 4. What are your biggest Flutter-specific pain points?

*Type: Multiple choice · ID: `fl_pain`*

**Maximum selections:** 3

- Native integration / plugins
- Package quality
- App size
- Build / release tooling
- Performance
- Platform look and feel
- Web / desktop parity
- State management
- Other

#### 5. What would most improve Flutter for you?

*Type: Long text · ID: `fl_ask`*

*Free-text prompt:* Optional

### React Native

Shown for **React Native**.

#### 1. What is your primary React Native workflow?

*Type: Single choice · ID: `rn_workflow`*

- Expo managed / development builds
- Expo with custom native code
- React Native Community CLI
- React Native embedded in an existing native app
- Other

#### 2. How far has your team adopted the New Architecture?

*Type: Single choice · ID: `rn_arch`*

- Fully adopted
- Partially / migrating
- Not yet
- Not sure

#### 3. Which state management tools do you use?

*Type: Multiple choice · ID: `rn_state`*

- Redux / Redux Toolkit
- Zustand
- TanStack Query
- MobX
- React Context / hooks
- Jotai / Recoil
- Other

#### 4. What are your biggest React Native-specific pain points?

*Type: Multiple choice · ID: `rn_pain`*

**Maximum selections:** 3

- Dependencies / upgrades
- Native module compatibility
- Debugging
- Performance
- Platform parity
- Build configuration
- Navigation
- Testing
- Other

#### 5. What would most improve React Native for you?

*Type: Long text · ID: `rn_ask`*

*Free-text prompt:* Optional

### Kotlin Multiplatform

Shown for **Kotlin Multiplatform** or **Compose Multiplatform**.

#### 1. What do you share across platforms?

*Type: Multiple choice · ID: `kmp_shared`*

- Domain / business logic
- Networking
- Persistence
- UI with Compose Multiplatform
- Tests
- Other

#### 2. How is the iOS interface built?

*Type: Single choice · ID: `kmp_ios_ui`*

- SwiftUI
- UIKit
- Compose Multiplatform
- Mixed native and Compose UI
- No iOS target
- Other

#### 3. How mature is your KMP adoption?

*Type: Single choice · ID: `kmp_stage`*

- Investigating / learning
- Prototype / proof of concept
- Partially in production
- Widely used in production

#### 4. What are your biggest KMP-specific pain points?

*Type: Multiple choice · ID: `kmp_pain`*

**Maximum selections:** 3

- Xcode integration
- Kotlin / Swift interop
- Gradle / builds
- Library ecosystem
- Debugging / tooling
- Team organization
- Compose iOS maturity
- Other

#### 5. What would most improve Kotlin or Compose Multiplatform for you?

*Type: Long text · ID: `kmp_ask`*

*Free-text prompt:* Optional

### Web & hybrid mobile

Shown for **Mobile web / PWA** or **Ionic / Capacitor**.

#### 1. What kinds of mobile experiences do you build?

*Type: Multiple choice · ID: `web_type`*

- Responsive websites
- Installable PWAs
- Capacitor / Ionic apps
- NativeScript apps
- Embedded web views
- Other

#### 2. What do you primarily use for UI?

*Type: Single choice · ID: `web_stack`*

- React / Next.js
- Vue / Nuxt
- Angular
- Svelte / SvelteKit
- Plain web platform
- Other

#### 3. What limits your mobile web or hybrid apps most?

*Type: Multiple choice · ID: `web_pain`*

**Maximum selections:** 3

- Background tasks
- Push notifications
- Offline behavior
- Hardware access
- Browser inconsistencies
- Store distribution
- Performance
- Native integrations
- Other

#### 4. Do you publish through mobile app stores?

*Type: Single choice · ID: `web_release`*

- Yes, Apple and Google
- Only Apple
- Only Google
- No
- Not sure

#### 5. What would most improve mobile web or hybrid development?

*Type: Long text · ID: `web_ask`*

*Free-text prompt:* Optional

### Your approach

Fallback for **Other / mixed** or when the primary approach is not selected.

#### 1. What is your primary development stack?

*Type: Short text · ID: `other_stack`*

*Free-text prompt:* e.g. .NET MAUI, Unity, a custom stack…

#### 2. What makes this approach a good fit?

*Type: Long text · ID: `other_reasons`*

*Free-text prompt:* Optional

#### 3. What frustrates you most about this approach?

*Type: Long text · ID: `other_pain`*

*Free-text prompt:* Optional
