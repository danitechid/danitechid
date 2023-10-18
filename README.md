## Hi there 👋

Hello, best wishes. Let me introduce myself, I'm Dani Ramdani. I am a Programmer with the role of FullStack Web Developer. Currently, I am studying at CUY University through the self-taught method or free online lectures from YouTube. My skills include the ability to create various types of websites, website applications, and APIs. Apart from that, I also have experience in creating WhatsApp Bots. I have been involved in various projects, including creating REST APIs, RESTful APIs using Node and Express, WhatsApp Bots with Node, DDoS script development using Python, Web Streaming Video development with native PHP, WhatsApp Clone using native PHP, as well as other projects. Thank You.

```asm
section .data
    full_name db "Dani Ramdani",0
    age db 17
    location db "Bogor, West Java, Indonesia",0
    career db "Programmer",0
    role db "FullStack Web Developer",0
    skills db "HTML & CSS", 0
           db "JavaScript", 0
           db "Bootstrap", 0
           db "Tailwind CSS", 0
           db "Node", 0
           db "Express", 0
           db "PHP", 0
           db "Java", 0
           db "Python", 0
           db "Ruby", 0
           db "C", 0
           db "C++", 0
           db "C#", 0
           db "F#", 0
           db "Go", 0
           
section .text
global _start

_start:
    ; Display personal information
    mov eax, 4         ; syscall: write
    mov ebx, 1         ; file descriptor: stdout
    mov ecx, full_name  ; message to write
    mov edx, 12        ; length of message
    int 0x80           ; interrupt to invoke syscall
    
    ; Display other information...
    
    ; Exit the program
    mov eax, 1         ; syscall: exit
    xor ebx, ebx       ; exit code 0
    int 0x80           ; interrupt to invoke syscall

```

### Website
<a href="https://danitechno.com">danitechno.com</a> (Bio link)
<br />
<a href="https://danitechid.com">danitechid.com</a> (Portfolio)

### For business
<a href="mailto:contact@danitechno.com">contact@danitechno.com</a>
