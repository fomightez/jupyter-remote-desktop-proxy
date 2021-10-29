# Jupyter Remote Desktop Proxy
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/jupyter-remote-desktop-proxy/HEAD?urlpath=desktop)

------

This is a test of updating https://github.com/fomightez/jupyter-desktop-server based on https://github.com/jupyterhub/jupyter-remote-desktop-proxy, so I can eventually add PyMOL and see if better than https://github.com/fomightez/Jupyter-desktop_with_pymol . ==> It was and [there](https://github.com/fomightez/Jupyter-desktop_with_pymol) has been updated with this better desktop experience. Keeping this as a testing grounds though.

I was not able to make this Dockefile independent as the turbobvnc installing via postBuild didn't work due to it needing root.

--------------------

Run XFCE (or other desktop environments) on Jupyter.

This is based on https://github.com/ryanlovett/nbnovnc.

When this extension is launched it will run a Linux desktop on the Jupyter single-user server, and proxy it to your browser using VNC via Jupyter.

If a `vncserver` executable is found in `PATH` it will be used, otherwise a bundled TightVNC server is run.
You can use this to install vncserver with support for other features, for example the [`Dockerfile`](./Dockerfile) in this repository installs TurboVNC for improved OpenGL support.


