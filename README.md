# SharePad-Lite
[SharePad Lite live (demo)](https://raw.githack.com/dayeggpi/SharePad-Lite/main/index.html)

A minimalist sharing tool that lives entirely in your browser and stores everything in the URL hash.<br/>

<img width="1910" height="149" alt="waterfox_O2RPqDEqHw" src="https://github.com/user-attachments/assets/2edbdb65-197f-4d60-908e-ed30180edba9" />


# Features

- 📝 A text area that you can easily share to anyone
- 🗜️ Compression magic - Your text gets compressed with deflate
- 🔗 URL storage - Share your notes by copying the URL
- 💾 Auto-save
- 📱 Mobile friendly - Type your manifesto on the go
- 🎯 No backend - Zero servers were harmed in the making of this app
- 💕 Style – Customize the look with CSS via DevTools
- 🌓 Dark or Light mode - to allow you to chose your color scheme preference
- QR code generation of the text and for links
- Markdown support
- Export to txt file
- Have multiple notes and manage the list more easily
    

# How to use

- Open https://raw.githack.com/dayeggpi/SharePad-Lite/main/index.html or save index.html on your server (adjust manifest.json `start_url` and `scope` to your needs in that case)
- Open the page, type any text
- Share the link or the QR code of the link and enjoy !

# Pro tips

- Start your document with # Title to set a custom page title and check out the markdown tips
- Your data lives in localStorage AND the URL. Double the fun!
- Add a `style` attribute to the `<article>` tag via DevTools (F12), it will also be shared !
```
    background: url(//raw.githubusercontent.com/dayeggpi/SharePad-Lite/main/pixel.png);
    font-family: "Comic Sans MS", "Comic Sans", cursive;
    font-size: 26px;
    color: red;
```
<img width="850" height="206" alt="530555106-d46b0b49-dba5-4d4f-bee2-a2646d4a2633" src="https://github.com/user-attachments/assets/1b78fbbf-c08d-481f-835c-c99e1b8d6ead" />


# Inspiration

Inspired by the amazing [textarea](https://github.com/antonmedv/textarea).<br/>

# Important note

⚠️ Any change in the note will generate a new link. <br/>
⚠️ Careful when sharing links, as data lives in the URL forever ! 
