<div align="justify">

```
Brave:               1.41.94 Chromium: 103.0.5060.114 (Official Build) unknown (64-bit) 
Revision:            a1c2360c5b02a6d4d6ab33796ad8a268a6128226-refs/branch-heads/5060@{#1124}
Operating System:    Gentoo/Linux x86_64 // Gentoo Base System release 2.8
JavaScript:          V8 10.3.174.18
Command-line:        brave --use-gl=desktop --enable-features=VaapiVideoDecoder,VaapiVideoEncoder %u
```

# <img alt="" align="left" src="https://badges.pufler.dev/visits/owl4ce/chrome-flags?style=flat-square&label=&color=000000&logo=github&logoColor=white&labelColor=000000"/> <p align="right">`Enabled`</p>

## Override software rendering list
Overrides the built-in software rendering list and enables GPU-acceleration on unsupported system configurations. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#ignore-gpu-blocklist

## WebRTC multi-channel capture audio processing.
Support in WebRTC for processing capture audio in multi channel without downmixing when running APM in the render process. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-webrtc-capture-multi-channel-audio-processing

## Enable Reader Mode
Allows viewing of simplified web pages by selecting 'Customize and control Chrome'>'Distill page' – Mac, Windows, Linux, Chrome OS

chrome://flags/#enable-reader-mode

## Show Autofill predictions
Annotates web forms with Autofill field type predictions as placeholder text. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#show-autofill-type-predictions

## Center-aligned Autofill suggestions.
When enabled, the Autofill suggestion popup will be aligned to the center of the initiating field and not to its border. – Mac, Windows, Linux, Chrome OS

chrome://flags/#autofill-center-aligned-suggestions

## Type-specific width limits for the Autofill popup
Controls if different width limits are used for the popup that provides Autofill suggestions, depending on the type of data that is filled. – Mac, Windows, Linux, Chrome OS

chrome://flags/#autofill-type-specific-popup-width

## Consistent Autofill settings icon
If enabled, all Autofill data types including addresses, credit cards and passwords will use a consistent icon in the popup settings footer. – Mac, Windows, Linux, Chrome OS

chrome://flags/#autofill-use-consistent-popup-settings-icons

## Smooth Scrolling
Animate smoothly when scrolling page content. – Windows, Linux, Chrome OS, Android

chrome://flags/#smooth-scrolling

## Overlay Scrollbars
Enable the experimental overlay scrollbars implementation. You must also enable threaded compositing to have the scrollbars animate. – Windows, Linux, Chrome OS

chrome://flags/#overlay-scrollbars

## Experimental QUIC protocol
Enable experimental QUIC protocol support. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-quic

## Experimental JavaScript
Enable web pages to use experimental JavaScript features. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-javascript-harmony

## Experimental WebAssembly
Enable web pages to use experimental WebAssembly features. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-experimental-webassembly-features

## WebAssembly baseline compiler
Enables WebAssembly baseline compilation and tier up. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-webassembly-baseline

## WebAssembly lazy compilation
Enables lazy (JIT on first call) compilation of WebAssembly modules. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-webassembly-lazy-compilation

