Currently I'm limiting this repository to services that work without a graphical display (X11 or Wayland or anything else). As of systemd v205, one cannot use `systemd --user` standalone anyway (instead, a user service manager is started automatically on first login).

This is a personal configuration repo, so I'm not going to accept any pull requests adding units for programs that I don't use and/or don't even have installed. In fact, expect this repository to be deleted soon.
