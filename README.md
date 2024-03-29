## Random iOS write-ups
_If Burbulla saw what I tried to pass off as linear algebra in these two posts, he'd probably try and take my iron ring away_
* [How do basic 3D transforms of iOS views work under the hood?](https://thealexanderlee.com/blog/how-do-3d-transforms-of-ios-views-work-under-the-hood)
* [3D transforms on iOS under the hood part II: perspective shifts](https://thealexanderlee.com/blog/3d-transforms-on-ios-under-the-hood-part-2-perspective-shifts)

## Open-source Swift Packages I wrote
* [DesignReviewer](https://github.com/alexslee/DesignReviewer): cut down on Xcode lag, and debug/make tweaks to your UI right from your application
    *  Complete with an implementation of the 3D view hierarchy experience you get from Xcode, written with incremental `CALayer` transforms + `CAAnimation` -- handily enough, those transformations are [documented in the code](https://github.com/alexslee/DesignReviewer/blob/0d36b57f57d3581bc44defb43ec01d70dc0ca2cb/Sources/DesignReviewer/Exploded%20Hierarchy/DesignReviewExplodedHierarchyContainerView.swift#L74) + the fundamentals are written in the articles above
 *  [FlexSeal](https://github.com/alexslee/FlexSeal): A lifecycle tracking tool to find potential memory leaks during development and testing. Displays the count + addresses of all instances of the classes you wish to track, with handy visual cues when the limits you define are exceeded. 
     *  Using this in conjunction with Xcode's memory graph can be a powerful way of root-causing any suspected leaks
 *  [Scintillate](https://github.com/alexslee/Scintillate): a lightweight, UIKit+AppKit-friendly way to either mask content or show a loading state. Think: SwiftUI's 'redacted' modifier, for non-SwiftUI applications on iOS + macOS.
    *  Another use case for the recursive view hierarchy traversal logic from `DesignReviewer`, along with some simple `CALayer` + `CAAnimation` management.

## Random stat generator that is definitely undercounting but at least it looks nice

[![Alex's GitHub stats](https://github-readme-stats-psi-coral.vercel.app/api?username=alexslee&count_private=true&include_all_commits=true&theme=nightowl)](https://github.com/anuraghazra/github-readme-stats)

<!--
**alexslee/alexslee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
