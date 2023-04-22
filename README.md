# FRONTEND-ASSIGNMENT

** it works perfectly fine for such inputs 
** the JSON should be of the following format


{
  "title": "Example Form",
  "type": "object",
  "properties": {
    "name": {
      "type": "string",
      "title": "Name",
      "description": "Please enter your name."
    },
    "email": {
      "type": "string",
      "title": "Email",
      "description": "Please enter your email address."
    },
    "age": {
      "type": "number",
      "title": "Age",
      "description": "Please enter your age.",
      "minimum": 18
    },
    "newsletter": {
      "type": "boolean",
      "title": "Subscribe to Newsletter",
      "description": "Do you want to receive our newsletter?",
      "default": true
    }
  }
}
