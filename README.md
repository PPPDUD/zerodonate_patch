# zerodonate_patch
Automatically patch the XMRig source code to disable mandatory donations. An up-to-date mirror of the patchfile is hosted at https://mojavesoft.net/common/zerodonate_patch.

To execute the patch on an Ubuntu system, run `curl https://mojavesoft.net/common/zerodonate_patch | patch [xmrig-path-here]/src/donate.h --verbose` (replacing [xmrig-path-here] with the path to your XMRig source code folder).

Not endorsed or approved by XMRig.
