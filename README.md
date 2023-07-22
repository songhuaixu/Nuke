<br/>
<img src="https://user-images.githubusercontent.com/1567433/114792417-57c1d080-9d56-11eb-8035-dc07cfd7557f.png" height="205">

# Image Loading System

<p align="left">
<img src="https://img.shields.io/badge/platforms-iOS%2C%20macOS%2C%20watchOS%2C%20tvOS-lightgrey.svg">
<img src="https://github.com/kean/Nuke/workflows/Nuke%20CI/badge.svg">
</p>

Nuke provides an efficient way to load and display images in your app and is easy to learn and use.

The framework is lean and compiles in under 2 seconds[¹](#footnote-1). Nuke has an automated test suite 2x the codebase size, ensuring excellent reliability. Nuke is optimized for [performance](https://kean-docs.github.io/nuke/documentation/nuke/performance-guide), and its architecture enables virtually unlimited possibilities for customization.

> **Fast LRU memory and disk cache** · **SwiftUI** · **Smart background decompression** · **Image processing** · **Resumable downloads** · **Intelligent deduplication** · **Request prioritization** · **Prefetching** · **Rate limiting** · **Progressive JPEG, HEIF, WebP, SVG, GIF** · **Alamofire** · **Combine** · **Async/Await**

## Sponsors

<a target="_blank" rel="noopener noreferrer" href="https://getstream.io/chat/sdk/swiftui/?utm_source=Nuke&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Nuke_July2022_SwiftUIChat_klmh22#gh-light-mode-only"><img src="https://user-images.githubusercontent.com/1567433/175186173-64eb53cb-b5d6-4ed4-aaca-87dbbb0834ab.png#gh-light-mode-only" width="300px" alt="Stream Logo" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://getstream.io/chat/sdk/swiftui/?utm_source=Nuke&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Nuke_July2022_SwiftUIChat_klmh22#gh-dark-mode-only"><img src="https://user-images.githubusercontent.com/1567433/175562043-0ab82adc-e3c7-4c0b-8813-a7940ff41db8.png#gh-dark-mode-only" width="244px" alt="Stream Logo" style="max-width: 100%;"></a>

Nuke is proudly sponsored by [Stream](https://getstream.io/chat/sdk/swiftui/?utm_source=Nuke&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Nuke_July2022_SwiftUIChat_klmh22), the leading provider in enterprise grade Feed & Chat APIs.

> [Support](https://github.com/sponsors/kean) Nuke on GitHub Sponsors.

### Additional Sponsors

<table>
  <tr>
    <td valign="center">
        <a href="https://proxyman.io"><img src="https://github.com/kean/Nuke/assets/1567433/f7ed209a-363d-4ebd-9919-dbc796d21b07" height="40px" alt="Proxyman Logo"></a>
    </td>
    <td valign="center">
        <a href="https://www.namiml.com#gh-light-mode-only"><img src="https://github.com/kean/Nuke/assets/1567433/39ffc0e5-2fb4-4830-b565-7866c6472d6c#gh-light-mode-only" height="28px" alt="Nami Logo"></a><a href="https://www.namiml.com#gh-dark-mode-only"><img src="https://github.com/kean/Nuke/assets/1567433/951aaf7d-e47e-4e36-a159-e0d3e30f785d#gh-dark-mode-only" height="28px" alt="Nami Logo"></a>
    </rd>
    <td valign="center">
        <a href="https://sentry.io#gh-light-mode-only"><img src="https://github.com/kean/Nuke/assets/1567433/e286b853-fd9b-4948-af3f-b10614982fa4#gh-light-mode-only" height="40px" alt="Nami Logo"></a><a href="https://sentry.io#gh-dark-mode-only"><img src="https://github.com/kean/Nuke/assets/1567433/40f99559-a5ff-41ae-b614-867e9cce1263#gh-dark-mode-only" height="40px" alt="Nami Logo"></a>
    </td>
  </tr>
</table>

## Installation

Nuke supports [Swift Package Manager](https://www.swift.org/package-manager/), which is the recommended option. If that doesn't work for you, you can use binary frameworks attached to the [releases](https://github.com/kean/Nuke/releases).

## Documentation

Nuke is easy to learn and use thanks to documentation generated using DocC: [**Nuke**](https://kean-docs.github.io/nuke/documentation/nuke/getting-started/), [**NukeUI**](https://kean-docs.github.io/nukeui/documentation/nukeui/), [**NukeExtensions**](https://kean-docs.github.io/nukeextensions/documentation/nukeextensions/). Make sure to also check out [**Nuke Demo**](https://github.com/kean/NukeDemo).

> Upgrading from the previous version? Use a [**Migration Guide**](https://github.com/kean/Nuke/tree/master/Documentation/Migrations).

<a href="https://kean-docs.github.io/nuke/documentation/nuke/getting-started">
<img width="690" alt="Nuke Docs" src="https://user-images.githubusercontent.com/1567433/175793167-b7e0c557-b887-444f-b18a-57d6f5ecf01a.png">
</a>

## Extensions

The image pipeline is easy to customize and extend. Check out the following first-class extensions and packages built by the community.

|Name|Description|
|--|--|
|[**Alamofire Plugin**](https://github.com/kean/Nuke-Alamofire-Plugin)|Replace networking layer with [Alamofire](https://github.com/Alamofire/Alamofire)|
|[**NukeWebP**](https://github.com/makleso6/NukeWebP)| **Community**. [WebP](https://developers.google.com/speed/webp/) support, built by [Maxim Kolesnik](https://github.com/makleso6)|
|[**WebP Plugin**](https://github.com/ryokosuge/Nuke-WebP-Plugin)| **Community**. [WebP](https://developers.google.com/speed/webp/) support, built by [Ryo Kosuge](https://github.com/ryokosuge)|
|[**AVIF Plugin**](https://github.com/delneg/Nuke-AVIF-Plugin)| **Community**. [AVIF](https://caniuse.com/avif) support, built by [Denis](https://github.com/delneg)|
|[**RxNuke**](https://github.com/kean/RxNuke)|[RxSwift](https://github.com/ReactiveX/RxSwift) extensions for Nuke with examples|

> Looking for a way to log your network requests, including image requests? Check out [**Pulse**](https://github.com/kean/Pulse).

## Minimum Requirements

| Nuke       | Date         | Swift       | Xcode      | Platforms                                     |
|------------|--------------|-------------|------------|-----------------------------------------------|
| Nuke 12.0  | Mar 4, 2023  | Swift 5.6   | Xcode 13.3 | iOS 13.0, watchOS 6.0, macOS 10.15, tvOS 13.0 |
| Nuke 11.0  | Jul 20, 2022 | Swift 5.6   | Xcode 13.3 | iOS 13.0, watchOS 6.0, macOS 10.15, tvOS 13.0 |
| Nuke 10.0  | Jun 1, 2021  | Swift 5.3   | Xcode 12.0 | iOS 11.0, watchOS 4.0, macOS 10.13, tvOS 11.0 |

## License

Nuke is available under the MIT license. See the LICENSE file for more info.

----

> <a name="footnote-1">¹</a> Measured on MacBook Pro 14" 2021 (10-core M1 Pro)
