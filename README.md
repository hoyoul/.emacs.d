* ORG파일을 emacs 설정파일로 변경
- org-babel
- org-tangle 사용
* right command to Meta key

* package repo and use-package settings
* auto update package
* Basic UI settings
- menubar,toolbar,tooltip mode disable

* Yasnippet
- local에 snippets를 유지
* Theme
- doom monokai theme
* doom mode line install
- `M-x all-the-icons-install-fonts` 실행
- 'M-x package-refresh-contents' 실행

* font settings
- Firacode(fixed font), Cantarell(variable font) setting.
- unless all-the-icons-install-font, u can see broken icon.

* org bullet heading
- change headings on org mode

* numbering window on multiples
- use ace-window

* lorem ipsum
- for random string

* ivy & counsel
- when u use some command without candidates like find-files(C-x C-f), you don't feel comfortable.
- ivy and counsel give candidates on minibuffer.

* rainbow delimeters & highlight parentheses
- rainbow make parenthese colored.
- highlight make more bright parenthese on cursor.
- if u use them, turn on them.

* org-roam
- store notes to dropbox for me.

* undo tree
- it shows undo history to tree style

* neotree
- it shows directories like window file explorer.
- you should setting global key to neotree-toggle which can show directories.

<<<<<<< HEAD
* hydra
- hydra can make menu to varieties of buffer.(ex:buffer list, org  buffer, python buffer...)
- I don't use it.
=======
* Hydra and ibuffer
- buffer management. in case of switching buffer, just type C-x b but if u see all buffers using C-x C-b. The reason that you see all buffers is to delete sth. that needs hydra and ibuffer.

* change list marker to dot marker in org mode
- look better dot than -.

* region highlight.
- pressing C-spc, you can assign region. However, the region cannot distint from other contents. so changed region color.

* slime for common lisp code
- install sbcl and quicklisp(like package manager) on your system.
- The emacs use the slime to connect sbcl on your system so you need to install slime for connection on your emacs.
>>>>>>> 9073174986b7c4aa052640a2973393c485af37b1
