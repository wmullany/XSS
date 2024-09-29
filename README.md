# XSS Example

This repository demonstrates a basic Cross-Site Scripting (XSS) vulnerability.

## Overview

In this example, user input is directly rendered in the HTML without proper sanitisation. An attacker can exploit this by injecting malicious scripts.

## How to Test

1. Clone the repository.
2. Open `index.html` in a web browser.
3. In the input field, enter the following:
   ```javascript
   <script>alert('XSS Attack!');</script>
