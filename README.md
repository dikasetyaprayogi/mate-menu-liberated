# mate-menu-libre
mate-menu without nonfree suggestions and support for services that are unsafe and dangerous for privacy

! current repo contains raw edited source of the archlinux mate-menu-17.04.3-1.pkg.tar.xz , additional review and adjustment should be considered when packaging for your distro !


quick changelogs from the original

- [x] /usr/share/mate-menu/icons/search_engines/ : replaced google.ico with duckduckgo.ico
- [x] /usr/lib/python2.7/site-packages/mate_menu/plugins/applications.py : replaced Google, google, google.com, and google.ico, lines in the code with DuckDuckGo, duckduckgo, duckduckgo.com, and duckduckgo.ico
- [x] /usr/share/mate-menu/plugins/applications.py : replaced Google, google, google.com, and google.ico, lines in the code with DuckDuckGo, duckduckgo, duckduckgo.com, and duckduckgo.ico
- [x] /usr/share/mate-menu/applications.list : replaced firefox.desktop, thunderbird.desktop, and pidgin.desktop lines in the code with iceweasel-uxp.desktop, icedove-uxp.desktop, and iceape.desktop
