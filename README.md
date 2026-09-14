# 1a-2-Ubuntu-Desktop-and-Command-Line-Familiarisation

- Which file editors are best for remote access and why?
  
Nano and Vim are the best choice for remote access because they run directly inside the terminal over SSH connections. Unlike graphical editors like gedit, command-line editors don't need a heavy visual interface, which means you can edit files smoothly even on a slow internet connection. Nano is super easy to use for quick edits, while Vim is great for editing large files fast without ever touching a mouse.  

- Compare software installation methods: SaaS vs binaries vs repos vs source.
  
Software installation on Linux happens in a few different ways depending on where the app runs and how it's built. SaaS (Software as a Service) runs entirely online in your web browser without installing anything. Pre-compiled binaries are standalone setup file that you download from a website and install manually. Repositories use built-in system managers like apt to download safe software directly from official channels. Finally, source code compilation means downloading raw code files and building the program yourself using a tool like gcc.

- What are pros/cons of each method from user and developer perspectives?
  
Each method has its own trade-offs for users and developers. SaaS is great for users because there's no installation and it works anywhere, but it requires constant internet. Developers can push updates instantly but have to pay for web servers. Pre-compiled binaries are easy to double-click and install, giving developers freedom outside official stores, but users have to update them manually and developers must build different versions for different computers. Repositories are my favorite because they update automatically and stay secure, making it easy for developers to reach users, even if the repo version isn't always the absolute newest release. Lastly, compiling from source lets users customize performance and gives developers full control over code settings, but it can be really difficult for average users when missing tools like build-essential cause build errors.

- How did using CLI improve your understanding of Linux?
  
Using the terminal really helped me understand what's actually going on under the hood of the operating system. Using commands like "ip" "a" and "nslookup" made networking and IP addresses make way more sense, while tools like top and "ps" -e showed me how Linux manages background tasks and RAM in real time. Editing files with "sudo" and checking config files showed me how security and package downloads actually work. Overall, I realized that while the desktop GUI is nice for everyday stuff, the command line is way faster and gives you complete control over the system.  
