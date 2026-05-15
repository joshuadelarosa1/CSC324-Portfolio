+++
date = '2026-04-15T13:46:31-05:00'
draft = false
title = 'Infrastructure'
+++

## Infrastructure

In terms of development tools, I used Visual Studio Code as my IDE along with (from time to time) Copilot to help me write code. We weren't really able to automate the build/deployment process using code, so we stuck to the simple 'drag and drop' method of running our code through Love in order to see how our build would look like when deployed. One specific issue I had while writing code was not knowing how my formatting was looking like as I was updating it. For example, a button would suddenly be off-screen or off-centered, while seemingly nothing changed in the code. This often meant having to go back and forth between writing something in VS Code, then dragging and dropping, sometimes getting a blue screen, and having to redo what I had done before to try again. Debugging in VS Code itself (through benchmarks or other tools) was not really an option when dealing with formatting issues, as it wasn't able to identify why a certain block wasn't in the correct position. When it wasn't a formatting related issue and instead something in the syntax itself, the lua blue screen was also particularly frustrating because it did not give the most in-depth reasoning to why it occurred. This made it hard to debug without using Google or AI. Copilot was somewhat helpful for when these kinds of things happened, however, since I don't think it often understood what I was asking of it (especially in terms of the UI design), it didn't always provide a solution to the issue that was occuring. When Copilot was not producing anything useful, I often also tried to ask ChatGPT and look around Google to see if others had similar issues.

This demonstrates the completion of the infrastructure competency because I identified different tools I used when writting and debugging code, along with how these tools sometimes helped/hindered when debugging UI issues.