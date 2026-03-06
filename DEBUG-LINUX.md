Problema

```log
(.venv) pabloqpacin•repos/Setenova/yt-dlp-gui(main)» python3 app/app.py                                                                              [16:40:03]
qt.qpa.plugin: From 6.5.0, xcb-cursor0 or libxcb-cursor0 is needed to load the Qt xcb platform plugin.
qt.qpa.plugin: Could not load the Qt platform plugin "xcb" in "" even though it was found.
This application failed to start because no Qt platform plugin could be initialized. Reinstalling the application may fix this problem.

Available platform plugins are: xcb, minimal, linuxfb, minimalegl, wayland-brcm, wayland-egl, wayland, vkkhrdisplay, offscreen, vnc, eglfs.

[1]    1226355 IOT instruction (core dumped)  python3 app/app.py
```

Solución

```log
pabloqpacin•repos/Setenova/yt-dlp-gui(main)» agi libxcb-cursor0                                                                                      [16:40:43]
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed:
   libxcb-cursor0 (0.1.1-4ubuntu1)
0 upgraded, 1 newly installed, 0 to remove and 116 not upgraded.
```
