Oculus OpenXR Mobile SDK (mirror)
===

Version 37.0.0.

This is a Git mirror of Oculus' OpenXR Mobile SDK, for use as a submodule in LÖVR.  We only need to
link against the OpenXR loader library, so this is literally just the 2 `.so` files in the
`OpenXR/Libs/Android/arm64-v8a` directory of the SDK.

Because the open source OpenXR loader did not initially ship with support for Android, Oculus
released their own OpenXR loader.  The open source loader has since added support for Android, so
hopefully this isn't necessary for very long.
