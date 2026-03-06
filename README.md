# LyricsFinder
ʟʏʀɪᴄs ꜰɪɴᴅᴇʀ ɪs ᴀ sɪᴍᴘʟᴇ ᴡᴇʙ ᴀᴘᴘ ᴛᴏ sᴇᴀʀᴄʜ ᴀɴᴅ ʀᴇᴀᴅ sᴏɴɢ ʟʏʀɪᴄs ɪɴsᴛᴀɴᴛʟʏ. ᴜsᴇʀs ᴄᴀɴ ᴇɴᴛᴇʀ ᴀ sᴏɴɢ ᴛɪᴛʟᴇ ᴀɴᴅ ᴀʀᴛɪsᴛ ɴᴀᴍᴇ ᴛᴏ ɢᴇᴛ ᴀᴄᴄᴜʀᴀᴛᴇ ʀᴇsᴜʟᴛs. ɪᴛ sᴜᴘᴘᴏʀᴛs ʙᴏᴛʜ ᴘʟᴀɪɴ ʟʏʀɪᴄs ᴀɴᴅ sʏɴᴄᴇᴅ ʟʏʀɪᴄs, ᴍᴀᴋɪɴɢ ɪᴛ ᴇᴀsʏ ᴛᴏ ꜰᴏʟʟᴏᴡ ᴀʟᴏɴɢ ᴡɪᴛʜ ᴛʜᴇ sᴏɴɢ. ᴛʜᴇ ᴡᴇʙsɪᴛᴇ ʜᴀs ᴀ ᴄʟᴇᴀɴ, ʀᴇsᴘᴏɴsɪᴠᴇ ᴅᴇsɪɢɴ ᴀɴᴅ ɪs ᴇᴀsʏ ᴛᴏ ᴜsᴇ.

# LRCFINDER

LRCFINDER is a sleek, frontend-only web application that allows you to effortlessly search for and display song lyrics. Built with HTML, CSS, and Vanilla JavaScript, it features a modern, responsive design with glassmorphism elements and smooth animations.

## Features

- **Search by Song & Artist:** Find lyrics accurately by providing the song title and optionally the artist name.
- **Synced & Plain Lyrics:** View both plain text lyrics and time-synced lyrics (when available) switched easily via tabs.
- **Modern UI:** A visually pleasing dark theme, featuring animated background blobs, glassmorphism UI components, and modern typography (`Outfit` font).
- **Copy to Clipboard:** One-click copy functionality to quickly grab the lyrics.
- **Responsive Design:** Works beautifully across devices, from desktops to mobile phones.
- **API Integration:** Utilizes the [LRCLIB API](https://lrclib.net/) to fetch accurate and fast results.
- **Frontend Only:** No backend required! Can be hosted anywhere static files are supported (e.g., GitHub Pages).

## Installation & Usage

Since this is a frontend-only project without any build steps or backend dependencies, getting started is incredibly simple:

1. **Clone or Download** the repository to your local machine.
2. **Open `index.html`** in your preferred web browser.

That's it!

## How to use

1. Enter the **Song Name** in the designated input field.
2. (Optional but recommended) Enter the **Artist Name** for enhanced accuracy.
3. Click the **Search** button or press `Enter`.
4. Read or copy your lyrics directly from the app. Use the tabs to switch between Synced and Plain lyrics if available.

## Technologies Used

- **HTML5:** Semantic structure.
- **CSS3:** Custom styling, CSS Variables, Glassmorphism, animations, and responsive media queries.
- **Vanilla JavaScript (ES6+):** DOM manipulation, event handling, and asynchronous API fetching using the Fetch API.
- **FontAwesome:** For intuitive UI icons.
- **Google Fonts:** The `Outfit` font family.

## API Reference

This project is powered by [LRCLIB](https://lrclib.net/), an open-source API for fetching lyrics. 

- `/api/get`: Used for exact matches when both Track Name and Artist Name are provided.
- `/api/search`: Used as a fallback and general search for finding closest matching tracks.

## License

This project is open-source and free to use.