## WebAssembly tiering
Enables tiered compilation of WebAssembly (will tier up to TurboFan if #enable-webassembly-baseline is enabled). – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-webassembly-tiering

## Future V8 VM features
This enables upcoming and experimental V8 VM features. This flag does not enable experimental JavaScript features. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-future-v8-vm-features

## GPU rasterization
Use GPU to rasterize web content. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-gpu-rasterization

## Show autofill signatures.
Annotates web forms with Autofill signatures as HTML attributes. Also marks password fields suitable for password generation. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-show-autofill-signatures

## Pull-to-refresh gesture
Pull-to-refresh gesture in response to vertical overscroll. – Windows, Linux, Chrome OS

chrome://flags/#pull-to-refresh

## WebGL Draft Extensions
Enabling this option allows web applications to access the WebGL extensions that are still in draft status. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-webgl-draft-extensions

## Zero-copy rasterizer
Raster threads write directly to GPU memory associated with tiles. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-zero-copy

## Enable Mojo Shared Memory Channel
If enabled Mojo on Linux based platforms can use shared memory as an alternate channel for most messages. – Linux, Chrome OS, Android

chrome://flags/#mojo-linux-sharedmem

## History Journeys
Enables the History Journeys UI. – Mac, Windows, Linux, Chrome OS

chrome://flags/#history-journeys

## Reading List
Click on the Bookmark icon or right click on a tab to add tabs to a reading list. – Mac, Windows, Linux, Chrome OS

chrome://flags/#read-later

## Parallel downloading
Enable parallel downloading to accelerate download speed. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-parallel-downloading

## Enable new download backend
Enables the new download backend that uses offline content provider – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-new-download-backend

## Accessible PDF Forms
Enables accessibility support for PDF forms. – Mac, Windows, Linux, Chrome OS

chrome://flags/#accessible-pdf-form

## Move Autofill omnibox icons next to the profile avatar icon
When enabled, Autofill data related icon will be shown in the status chip next to the profile avatar icon in the toolbar. – Mac, Windows, Linux

chrome://flags/#autofill-enable-toolbar-status-chip

## Live Caption
Enables the live caption feature which generates captions for media playing in Chrome. Turn the feature on in chrome://settings/accessibility. – Mac, Windows, Linux, Chrome OS

chrome://flags/#enable-accessibility-live-caption

## Hardware Media Key Handling
Enables using media keys to control the active media session. This requires MediaSessionService to be enabled too – Mac, Windows, Linux, Chrome OS

chrome://flags/#hardware-media-key-handling

## Autofill Uses Improved Label Disambiguation
When enabled, the Autofill dropdown's suggestions' labels are displayed using the improved disambiguation format. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#autofill-use-improved-label-disambiguation

## Strict Extension Isolation
Experimental security mode that prevents extensions from sharing a process with each other. – Mac, Windows, Linux, Chrome OS

chrome://flags/#strict-extension-isolation

## Strict-Origin-Isolation
Experimental security mode that strengthens the site isolation policy. Controls whether site isolation should use origins instead of scheme and eTLD+1. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#strict-origin-isolation

## Global Media Controls Modern UI
Use a redesigned version of the Global Media Controls UI. Requires #global-media-controls to also be enabled. – Mac, Windows, Linux, Chrome OS

chrome://flags/#global-media-controls-modern-ui

## Offer save and autofill of UPI/VPA values
If enabled, when autofill recognizes a UPI/VPA value in a payment form, it will offer to save it. If saved, it will be offered for filling in fields which expect a VPA. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-autofill-upi-vpa

## Back-forward cache
If enabled, caches eligible pages after cross-site navigations.To enable caching pages on same-site navigations too, choose 'enabled same-site support'. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#back-forward-cache

## Impulse-style scroll animations
Replaces the default scroll animation with Impulse-style scroll animations. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#impulse-scroll-animations

## Reduce User-Agent request header
Reduce (formerly, "freeze") the amount of information available in the User-Agent request header. See https://www.chromium.org/updates/ua-reduction for more info. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#reduce-user-agent

## 'About this site' section in page info
Enable the 'About this site' section in the page info. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#page-info-about-this-site

## Experimental canvas 2D API features
Enables in-progress features for the canvas 2D API. See https://github.com/fserb/canvas2d. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#new-canvas-2d-api

## Enable LiteVideos
Enable the LiteVideo optimization to throttle media requests to reduce data usage – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-lite-video

## Force LiteVideos decision
Force the LiteVideo decision to be allowed on every navigation. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#lite-video-force-override-decision

## Allow widgets to inherit native theme from its parent widget.
When enabled, secondary UI like menu, dialog etc would be in dark mode when Incognito mode is open. – Mac, Windows, Linux, Chrome OS

chrome://flags/#inherit-native-theme-from-parent-widget

## Restructured Language Settings (Desktop)
Enable the new restructured language settings page – Mac, Windows, Linux, Chrome OS

chrome://flags/#desktop-restructured-language-settings

## Detailed Language Settings (Desktop)
Enable the new detailed language settings page – Mac, Windows, Linux, Chrome OS

chrome://flags/#desktop-detailed-language-settings

## Revamped Incognito New Tab Page
When enabled, Incognito new tab page will have an updated UI – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#incognito-ntp-revamp

## Prerender2
Enables the new prerenderer implementation for <script type=speculationrules> that specifies prerender candidates. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-prerender2

## WebUI Branding Update
Changes various UI components in WebUI pages to have a more modern look. – Mac, Windows, Linux, Chrome OS

chrome://flags/#webui-branding-update

## Chrome Labs
Access Chrome Labs through the toolbar menu to see featured user-facing experimental features. – Mac, Windows, Linux, Chrome OS

chrome://flags/#chrome-labs

## Autofill Address Save Prompts
Enable the Autofill address save prompts. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#autofill-address-save-prompt

## Enable WebRTC actions in Media Session
Adds new actions into Media Session for video conferencing. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#media-session-webrtc

## Composite after paint
A new algorithm to create compositing layers. See http://bit.ly/composite-after-paint. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#composite-after-paint

## Enable the fix for Autofill offer in Incognito mode
When enabled, the fix will be enabled and offers should work correctly in Incognito mode. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#autofill-fix-offer-in-incognito

## Playback Speed Button
Enable the playback speed button on the media controls. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#playback-speed-button

## Privacy Review
Shows a new subpage in Settings that helps the user to review various privacy settings. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#privacy-review

## Show app menu history sub menus
Show app menu history sub menus for the contents of recently closed tab groups and windows. – Mac, Windows, Linux, Chrome OS

chrome://flags/#tab-restore-sub-menus

## Fuzzy search for Tab Search
Enable fuzzy search for Tab Search. – Mac, Windows, Linux, Chrome OS

chrome://flags/#tab-search-fuzzy-search

## Show Chrome What's New page at chrome://whats-new
Enables Chrome What's New page at chrome://whats-new. – Mac, Windows, Linux, Chrome OS

chrome://flags/#chrome-whats-new-ui

## Enables Display Compositor to use a new gpu thread.
When enabled, chrome uses 2 gpu threads instead of 1. Display compositor uses new dr-dc gpu thread and all other clients (raster, webgl, video) continues using the gpu main thread. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#enable-drdc

## Extensions Menu Access Control
Enables a redesigned extensions menu that allows the user to control extensions site access. – Mac, Windows, Linux, Chrome OS

chrome://flags/#extensions-menu-access-control

## Out-of-process 2D canvas rasterization.
The rasterization of 2d canvas contents is performed in the GPU process. Requires that out-of-process rasterization be enabled. – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#canvas-oop-rasterization

## Enable cosmetic filtering
Enable support for cosmetic filtering – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#brave-adblock-cosmetic-filtering

## Shields first-party network blocking
Allow Brave Shields to block first-party network requests in Standard blocking mode – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#brave-adblock-default-1p-blocking

## Enable domain blocking
Enable support for blocking domains with an interstitial page – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#brave-domain-block

## Enable debouncing
Enable support for skipping top-level redirect tracking URLs – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#brave-debounce

## Enable extension network blocking
Enable blocking for network requests initiated by extensions – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#brave-extension-network-blocking

## Enable sync loading of cosmetic filter rules
Enable sync loading of cosmetic filter rules – Mac, Windows, Linux, Chrome OS, Android

chrome://flags/#brave-cosmetic-filtering-sync-load

## Enable Brave Sync v2
Brave Sync v2 integrates with chromium sync engine with Brave specific authentication flow and enforce client side encryption – Mac, Windows, Linux, Chrome OS

chrome://flags/#brave-sync-v2

## Interactive Tab audio indicator
Enable the Tab audio indicator to also be a button which can mute and unmute the Tab. – Mac, Windows, Linux, Chrome OS

chrome://flags/#tab-audio-icon-interactive

## Enable SpeedReader
Enables faster loading of simplified article-style web pages. – Mac, Windows, Linux, Chrome OS

chrome://flags/#brave-speedreader

# <p align="right">`Debugging`</p>

## Local State Debug Page
Debug Chrome local state in JSON format.

chrome://local-state

## Media Internals
Tool to dig into the guts of the Chrome [audio/video stack](https://dev.chromium.org/audio-video). For per browser tab, see https://developer.chrome.com/docs/devtools/media-panel.

chrome://media-internals

## URLs
Show all available Chrome URLs.

chrome://about

</div>
