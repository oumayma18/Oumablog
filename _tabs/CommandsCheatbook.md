---
layout: page
icon: fa-solid fa-list
title: Commands Cheatbook
type: cheatsheet
---

A bunch of commands I use to break stuff 💥👾

## Port Scanning

### Scan ports faster:

<pre style="
    background-color: #1d1f21; 
    color: #f8f8f2; 
    font-family: 'Courier New', Courier, monospace; 
    font-size: 1.2rem; 
    padding: 20px; 
    border-radius: 12px; 
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.6); 
    border: 2px solid #ff79c6; 
    position: relative; 
    overflow-x: auto; 
    white-space: pre-wrap; 
    word-wrap: break-word; 
    animation: neon-flicker 1.5s infinite alternate;
">

    rustscan -a 10.10.190.187 -- -A

    <style>
        @keyframes neon-flicker {
            0% {
                text-shadow: 0 0 5px #ff79c6, 0 0 10px #ff79c6, 0 0 15px #ff79c6, 0 0 20px #ff79c6;
            }
            50% {
                text-shadow: 0 0 5px #50fa7b, 0 0 10px #50fa7b, 0 0 15px #50fa7b, 0 0 20px #50fa7b;
            }
            100% {
                text-shadow: 0 0 5px #bd93f9, 0 0 10px #bd93f9, 0 0 15px #bd93f9, 0 0 20px #bd93f9;
            }
        }
    </style>
</pre>



