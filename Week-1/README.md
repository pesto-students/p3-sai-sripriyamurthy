# Week1 Assignment1 - HTML
Assignment on HTML

## How a Browser Works
When a user enters an URL in the browser, how does the browser fetch the desired result ? Explain this with the below in mind and Demonstrate this by drawing a diagram for the same

1. What is the main functionality of the browser?
2. High Level Components of a browser.
3. Rendering engine and its use.
4. Parsers (HTML, CSS, etc)
5. Script Processors
6. Tree construction
7. Order of script processing
8. Layout and Painting


## Guidelines:

1. Submit this assignment on GIT - Answer should be in readme File (with images) on GIT.
2. Candidates should be able to explain how a browser works.
3. What are the high level components of a browser?
4. How each component works with each other. (For example: Networking component is the one which makes HTTP calls, Data storage component is a browser’s persistence layer which saves data locally such as Cookies and Local Storage.
5. How Parsing works and its importance.
6. The order of execution of scripts.

## Outcome:

1. Under the hood understanding of how a browser works.
2. What are the features a browser provides?
3. What a browser is capable of doing.
4. How a web page is translated from a string in a URL to a webpage.

## Browser High Level Structure

Lets understand the Browser components 

# ![HighLevelStructure](media/Web-Browser-Components.png)

The browser's main components are:

1. **The user interface:** This includes the address bar, back/forward button, bookmarking menu, etc. Every part of the browser display except the window where you see the requested page.
2. **The browser engine:** marshals actions between the UI and the rendering engine.
3. **The rendering engine:** responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.
4. **Networking:** For network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.
5. **UI backend:** used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.
6. **JavaScript interpreter:** Used to parse and execute JavaScript code.
7. **Data storage:** This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.

## Details on the references used to create this README

<details><summary>Get details</summary>
 
- How to write README.md usiung markdown is learnt from [here] (https://cloudaffaire.com/how-to-write-readme-md-using-markdown/)
 
- Details about the assignment were learnt from [here](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/#The_browsers_we_will_talk_about), [here](https://www.youtube.com/watch?v=hJHvdBlSxug) and [here](https://www.youtube.com/watch?v=WjDrMKZWCt0&t=378s)
 
</details>
