# Hi, I'm Andrew Chelimo

**BSE in Artificial Intelligence @ UPenn | Android and Kotlin Multiplatform Developer | Android Developer @ Penn Labs**

[LinkedIn](https://linkedin.com/in/da-chelimo) | [Portfolio](https://da-chelimo.netlify.app) | chelimo@engineering.upenn.edu

<br>

## About Me
I build Android and Kotlin Multiplatform apps and care about the details that users feel: startup time, memory, crash rates, offline behavior, and clean architecture that lets a team keep shipping. I have been writing Kotlin for 5 years, and today I work on Penn Mobile (4,000+ monthly active users) as part of Penn Labs, where I own notifications and home-screen widgets. I also pair that with AI engineering, from vector-search recommendation pipelines to LLM routing and eval harnesses.

Outside of code: cycling, volunteering, table tennis, and nature walks.

<br>

## Skills
**Languages:** Kotlin, Java, Swift, Python, SQL, C, JavaScript <br>
**Android and KMP:** Jetpack Compose, Compose Multiplatform, Kotlin Multiplatform, MVVM and Clean Architecture, Coroutines and Flow, Hilt, Koin, Room, Retrofit, JUnit <br>
**Backend and Cloud:** FastAPI, Ktor, PostgreSQL, Supabase (Auth, Edge Functions), AWS (RDS, S3), Firebase (Auth, Crashlytics, FCM) <br>
**AI Engineering:** Claude API, RAG, CLIP embeddings, pgvector, multi-model routing and eval harnesses, agentic dev workflows (Claude Code, Codex) <br>
**Certifications:** TripleByte Certified Android Engineer <br>

<br>

## Featured Projects

### TikTok Clone - Video Recommendation Engine
A short-video app with a content-based recommendation pipeline, built end to end: a Kotlin Android client backed by a Python service that ranks videos by visual similarity.

- **Features:** Vertical video feed, personalized recommendations driven by what a user watches
- **How it works:** Video frames are embedded with CLIP, stored in PostgreSQL with pgvector, and searched with an HNSW index for fast nearest-neighbor retrieval
- **Tech stack:** Kotlin, Jetpack Compose, Python, FastAPI, CLIP, PostgreSQL, pgvector (HNSW)

<br>

### Penn Mobile - Production App at Penn Labs
The official app for Penn students, built and maintained by Penn Labs. I have been on the Android team since September 2025 and own notifications and home-screen widgets.

- **Stability:** Cut app crashes by 30% by tracing a lifecycle crash in Firebase Crashlytics (150+ users affected) and decoupling network calls from the UI
- **Performance:** Reduced a screen's freeze time by 89% (1.76s to 189ms) and memory use by 72 MB by profiling in Android Studio and decoding downsized images asynchronously with Coil
- **Migration:** Led the incremental XML-to-Jetpack Compose migration of 5 screens without freezing feature work
- **Architecture and quality:** Refactored two monolithic Fragments into Clean Architecture with MVVM, UDF, and Hilt; raised test coverage on two core features from 0% to 80% with JUnit

<br>

## More Projects

- **Whisper:** Offline-first real-time chat app with media sharing, Stories, and edit/unsend messages (Firebase, Koin)
- **Evenly:** Bill-splitting app built with Kotlin Multiplatform and Compose Multiplatform
- **Sky Weather:** Weather app with 1,000+ downloads and a 5.0 rating on Google Play (Room, Retrofit, Hilt, WorkManager)
- **Trecipe:** Recipe discovery app on Google Play with offline caching and infinite-scroll search (Kotlin, Room)
- **SHIFT:** Web, iOS, and Android staffing platform for 105 Penn Housing front-desk workers, with a Claude-powered RAG support agent, pitched to Penn Housing leadership for a pilot

<br>

## Get in Touch
I am looking for Android and mobile engineering internships. Reach me on [LinkedIn](https://linkedin.com/in/da-chelimo) or at chelimo@engineering.upenn.edu.
