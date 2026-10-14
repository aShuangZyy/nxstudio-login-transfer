# nxstudio-login-transfer - moved

This project is superseded by **[nxstudio-ncas-forge](https://github.com/aShuangZyy/nxstudio-ncas-forge)**.

The old approach - copy a captured Nikon NCAS credential snapshot to another
machine and keep it alive with a scheduled task - is no longer needed. The new
repository starts NX Studio without the sign in dialog by answering the two NCAS
calls on the local machine, and ships a self test plus a one command launcher.

## New home

**https://github.com/aShuangZyy/nxstudio-ncas-forge**

```powershell
git clone https://github.com/aShuangZyy/nxstudio-ncas-forge.git
cd nxstudio-ncas-forge
powershell -NoProfile -ExecutionPolicy Bypass -File start-nxstudio.ps1
```

This repository is kept only as a pointer so old links do not break.