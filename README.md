# SA:MP `system` plugin (REUPLOAD)
Reupload of an old SA:MP plugin that execute shell commands and return the output.

Was originally made by **Killerkid** and found in [this SA:MP forums backup](https://sampforum.blast.hk/showthread.php?tid=100177&pid=1152803#pid1152803).

It's __untested__ and, as it doesnt include any license file, consider it an *ARR* software - *All Rights Reserved*, in case for Killerkid himself.

From his description of how to use it:

```
#include <system>

new string[13];
system("echo Hello World!", string, sizeof(string)); // 'string' now contains the output
printf(string);
```

Will print `Hello World!`.
