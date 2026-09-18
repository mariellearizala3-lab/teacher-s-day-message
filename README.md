# teacher-s-day-message
Happy Teacher's Day Message

Teacher's Day Tribute Website

A responsive and interactive Teacher's Day greeting card created using HTML, CSS, and JavaScript. The website presents a digital envelope that opens into a heartfelt message, gratitude cards, animations, and optional background music.

Project Features

Interactive envelope opening animation

Teacher's Day greeting card design

Personalized teacher and student names

Animated typewriter message

Flip-style gratitude cards

Send-a-hug button with confetti animation

Replay button to restart the greeting

Scroll controls for mobile and desktop

Responsive layout for different screen sizes

Accessibility support through keyboard controls and ARIA labels

Optional audio/music support

Project Files

Teacher-Day-Website/
│
├── teacher-day.html
├── teacher-music.mp3
└── README.md

File Description

teacher-day.html – Main webpage containing the structure, styling, animations, and JavaScript functionality.

teacher-music.mp3 – Optional music file used as background music.

README.md – Project documentation and usage instructions.

Requirements

You only need:

A modern web browser such as Google Chrome, Microsoft Edge, or Mozilla Firefox

The HTML file

The MP3 file, if you want to use background music

No server or internet connection is required for the core webpage.

How to Run the Website

Download or copy all project files into one folder.

Make sure the HTML and MP3 files are in the same folder.

Confirm that the music filename matches the filename used in the HTML source.

Open teacher-day.html by double-clicking it.

Click or tap the envelope to open the Teacher's Day card.

Use the available buttons to interact with the greeting card.

Adding the Music

Place the MP3 file in the same folder as the HTML file. Example:

teacher-day.html
teacher-music.mp3

The audio element should reference the correct filename:

<audio id="teacherMusic" loop>
    <source src="teacher-music.mp3" type="audio/mpeg">
    Your browser does not support audio.
</audio>

Important Notes

The filename in the src attribute must exactly match the MP3 filename.

Some browsers restrict automatic audio playback.

If the music does not start automatically, use a button that starts playback after a user click.

Keep the MP3 file in the same directory unless you update the file path in the HTML.

Customizing the Content

Open teacher-day.html in a code editor and locate the editable content section.

You can update:

Teacher's name

Student's name

Short greeting message

Personal message

Gratitude card titles and descriptions

Example:

const TEACHER_NAME = "Dear Teacher";
const STUDENT_NAME = "Your Student";

Replace the values with your preferred names.

Browser Compatibility

The project is designed for modern browsers that support:

HTML5

CSS3

JavaScript

Web Audio API

CSS animations and transitions

Troubleshooting

Music does not play

Check that the MP3 file is in the correct folder.

Check that the filename matches the HTML source.

Try clicking the music button.

Verify that your browser is not muted.

The page design looks incorrect

Make sure the complete HTML file was copied.

Open the file using a modern browser.

Refresh the page after saving changes.

Buttons do not respond

Open the browser's developer console and check for JavaScript errors.

Confirm that the HTML element IDs match the JavaScript references.

Ensure that the complete script section is present.

Credits

This project was created as a digital Teacher's Day tribute to express appreciation, gratitude, and respect for teachers.

License

This project is intended for educational and personal use. Confirm that you have the appropriate permission to use any third-party music included with the project
