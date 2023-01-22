# Journal with Local Storage V2

Use your browser as a journal (entries can only be viewed locally).
V2 now has an image upload facility.
**Note**

- Images must be stored in the `images` folder.
  - Image functionality will only work locally (therefore, no Git Page).

## Features

- **Create an entry**:
  - Add date (optional)
  - add heading (required)
  - add image (optional) **NEW**
    - remove image before publishing
  - add text (required).
    - Show error messages if required fields not filled.
  - Publish: saves to local storage, or
  - cancel.
- **Edit an entry**:
  - heading,
  - image,
  - text.
    - Save to local storage.
- **Delete an entry**:
  - deletes from local storage.

## HTML

- `template` used for journal entry item.
- `contenteditable` used for entry editing.

## Javascript

- ES6 (no transpilation to ES5)
- Unique local storage key, `JOURNAL_IMAGE_ENTRIES-LIST-entries`:
  - If journal entries are deleted, no other local storage will be affected.

## CSS

- `grid` used for page layout.
- `flexbox` used for element layout.
- `CSS variables` used for common properties.

## Testing

- Tested on:
  - Windows 10
    - Chrome
    - Firefox
    - Microsoft Edge

## Acknowledgements

- The code is an extended version of [Journal with Local Storage](https://github.com/chrisnajman/journal-with-local-storage).
