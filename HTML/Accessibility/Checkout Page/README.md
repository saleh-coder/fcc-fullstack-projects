# Checkout Page

A simple HTML project demonstrating the creation of an **accessible checkout page**.

## Structure

- **Sections with `role="region"` and `aria-labelledby`**: improve accessibility by allowing screen readers to identify each area.
- **Cart**: includes a sample item with image and descriptive `alt` text.
- **Payment form**:
  - Field for cardholder name.
  - Field for card number with validation (`pattern` for 16 digits).
  - Submit button to finalize payment.

## Best Practices Applied

- **Semantic HTML**: use of `<main>`, `<section>`, `<h2>`.
- **Accessibility (a11y)**:
  - `aria-labelledby` to link headings with regions.
  - Descriptive `alt` for images.
  - Proper `label` associations with form inputs.
- **Form validation**:
  - `required` on mandatory fields.
  - `pattern` and `inputmode` to restrict card number input.

## How to Run

Open the `index.html` file in any modern browser.
