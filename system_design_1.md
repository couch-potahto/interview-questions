# Designing a custom URL shortener

## Preface
URL shortening is used to create shorter aliases for long URLs. These shortened aliases are called "short links", and users are redirected to the original URL when they use these "short links". URL shortening is used to optimize links across devices, track click rates, or to hide original URLs.

## Requirements and Goals of the System

### Functional Requirements
1. Given a URL, our service should generate a **shorter** and **unique** alias of it. This alias should be reusable up to a default of 12 hours, or to a minimum of 5 mins should a user define it during the creation of this alias
2. The service should redirect them to the original link through the alias
3. Users should be given the option to pick a short link for their URLs

### Non-Functional Requirements
1. System should be highly available.
2. URL redirection should happen in real-time with minimal latency
3. Shortened links should not be predictable

### Extended Requirements
1. Analytics (How many times a short alias was clicked etc)
2. Service should be accessible through REST APIs by other services
