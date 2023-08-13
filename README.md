## Hi there 👋

I'm Dani, I'm a programmer and my role in the world of programmers is Full Stack Developer, I have experience making social media projects, I've created a ChatApp project similar to WhatsApp and I've created a D-FBook project similar to Facebook, and lastly I build WhatsApp bot project and RESTful API with full CRUD

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
           db "Node.js", 0
           db "Express.js", 0
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
<a href="mailto:contact@danitechid.com">contact@danitechid.com</a>
