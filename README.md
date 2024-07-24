# zenselect

ZenSelect is a lightweight JavaScript utility designed to enhance the user experience of Zendesk Help Center forms by making dropdown fields searchable.

## Features

- **Searchable Dropdowns**
- **Easy Integration**
- **Customizable**
- **Lightweight**

## Usage

Include the CDN link and call the `zenSelect` function with the ID of the field you want to make searchable.

```html
<script src="https://cdn.example.com/zenselect.min.js"></script>
<script>
    document.addEventListener('DOMContentLoaded', function() {
        zenSelect('dropdown-field-id', {
            placeholder: 'Type to search...',
        });
    });
</script>
