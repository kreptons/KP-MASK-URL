# Kreptons URL Masker

**Kreptons URL Masker** is a bash script designed to obscure phishing URLs, making them appear innocuous and legitimate. This tool shortens a given phishing URL and masks it with a user-provided domain and optional social engineering words to create a convincing facade.

## Features

- **URL Validation:** Ensures the provided URLs start with `http` or `https`.
- **URL Shortening:** Utilizes the `is.gd` URL shortener for concise URLs.
- **Custom Masking:** Allows masking of shortened URLs with a user-provided domain and optional social engineering keywords.
- **User Guidance:** Offers clear prompts and error messages to guide the user through the process.

## Getting Started

### Prerequisites

Before running the script, ensure you have the following installed on your Linux system:

- Bash (Unix shell)
- cURL (command line tool for transferring data with URLs)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/kreptons/KP-MASK-URL.git
   cd kreptons-url-masker
