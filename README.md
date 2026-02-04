# 4Th Of July Offers

Professional marketing email for announcing special offers on the 4th of July for retail and travel & tourism industries.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Travel & Tourism, Retail
- **Message Type:** Marketing
- **Tags:** sale, discount, offers, 4thofjuly

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/4th-of-july-offers.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/4th-of-july-offers/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.4th-of-july-offers',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
