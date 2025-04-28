# GoBld  (still in progress)

## Overview
GoBld is a utility designed to run commands when directories change, files are added or deleted,
or when their content is modified. While still under development, it currently supports Go, 
Rust (with some issues), and bash scripts, with plans to extend its capabilities to other 
languages in the future.

## Motivation
As a Vim user and occasional Emacs, I became liked Kakoune (a text editor), 
specifically its desertEx theme. However, I found it challenging to replicate the command-running functionality 
I enjoyed in Vim within Kakoune. Despite extensive searches online, I couldn't find a satisfactory solution. 
Thus, I embarked on creating GoBld: a tool that enables running commands while editing files.
Then if found **entr**

