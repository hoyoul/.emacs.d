

* ORG파일을 emacs 설정파일로 
** [기존 방식 - init.el]
- emacs booting시에 init.el이란 설정파일을 실행.
- init.el은 code위주, 설명은 부가적(주석으로 처리). 

** [새로운 방식 - emacs.org]
- org file에서 설정하고 init파일을 변환.
- org설정파일은 document위주, code는 부가적.
- org file은 plain text라서 code를 실행할수 있는 code block의 설정은 org-babel이 하고, code를 init.el로 변환저장은 org-tangle이 수행.

** 수행 방식
1) org babel
- org-babel-load-language에서 interpreter를 설정. 해당 code block을 사용할 수 있다.
- code block의 실행은 C-c C-c를 누르면 interpreter가 실행되면서 code block을 해석한다.
2) org-tangle
- 상단에 org문서에 대한 property에서 변경할 파일 init.el을 명시한다.
- elisp code block에서 org문서를 저장할때 tangle을 수행하게 hook을 건다.

3) 위 두가지를 설정했으면, 이제 C-c C-c로 2개의 block을 실행한다. 이제부터는 init.el에서 emacs설정 파일을 만드는 것이 아니라, org파일로 설정하면 된다.

* right command to Meta key
- 오른쪽 command key를 meta key로 설정했다. karabiner로 설정할 수 있지만, emacs에서만 사용할 것이라서 여기서 설정.