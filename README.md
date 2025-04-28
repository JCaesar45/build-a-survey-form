# Survey Form

A clean and accessible HTML survey form allowing users to submit basic personal information, preferences, and additional comments.

## Preview

> A simple and user-friendly survey form with input validation and structured fields.

## Project Description

This project builds a responsive and accessible survey form. Users can enter their personal details, select options, and submit their responses. Basic HTML form elements are organized with labels and fieldsets for better structure.

## Features

- **Title** and **Description** at the top of the form
- **Input Fields**:
  - Text field for **Name** (required)
  - Email field for **Email Address** (required, format validated)
  - Number field for **Age** (restricted between 18–100)
- **Dropdown Menu**:
  - Select between "United States" and "Canada"
- **Radio Buttons** for Gender selection (required)
- **Checkboxes** for Hobbies selection (optional)
- **Textarea** for additional comments
- **Submit Button** to send form data
- **Required Attributes** on necessary fields for form validation
- **Responsive Layout** with `meta viewport` for mobile compatibility
- **Semantic HTML** structure for better accessibility

## Code Structure

- `<!DOCTYPE html>`: Declares document type
- `<html lang="en">`: Language set to English
- `<head>`:
  - `<meta charset="UTF-8">` and `<meta name="viewport">` for proper rendering
  - `<title>`: Page title
- `<body>`:
  - `<h1>` and `<p>` to introduce the form
  - `<form id="survey-form">` with:
    - `<label>` and corresponding inputs (`<input>`, `<select>`, `<textarea>`)
    - `<fieldset>` elements grouping related inputs
    - `<button>` to submit

## How to Use

1. Open `index.html` in any modern browser.
2. Fill out each required field.
3. Click the **Submit** button to send the form data (can be connected to a backend if needed).

## Technologies Used

- HTML5
- Basic Form Validation (HTML attributes)

## Form Fields Overview

| Field               | Type              | Required | Validation                   |
|---------------------|-------------------|----------|-------------------------------|
| Name                | Text input         | Yes      | Must not be empty             |
| Email Address       | Email input        | Yes      | Must be a valid email format  |
| Age                 | Number input       | Yes      | Must be between 18 and 100    |
| Country             | Dropdown menu      | Yes      | Must select an option         |
| Gender              | Radio buttons      | Yes      | Must select one option        |
| Hobbies             | Checkboxes         | No       | Optional selections           |
| Additional Comments | Textarea           | No       | Optional free-text comments   |

---

Enhance user experience and easily gather information with this Survey Form! 📝
