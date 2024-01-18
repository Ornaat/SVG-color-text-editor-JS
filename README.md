# Ornaat template editor: a web application to edit color en typeface of a template
This project, named "Ornaat template Editor," is a web application that empowers users to personalize templates. Users can customize colors and modify the typeface. Real-time updates allow users to see the changes as they personalize their template. Once satisfied, users can submit their design by clicking "Send."

Upon clicking "Send," users will receive an email containing the final template as an image, along with details of the chosen colors and typeface. Additionally, an email (with the same content) will be sent to the administrator's email address.

### User features
- Choose from a variety of templates (SVG).
- Editing a template (SVG) real-time via:
   - Input hex codes to precisely define color values.
   - Enter CMYK values (which will be automatically converted to hex for realtime view).
   - Modify the typeface using the Google Font Library.
- Click the "Send" button to receive an email with the finalized template (PNG) and design details.

### Stretch goal user features
- Customize colors using a colorwheel for an intuitive experience.
- Frontend with "Send" button and a frontend without this button.

### Administrator Features
- Receive emails containing design details when users finalize their creations (triggered by user clicking "Send").
- Upload and manage a variety of templates (SVG) for users to choose from.
   - Manage templates: delete, private, rename.

### Stretch goal administrator features
- Backend database with all user submissions.
- Backend database manage options:
   - Labels: in process, done
   - Delete submissions

### Technologies
- Frontend: JavaScript, HTML, CSS
- Database: MySQL via phpMyAdmin
