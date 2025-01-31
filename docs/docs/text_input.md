# Text Input Field

## Overview
The **Text Input Field** allows users to enter custom text responses in a form. This field can be configured with validation rules using **regular expressions (regex)** to ensure correct input formats.

## Usage Example
Use a **text input** field when collecting information such as names, emails, or custom responses.

## Example: Email Validation with Regex
To ensure users enter a valid email address, use the following regex pattern:

```regex
^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$
```

### Example Form Configuration
```json
{
    "type": "text",
    "label": "Email Address",
    "placeholder": "Enter your email",
    "validation": {
        "regex": "^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\\.[a-zA-Z]{2,}$",
        "error_message": "Please enter a valid email address."
    }
}
```

This configuration ensures that only properly formatted email addresses are accepted.
