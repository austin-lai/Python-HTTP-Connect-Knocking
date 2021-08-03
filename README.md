# Python-HTTP-Connect-Knocking

> Austin Lai | August 3rd, 2021

---

<!-- Description -->

Python HTTP Request Connect script, Knocking Port to get next port and instruction.

Created for one of TryHackMe Room.

Using python library:

- re
- socket
- requests
- urllib

**[Please check out the full script _here_](https://github.com/austin-lai/TryHackMe-WriteUp/blob/master/TryHackMe(THM)-HackBack%202019/python-http-connect.py)**

<!-- /Description -->

## Detail of script usage

Script require you to have a Starting Number = 0, to perform calculation.

The script is use to create HTTP request to webserver with given default port (example 3010).

Then in the response, it will give the instruction as shown below:

```text
multiply        1         6783
operation     number      port
```

You will have to do calculation and store it in script by using your Starting Number {Operation given} {Number given}

Then create HTTP request and connect to the port given.

Repetition of above till it hit specific port (example port 9765) and you will get the final number base on the calculation.

--- Ideally, the calculation should start when the LivePort (example 1337) is alive !

<br />

---

> Do let me know any command or step can be improve or you have any question you can contact me via THM message or write down comment below or via FB

