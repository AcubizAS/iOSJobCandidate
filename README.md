# iOSJobCandidate

## Overview

The goal of this assignment is to build a small iOS application that fetches data from a public API, displays a list of items, and shows a detail view when an item is selected.

This exercise is intentionally limited in scope. We are primarily interested in code quality, structure, and decision-making rather than visual polish or advanced features.

---

## Time Expectation

4–5 hours.

Please try to stay within this time frame. If you choose to spend additional time, note this in the README and briefly explain why. We value transparency over completeness.

---

## Functional Requirements

### List Screen
- Fetch data from a public API
- Display a list of items
- Each item should show:
  - A title
  - A secondary piece of information
- Display a loading state
- Handle empty and error states

### Detail Screen
- Selecting an item should navigate to a detail view
- The detail view should display additional information about the selected item

### Networking
- Perform asynchronous network requests
- Basic error handling is sufficient

---

## API

You may use one of the following public APIs, or another comparable API of your choice:

- GitHub API (users or repositories)
    - Example endpoints:
      - https://api.github.com/users
      - https://api.github.com/search/repositories?q=ios
- iTunes Search API
  - Example endpoint:
    - https://itunes.apple.com/search?term=ios&entity=software
- OpenWeather (current weather only)
  - Example endpoint:
    - https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&current_weather=true
- Any public JSON API you are comfortable with

If you prefer to use mocked data or a local JSON file, that is acceptable. Please explain your choice in the README.

---

## Technical Requirements

- Language: Swift
- Minimum iOS version: iOS 16+
- UI framework: SwiftUI or UIKit
- Architecture: Your choice (MVVM encouraged but not required)
- Dependencies: Avoid heavy third-party frameworks. Small utilities are fine.

---

## Deliverables

Please provide:

1. The source code (GitHub repository or zip file)
2. A README that includes:
   - A brief explanation of your approach
   - Architecture and design decisions
   - Trade-offs made due to time constraints
   - What you would improve or add with more time

---

## Getting Started

1. Create a new Xcode project / fork this project
2. Commit your work incrementally
3. Share the repository when complete

Thank you for taking the time to complete this assignment.
