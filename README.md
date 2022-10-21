# CyberGet-Edge
This is the GUI version of CyberGet, which is currently under development.

 
| Platform      |    Supported distributions    | State              |
| --------------|------------------------------ | ------------------ |
| Windows       | AMD64/ARM64 Windows10+        |  In development    |
| Linux         | AMD64/ARM64 4.15.0+           |  Wait for scroll   |
| MacOS         | AMD64/ARM64 MacOS 11+         |  Wait for scroll   |
| Android       | AMD64/ARM64 Android9+           |  Wait for scroll   |
| IOS           | <strong>not support</strong>  |  not support       |
 
<br>
The reason for waiting to roll is because each platform uses different technologies and they need to be adapted. Some platforms may not have full support, the table below lists these reasons.

| Platform      |    Support                    |    Reason          |
| --------------|------------------------------ | ------------------ |
| Windows       | latest                        |  Windows 7 and Windows 8.1 were originally on the pre-support list, but they were dropped due to framework adaptation issues    |
| Linux         | 4.15.0+                       |  Support for Linux systems is limited to the latest kernels. Due to possible problems with older kernels, programs running on kernels lower than 4.15.0 will be limited.<br>Also, programs will not run with SELinux turned on.   |
| MacOS         | compile only                  |  We don't have a MacOS testbed and can't guarantee that every build will run correctly on it or achieve what we want.   |
| Android       | latest                        |  Android and desktop platforms use completely different technologies for development, and the migration of code to be compatible with the platform will be a very time-consuming task.<br>We will only support Android9 and newer versions under ARM64/X86 architecture. But stable support is limited to Android11-12, other versions will only be guaranteed to build.   |
| IOS           | <strong>not support</strong>  |  We didn't have an IOS testbed, which was supposed to share the same set of code as Android, but we ended up dropping support for it due to uncertainty.       |
