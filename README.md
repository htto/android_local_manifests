android_local_manifests
=======================

My local manifests for various devices. Just checkout/copy/link into ${ANDROID_BUILD_TOP}/.repo/local_manifests/

About the files:

- b_cleanup.xml removes some projects I don't use/need.

- c_addons.xml adds some projects.

- c_device_specific_moves.xml removes some common projects and re-adds them under ${ANDROID_BUILD_TOP} device_specific_moves. This is done due to some devices needing patched projects or custom forked repositories and to avoid having to have the complete android tree twice. This currently needs my patched build/env_setup.sh and, as to expect, a device_specific folder in the device trees that need those.

- d_*.xml Are the device files.

