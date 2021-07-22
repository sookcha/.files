dotfiles
===================

Thoughtbot의 [rcm](https://github.com/thoughtbot/rcm) 을 이용해서 dotfile을 자동으로 설치합니다.

필요한 것
------------

zsh을 시스템으 기본 쉘로 설정하세요.

    chsh -s $(which zsh)

설치
-------

이 저장소를 클론 하세요

    git clone git://github.com/thoughtbot/dotfiles.git ~/dotfiles

(또는, [포크 하시고 포크를 계속 업데이트 하실 수도 있습니다](http://robots.thoughtbot.com/keeping-a-github-fork-updated))

[rcm](https://github.com/thoughtbot/rcm) 을 설치하세요.

    brew install rcm

dotfiles를 설치하세요.

    env RCRC=$HOME/dotfiles/rcrc rcup

업데이트
------

시간이 흐르면서 dotfiles 에 변경 사항이 생길 것입니다. 그럴때는 

    rcup

를 실행해서 새로운 파일과 vim 플러그인을 업데이트 할 수 있습니다.

업데이트
-------

dotfiles is copyright © 2009-2018 thoughtbot. It is free software, and may be
redistributed under the terms specified in the [`LICENSE`] file.

[`LICENSE`]: /LICENSE
