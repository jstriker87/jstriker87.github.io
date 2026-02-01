# James Cumming-Bart – Portfolio

I am a Junior Backend Engineer with a Computer Science BSc (2:1), and I have strong interest in making well-structured systems.  
I enjoy working on backend services and cross-platform tools that solve real problems.

I have over 10 years of experience delivering technical telecom projects in production environments, and I am skilled in modern software engineering practices using Go, Python, SQL, and REST APIs.

[My GitHub](https://github.com/jstriker87)

---

## 🔧 Core Skills

- **Languages:** Go, Python, C, Java, SQL, HTML, CSS
- **Other:** JavaScript, C#
- **Frameworks:** React, Express, Node
- **Tools:** Git, Docker, Linux, CI/CD
- **Concepts:** REST APIs, Domain Modelling, OOP, Data Structures, Relational Databases, Agile

---

## 🚀 Featured Projects

### 🗂 [Flashcards – Revision Browser App](https://github.com/jstriker87/Go-Flashcards)

**Go, HTML, Backend Architecture**

A revision flashcard system designed around a clean backend service and simple frontend.

**Highlights:**

- Designed and implemented a backend service in Go.
- Created a domain-driven structure for flashcards, as well as to track progress.
- Lightweight HTML frontend.
- Focuses on maintainability, clarity, and UI feedback.
- Built with portability and maintainability in mind.

Features:

- Backend service design.
- Separation of concerns.
- Practical Go engineering.
- Data modelling and application flow.

---

### 🎬 [mpv Progress Sync – Cross-Platform Media Progress Sync](https://github.com/jstriker87/mpv-progress-sync-cross-platform)

**Lua, Cross-Platform Scripting, Systems Design**

A cross-platform script that synchronises video playback progress across devices for mpv and mpv-android.

The problem with mpv's progress tracking is that is uses absolute file paths, so files can't be moved and cross-device sync is made inconvenient.

**Highlights:**

- Solves a real usability problem.
- Cross-platform engineering.
- Portable configuration.
- Privacy-maintaining storage via hashing.
- Clean, well-documented setup instructions.

Solution:

- Progress is identified using file **size + duration**.
- Stored using hashed data for privacy.
- Works on:
  - Linux
  - Windows
  - Android
- Designed for use with sync tools like Syncthing.

---

### 📂 [File-Processing-Pipeline – A file processing backend written in Go (WIP)](https://github.com/jstriker87/File-Processing-Pipeline)

**Go, Data Management, Productivity**

A backend designed for storing files along with descriptions, which can be used .

Finding files by their name and sometimes contents can lead to disappointment. By labelling the file with relevant metadata, you're more likely to find what you're looking for.

**Highlights:**

- Solves a context and understanding problem.
- Allows you to search and find files using your own reference information / metadata.
- Designed to be self hosted.
- Can be implemented to any program, page or script that can send POST / GET requests, and unmarshall json data.

Solution:

- The File-Processing-Ppipeline solvess this problem by allowing users to upload filees to their chosen location along with a description. This description can then be searched to allow eeasier location of files
- The backend system exposes four endpoints:
  - GET /status \
    - Shows the current storage usage stats of the upload directory.
  - POST /upload \
    - Uploads a file.
    - Limits file size to a configurable value.
    - Allows external file metadata uploading via a "description" attribute.
  - GET /search \
    - Search within the file description or file contents (excluding binary files).
    - Replies with a download links for the found files.
  - GET /download \
    - Downloads a file.

---

## 🧠 About Me

Before completing my Computer Science degree, I spent over a decade working in telecoms provisioning, technical coordination, and infrastructure projects.

That background gave me:

- A strong production mindset.
- Clear communication and documentation habits.
- Comfort working in complex technical environments.

Now I combine that experience with modern backend development skills.

I am seeking a **Junior Backend Engineer** role where I can:

- Build reliable services.
- Learn from experienced engineers.
- Contribute meaningfully to real production systems.

---

## 📫 Contact

- [GitHub](https://github.com/jstriker87)
- [Email](mailto:jbart1@gmail.com)
