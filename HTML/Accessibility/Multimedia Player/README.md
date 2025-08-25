# Multimedia Player

A simple HTML page created to demonstrate **audio and video playback** using semantic structure and accessibility considerations.

## Structure

- **Title (`<h1>`)**: page title indicating multimedia content.
- **Audio Section (`<section>` + `<audio>`)**: plays an audio file with descriptive `aria-label` for accessibility.
- **Video Section (`<section>` + `<video>`)**: plays a video file with controls, subtitles (`<track>`), and `aria-label` for screen reader users.
- **Transcript Section (`<section>` + `<p>`)**: text transcription of the video content for accessibility and reference.

## Best Practices Applied

- **Semantic HTML**: use of `<section>`, `<h2>`, `<audio>`, `<video>`, and `<p>` for clear content hierarchy.
- **Accessibility (a11y)**:
  - `aria-label` on audio and video elements to describe content for screen readers.
  - Subtitles provided via `<track>` with descriptive `label`.
  - Transcription available as text for users with hearing impairments.
- **Readability**: content structured in distinct sections for audio, video, and transcript.

## How to Run

Open the `index.html` file in any modern web browser.
