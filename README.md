## Welcome stranger 👋

Newbie pwner, currently learning what people have already mastered... 

pretty hopeless for a starter 😭

I will try to share as much as i can in the progress...

everything is already found by someone else anyway.

<img src=https://38.media.tumblr.com/2de3e0b0f051c4ba33cd375999704ded/tumblr_ntpp3pJ1ny1uewxwpo1_500.gif>

---

## CTF Write-ups 🚩

Not advanced...

as expected 😞

Serves as an info dump and knowledge check...

and sometimes for a quick reference on something.


<details>
  <summary><b>Format strings challenges</summary>

- <b>  FCSC 2022 </b>

<ol>
  
  -  <k>[writeup](https://github.com/4rsp/writeups/tree/main/FCSC/2022/formatage)</k>
  > *one shot, no leaks, Full RELRO, input stored on the heap... abuse double stack pointers for the win!* 

</ol>

- <b> nullcon CTF 2025 </b>

<ol>
  
  -  <k>[writeup](https://github.com/4rsp/writeups/tree/main/Nullcon-2025/hateful)</k>
  > *classic fmt challenge* 

</ol>

  </b>
</details>

<details>
  <summary><b>Heap challenges</summary>

#### glibc 2.36

- <b> nullcon CTF 2025 </b>

<ol>
  
  -  <k>[writeup](https://github.com/4rsp/writeups/blob/main/Nullcon-2025/hateful2/README.md)</k>
  > *tcache poisioning into FSOP attack* 

</ol>

#### glibc 2.35

- <b> Imaginary CTF 2023 </b>

<ol>
  
  -  <k>[writeup](https://github.com/4rsp/writeups/tree/main/Imaginary-CTF-2023/mailman)</k>
  > *house of botcake + FSOP + seccomp* 

</ol>

#### glibc 2.27

- <b> Sunshine CTF 2023 </b>

<ol>
  
  -  <k>[writeup](https://github.com/4rsp/writeups/tree/main/Sunshine-CTF-2023/house_of_sus)</k>
  > *house of force into malloc hooks* 

</ol>
</details>

<details>
  <summary><b>ROP/BOF challenges</summary>
    
-  <b> 0x3 CTF 2025 </b>

<ol>
  
  -  <k>[writeup](https://github.com/4rsp/writeups/blob/main/x3CTF-2025/devnull-as-a-service/)</k>
  > *restriected seccomp, call mprotect to fix the permissions of our shellcode and use openat-read-write syscalls* 

</ol>

  </b>

</details>


---


## It's demo time! 🔨

Mostly inspired by other hackers...
or something that kills time.
Always preferring to *practice,*
instead of staring at them long writeups !

- [exit_handlers](https://github.com/4rsp/docs/tree/main/practice.tool/exit.handlers)
> *_dl_fini and __exit_funcs* (libc 2.39)

- [file struct exploits](https://github.com/4rsp/docs/blob/main/practice.tool/file.structs/README.md)
> *exploiting _wide_data vtable (path=_IO_wfile_overflow) via targetting stdout* (libc 2.39)

---


<p align='center'>
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbTFjM3VnanB4Z3hrdG5yZTV3ejdwOGkzeWVld3hxb2w0N2JmeGdxNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4ilFRqgbzbx4c/giphy.gif">
</p>


<p align='center'>
<em>
work in progress...
  </em>
</p>
