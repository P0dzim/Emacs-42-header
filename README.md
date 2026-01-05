# Emacs-42-header
Emacs Lisp script to insert 42 header

> ⚠️ **Warning:** This code was written by an A.I. with the goal of replicating the original vim script.

## Installation

### 1. Configure user
 Open file `stdheader.el` and edit the fisrt lines with your user and e-mail:

```elisp
(defvar 42-header-user-login "your_user" "42 user login")
(defvar 42-header-user-mail "your_email_marvin@42.fr" "42 user email")
```
### 2. Move the file
 Move the file to `~/.emacs.d/`

 ### 3. Edit init.el
  At the end of `init.el` put: 

```elisp
(if (file-exists-p "~/.emacs.d/stdheader.el") (load-file "~/.emacs.d/stdheader.el"))
```
### 4. Usage
  Press key [F1] or C-c h to use.
