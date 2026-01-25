# jstriker87.github.io

# James Cumming-Bart –  Portfolio

I am a Junior Backend Engineer with a Computer Science BSc (2:1) and I have strong interest in making well-structured systems.  
I enjoy working on backend services abddd cross-platform tools that solve real problems.

I have over 10 years of experience delivering technical telecom projects in production environments, and I have skills with modern software engineering practices using Go, Python, SQL, and REST APIs.

GitHub: https://github.com/jstriker87  

---

## 🔧 Core Skills

- **Languages:** Go, Python, C, Java, SQL, HTML, CSS  
- **Other:** JavaScript, C#  
- **Frameworks:** React, Express, Node  
- **Tools:** Git, Docker, Linux, CI/CD  
- **Concepts:** REST APIs, Domain Modelling, OOP, Data Structures, Relational Databases, Agile  

---

## 🚀 Featured Projects

### 🗂 Flashcards – Revision Browser App  
**Go, HTML, Backend Architecture**  
[https://github.com/jstriker87/Go-Flashcards](https://github.com/jstriker87/Go-Flashcards)

A revision flashcard system designed around a clean backend service and simple frontend.

**Highlights:**
- Designed and implemented a backend service in Go
- Created a Domain-driven structure for flashcards, as well as to track progress
- Lightweight HTML frontend
- Focuses on maintainability, clarity, and UI feedback
- Built with portability and long-term maintainability in mind

Features:
- Backend service design
- Separation of concerns
- Practical Go engineering
- Data modelling and application flow

---

### 🎬 mpv Progress Sync – Cross-Platform Media Progress Sync  
**Lua, Cross-Platform Scripting, Systems Design**  
[https://github.com/jstriker87/mpv-progress-sync-cross-platform](https://github.com/jstriker87/mpv-progress-sync-cross-platform)

A cross-platform script that synchronises video playback progress across devices for mpv and mpv-android.

**Problem:**
mpv saves progress based on file paths, meaning:
- Moving files breaks progress
- Syncing across devices is impossible

**Solution:**
- Progress is identified using file **size + duration**
- Stored using hashed data for privacy
- Works on:
  - Linux
  - Windows
  - Android
- Designed for use with sync tools like Syncthing

**Highlights:**
- Solves a real usability problem
- Cross-platform engineering
- Portable configuration
- Secure file naming through hashing
- Clean, well-documented setup instructions

Features:
- Cross-platform compatibility
- Script portability
- Real-world problem solving

---

### 📂 File-Processing-Pipeline – A file processing backend written in Go (WIP)
**Go,Data Management, Productivity**  
[https://github.com/jstriker87/File-Processing-Pipeline](https://github.com/jstriker87/File-Processing-Pipeline)

A backend designed for storing files along with descriptions, which can be used .

**Problem:**
Sometimes when you have an important file, it takes time to search for it in the future
- There is no additional metadata to search for a document, other than knowiong certain keywords in the file


**Solution:**
 - The File-Processing-Ppipeline solvess this problem by allowing users to upload filees to their chosen location along with a description. This description can then be searched to allow eeasier location of files
 - The backend system exposes four endpoints
    /status - (GET) - Shows the current storage usage of your ‘uploads’ folder

    /upload - (POST) Allows users to upload a file of up to a certain size (The maximum filesize of files can be set in the configuration (see Configuration section)
        Alongside the file you can provide a description as a json with the key of 'description'. Foe example {"description": "My current CV 2026"}

    /search - (GET) - Allows users to search for words in the description provided with the file. You can also search inside the files themselves if they are encoded using UTF-8
        An example search of 'Apples' is http://localhost:8080/search?sq=Apples
        Example files that use UTF-8 encoding and therefore its file contents can also be searched) are:
            Web Files: .html, .css, .js, .xml
            Text & Data Files: .txt, .csv, .json, .md (Markdown)
            Configuration & Scripts: .py (Python), .ini, .yaml
        The search results provided will provide you with a direct link from the /download endpoint to download the files in the search results

    /download - (GET) - Allows users to download a file. The endpoint uses the name of the folder where your file is located
-
**Highlights:**
- Solves a context and understanding problem
- Allows you to search and find files using your own reference information / metadata
- Designed to be self hosted.
- Can be implemented to any program, page or script that can send POST / GET requests, and unmarshall json data

---

## 🧠 About Me

Before completing my Computer Science degree, I spent over a decade working in telecoms provisioning, technical coordination, and infrastructure projects.  
That background gave me:

- A strong production mindset  
- Clear communication and documentation habits  
- Comfort working in complex technical environments  

Now I combine that experience with modern backend development skills.

I am seeking a **Junior Backend Engineer** role where I can:
- Build reliable services
- Learn from experienced engineers
- Contribute meaningfully to real production systems

---

## 📫 Contact

- GitHub: https://github.com/jstriker87  
- Email: jbart1@gmail.com  
