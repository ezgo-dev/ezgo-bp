# ezgo-bp

ezgo for banana pi

1. ctrl-alt-F1, enter console.
2. adduser --shell /bin/bash ezgo
3. change /etc/group and /etc/sudoers to add ezgo
4. logout and relogin with ezgo
5. (delete user bananapi)
6. locale-gen zh_TW.utf8  && locale-gen zh_TW
7. /etc/profile.d/i18n.sh
8. wget -O - http://ezgo.goodhorse.idv.tw/apt/ezgo/ezgo.gpg.key | apt-key add -
9. echo "deb http://ezgo.goodhorse.idv.tw/apt/ezgo/ testing-bp main" > /etc/apt/sources.list.d/ezgo.list
10. apt-get update
12. change hostname and /etc/hosts
11. logout and relogin ezgo in console
13. apt-get install ezgo-menu ezgo-lxde ezgo-artwork
14. add-apt-repository ppa:fcitx-team/nightly
15. apt-get update; apt-get install fcitx fcitx-chewing fcitx-frontend-all fcitx-libs-qt5 fcitx-table-array30-big fcitx-table-cangjie3 fcitx-tools fcitx-m17n
16. timezone

17. apt-get upgrade
18. apt-get install firefox-locale-zh-hant language-pack-zh-hant language-pack-gnome-zh-hant

19. apt-get install qtqr gimp tuxpaint inkscape vlc filezilla winff audacity
(translations for qtqr, conf for tuxpaint, zh for audacity)
