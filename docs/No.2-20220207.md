# <img src="https://avatars.githubusercontent.com/u/95163760?v=4" style="width:6%;"></img>VORG Open Source Magazine No. 2



<h2 id="Contact">Contact</h2>

Official Twitter: [VORGDAO](https://twitter.com/VORGDAO).
<br><br>



<h3 id="mpv"><a href="https://github.com/mpv-player/mpv">mpv</a></h3>

<span><strong><i class="fa fa-star">Star 17.7k</i> <i class="fa fa-eye">Watch 476</i> <i class="fa fa-code-fork">Fork 2.2k</i></strong></span>

mpv is a free (as in freedom) media player for the command line. It supports a wide variety of media file formats, audio and video codecs, and subtitle types.

This software is based on the MPlayer project. Before mpv existed as a project, the code base was briefly developed under the mplayer2 project.

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/mpv.jpeg?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="air"><a href="https://github.com/cosmtrek/air">air</a></h3>

<span><strong><i class="fa fa-star">Star 5.8k</i> <i class="fa fa-eye">Watch 47</i> <i class="fa fa-code-fork">Fork 404</i></strong></span>

Live reload for Go apps.

`Air` is yet another live-reloading command line utility for Go applications in development. Just `air` in your project root directory, leave it alone, and focus on your code.

NOTE: This tool has nothing to do with hot-deploy for production.

Features
- Colorful log output
- Customize build or binary command
- Support excluding subdirectories
- Allow watching new directories after Air started
- Better building process

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/air.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="minilisp"><a href="https://github.com/rui314/minilisp">minilisp</a></h3>

<span><strong><i class="fa fa-star">Star 1.1k</i> <i class="fa fa-eye">Watch 28</i> <i class="fa fa-code-fork">Fork 151</i></strong></span>

A readable lisp in less than 1k lines of C.

It supports
- integers, symbols, cons cells,
- global variables,
- lexically-scoped local variables,
- closures,
- if conditional,
- primitive functions, such as +, =, <, or list,
- user-defined functions,
- a macro system,
- and a copying garbage collector.

Example
```lisp
(println 3)  ; prints "3"
(+ 1 2 3)  ; -> 6
(define a (+ 1 2))
(+ a a)  ; -> 6
```

[Back to Top](#Contact)
<br><br>



<h3 id="termux-app"><a href="https://github.com/termux/termux-app">termux-app</a></h3>

<span><strong><i class="fa fa-star">Star 10.8k</i> <i class="fa fa-eye">Watch 739</i> <i class="fa fa-code-fork">Fork 1.5k</i></strong></span>

Termux is an Android terminal application and Linux environment.

Note that this repository is for the app itself (the user interface and the terminal emulation).

Features
- Enjoy the bash and zsh shells.
- Edit files with nano and vim.
- Access servers over ssh.
- Compile code with gcc and clang.
- Use the python console as a pocket calculator.
- Check out projects with git and subversion.
- Run text-based games with frotz.

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/termux-app.jpeg?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="arco-design"><a href="https://github.com/arco-design/arco-design">arco-design</a></h3>

<span><strong><i class="fa fa-star">Star 2.6k</i> <i class="fa fa-eye">Watch 26</i> <i class="fa fa-code-fork">Fork 226</i></strong></span>

A comprehensive React UI components library based on the [Arco Design](https://arco.design/) system.

Features
- With more than 60 crafted components that you can use out of the box.
- Extensive design tokens can be customized to build your own theme.
- [Material market](https://arco.design/material/) provides a one-stop solution for materials management.
- All components are written in TypeScript so it's type friendly.

```typescript
import React from 'react';
import ReactDOM from 'react-dom';
import { Button } from '@arco-design/web-react';
import '@arco-design/web-react/dist/css/arco.css';

function App() {
  return (
    <Button type='secondary'>
      Hello World
    </Button>
  );
}

ReactDOM.render(<App />, document.getElementById('app'));
```
<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/arco-design.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="context-note"><a href="https://github.com/betterRunner/context-note">context-note</a></h3>

<span><strong><i class="fa fa-star">Star 424</i> <i class="fa fa-eye">Watch 8</i> <i class="fa fa-code-fork">Fork 36</i></strong></span>

A note-taking chrome extension: taking notes on the web with their context.

Features
- 📝 Notebook, reviewing notes on a book, while jumping back to the context for details.
- 🏷️ Tagbook, manage the notes neatly with a handy tag system.
- ⌨️ Rich text editor: embed quill as the rich text editor.

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/context-note.gif?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="prisma"><a href="https://github.com/prisma/prisma">prisma</a></h3>

<span><strong><i class="fa fa-star">Star 20.4k</i> <i class="fa fa-eye">Watch 187</i> <i class="fa fa-code-fork">Fork 716</i></strong></span>

Prisma is a next-generation ORM that consists of these tools:

- [Prisma Client](https://www.prisma.io/docs/concepts/components/prisma-client): Auto-generated and type-safe query builder for Node.js & TypeScript
- [Prisma Migrate](https://www.prisma.io/docs/concepts/components/prisma-migrate): Declarative data modeling & migration system
- [Prisma Studio](https://github.com/prisma/studio): GUI to view and edit data in your database

Prisma Client can be used in any Node.js or TypeScript backend application (including serverless applications and microservices). This can be a [REST API](https://www.prisma.io/docs/understand-prisma/prisma-in-your-stack/rest), a [GraphQL API](https://www.prisma.io/docs/understand-prisma/prisma-in-your-stack/graphql) a gRPC API, or anything else that needs a database.

```javascript
import { PrismaClient } from '@prisma/client'

const prisma = new PrismaClient()

// A `main` function so that you can use async/await
async function main() {
  const allUsers = await prisma.user.findMany({
    include: { posts: true },
  })
  // use `console.dir` to print nested objects
  console.dir(allUsers, { depth: null })
}

main()
  .catch((e) => {
    throw e
  })
  .finally(async () => {
    await prisma.$disconnect()
  })
```

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/prisma.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="rumps"><a href="https://github.com/jaredks/rumps">rumps</a></h3>

<span><strong><i class="fa fa-star">Star 2.6k</i> <i class="fa fa-eye">Watch 46</i> <i class="fa fa-code-fork">Fork 167</i></strong></span>

Ridiculously Uncomplicated macOS Python Statusbar apps.

```python
import rumps

class AwesomeStatusBarApp(rumps.App):
    @rumps.clicked("Preferences")
    def prefs(self, _):
        rumps.alert("jk! no preferences available!")

    @rumps.clicked("Silly button")
    def onoff(self, sender):
        sender.state = not sender.state

    @rumps.clicked("Say hi")
    def sayhi(self, _):
        rumps.notification("Awesome title", "amazing subtitle", "hi!!1")

if __name__ == "__main__":
    AwesomeStatusBarApp("Awesome App").run()
```

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/rumps.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="vienna-rss"><a href="https://github.com/ViennaRSS/vienna-rss">vienna-rss</a></h3>

<span><strong><i class="fa fa-star">Star 1.5k</i> <i class="fa fa-eye">Watch 58</i> <i class="fa fa-code-fork">Fork 222</i></strong></span>

[Vienna](https://www.vienna-rss.com/) is an RSS/Atom reader for macOS.

Vienna can connect directly to the websites you want to track. Additionally or alternatively, you can also sync with a server supporting the [Open Reader API](http://rss-sync.github.io/Open-Reader-API/rssconsensus/) (an adaptation of the now deceased Google Reader API). Vienna has been successfully tested with BazQux.com, FreshRSS.org, FeedHQ.org, InoReader.com and TheOldReader.com.

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/vienna-rss.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="tiler"><a href="https://github.com/nuno-faria/tiler">tiler</a></h3>

<span><strong><i class="fa fa-star">Star 5k</i> <i class="fa fa-eye">Watch 57</i> <i class="fa fa-code-fork">Fork 318</i></strong></span>

Build images with images.

Tiler is a tool to create an image using all kinds of other smaller images (tiles). It is different from other mosaic tools since it can adapt to tiles with multiple shapes and sizes (i.e. not limited to squares).

An image can be built out of circles, lines, waves, cross stitches, legos, minecraft blocks, paper clips, letters, ... The possibilities are endless!

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/tiler.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="tabby"><a href="https://github.com/Eugeny/tabby">tabby</a></h3>

<span><strong><i class="fa fa-star">Star 29.3k</i> <i class="fa fa-eye">Watch 357</i> <i class="fa fa-code-fork">Fork 1.7k</i></strong></span>

Tabby (formerly Terminus) is a highly configurable terminal emulator, SSH and serial client for Windows, macOS and Linux

- Integrated SSH and Telnet client and connection manager
- Integrated serial terminal
- Theming and color schemes
- Fully configurable shortcuts and multi-chord shortcuts
- Split panes
- Remembers your tabs
- PowerShell (and PS Core), WSL, Git-Bash, Cygwin, MSYS2, Cmder and CMD support
- Direct file transfer from/to SSH sessions via Zmodem
- Full Unicode support including double-width characters
- Doesn't choke on fast-flowing outputs
- Proper shell experience on Windows including tab completion (via Clink)
- Integrated encrypted container for SSH secrets and configuration
- SSH, SFTP and Telnet client available as a web app (also self-hosted).

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/tabby.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="Simula"><a href="https://github.com/SimulaVR/Simula">Simula</a></h3>

<span><strong><i class="fa fa-star">Star 2.2k</i> <i class="fa fa-eye">Watch 60</i> <i class="fa fa-code-fork">Fork 59</i></strong></span>

[Simula](https://simulavr.com/) is a VR window manager for Linux that runs on top of [Godot](https://godotengine.org/). It takes less than 1 minute to install.

Simula is officially compatible with SteamVR headsets equipped with Linux drivers (e.g. HTC Vive, HTC Vive Pro, & Valve Index). We have also added experimental support to OpenXR headsets that have Monado drivers (e.g. North Star, OSVR HDK, and PSVR). Some people have gotten the Oculus Rift S to run Simula via OpenHMD, though we have not officially tested this ourselves.

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/Simula.gif?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="koreader"><a href="https://github.com/koreader/koreader">koreader</a></h3>

<span><strong><i class="fa fa-star">Star 9.9k</i> <i class="fa fa-eye">Watch 299</i> <i class="fa fa-code-fork">Fork 971</i></strong></span>

KOReader is a document viewer primarily aimed at e-ink readers.

Features
- portable: runs on embedded devices (Cervantes, Kindle, Kobo, PocketBook, reMarkable), Android and Linux computers. Developers can run a KOReader emulator in Linux and MacOS.
- 
- multi-format documents: supports fixed page formats (PDF, DjVu, CBT, CBZ) and reflowable e-book formats (EPUB, FB2, Mobi, DOC, CHM, TXT). Scanned PDF/DjVu documents can also be reflowed with the built-in K2pdfopt library.
- 
- full-featured reading: multi-lingual user interface with a highly customizable reader view and many typesetting options. You can set arbitrary page margins, override line spacing and choose external fonts and styles. It has multi-lingual hyphenation dictionaries bundled into the application.
- 
- integrated with calibre (search metadata, receive ebooks wirelessly, browse library via OPDS), Wallabag, Wikipedia, Google Translate and other content providers.
- 
- optimized for e-ink devices: custom UI without animation, with paginated menus, adjustable text contrast, and easy zoom to fit content or page in paged media.
- 
- extensible: via plugins
- 
- fast: on some older devices, it has been measured to have less than half the page-turn delay as the built in reading software.

- and much more: look up words with StarDict dictionaries / Wikipedia, add your own online OPDS catalogs and RSS feeds, over-the-air software updates, an FTP client, an SSH server, …

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/koreader.jpeg?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="cutter"><a href="https://github.com/rizinorg/cutter">cutter</a></h3>

<span><strong><i class="fa fa-star">Star 10.8k</i> <i class="fa fa-eye">Watch 284</i> <i class="fa fa-code-fork">Fork 860</i></strong></span>

Cutter is a free and open-source reverse engineering platform powered by [rizin](https://github.com/rizinorg/rizin). It aims at being an advanced and customizable reverse engineering platform while keeping the user experience in mind. Cutter is created by reverse engineers for reverse engineers.

- Supports multiple languages and themes
- Binary search
- Hex editor
- Python scripts and plugins
- Support Linux, macOS, Windows

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/cutter.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



<h3 id="wsa_pacman"><a href="https://github.com/alesimula/wsa_pacman">wsa_pacman</a></h3>

<span><strong><i class="fa fa-star">Star 1.1k</i> <i class="fa fa-eye">Watch 21</i> <i class="fa fa-code-fork">Fork 176</i></strong></span>

A GUI package manager and package installer for Windows Subsystem for Android (WSA).

Currently provides a double-click GUI installer for .apk files that shows app information (package, icon, version and permissions), allows normal installations as well as upgrades and downgrades.

The app additionally provides a button to open Android settings and one to open the "Manage Applications" Android settings page, from which you can uninstall or disable applications and grant or revoke permissions.

<p align="center"><img src='https://github.com/VorgContract/VorgMagazine/blob/master/assets/No.2/wsa_pacman.png?raw=true' style="max-width:80%; max-height=80%;"></img></p>

[Back to Top](#Contact)
<br><br>



Official Twitter: [VORGDAO](https://twitter.com/VORGDAO).
