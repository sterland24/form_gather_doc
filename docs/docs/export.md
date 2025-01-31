# Exporting Form Data as JSON

## Overview
The admin panel allows exporting collected form responses in **JSON format** with a single click. This feature makes it easy to integrate form data with other tools and systems.

## How to Export Data as JSON
1. **Navigate to the Admin Panel**  
   - Go to the **Responses** section.
2. **Select the Form**  
   - Choose the form whose responses you want to export.
3. **Click the Export Button**  
   - Click the **Export as JSON** button.
   - The system will generate a JSON file containing all collected responses.

## Example JSON Output
After exporting, the JSON file may look like this:

```json
{
    "form_title": "User Feedback Form",
    "form_id": "12345",
    "responses": [
        {
            "id": "001",
            "timestamp": "2025-01-30T10:15:00Z",
            "data": {
                "name": "John Doe",
                "email": "john.doe@example.com",
                "rating": "5",
                "comments": "Great service!"
            }
        },
        {
            "id": "002",
            "timestamp": "2025-01-30T10:30:00Z",
            "data": {
                "name": "Jane Smith",
                "email": "jane.smith@example.com",
                "rating": "4",
                "comments": "Very satisfied with the support."
            }
        }
    ]
}
```