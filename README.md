# EVA2
## _Another version of EVA using anti-debugging techs &amp;&amp; using Syscalls_

# `First thing:` Dont Upload to virus total. this note is for you and not for me. if you wanna keep this code effective, and u want to use it to bypass windows defender, `DONT UPLOAD IT TO VIRUS` TOTAL OR ANY OTHER WEBSITE LIKE IT, else read the note at line 11 in EVA1

# REQUIREMENTS:
* visual studio 2019 [ it may work with visual studio 2017 ]
* cobalt strike [ take a look at my repo `cobalt-wipe` ]
* python2 for the encoder


# USAGE:
* load this profile : [googledrive_getonly.profile](https://github.com/ORCA666/EVA2/blob/main/googledrive_getonly.profile) in cobaltstrike 
* create your shellcode (x64 `x86 wont work`) using cobalt-strike [check my cobalt-wipe repo]
* place your shellcode inside [encoder.py](https://github.com/ORCA666/EVA2/blob/main/encoder.py) and run it using `python2`
* after [encoder.py](https://github.com/ORCA666/EVA2/blob/main/encoder.py) output your encrypted shellcode copy and paste it inside [EVA.cpp](https://github.com/ORCA666/EVA2/blob/main/EVA2-/EVA.cpp)
* if u want to inject to another process uncomment [line 45](https://github.com/ORCA666/EVA2/blob/2fa4662f03645af1ab3d5ae5248896749c28f64e/EVA2-/EVA.cpp#L45)
* build the code using visual studio 2019 - Release - x64 `x86 wont work`
* enjoy


# DEMO:
### [+] You can do your self a favour and disable *Automatic Sample Submission* in windows defender:

![Screenshot 2021-06-25 123639](https://user-images.githubusercontent.com/66519611/123405199-4137c100-d5b2-11eb-9d34-a2ae0ca65045.png)


https://user-images.githubusercontent.com/66519611/125239345-350d6c80-e2f1-11eb-9ce0-852fbafee68e.mp4




# special thanks for:
*  My friend [@NoOne-hub](https://github.com/NoOne-hub) for the syscalls 
*  [@hasherezade](https://github.com/hasherezade) for [antianalysis_demos](https://github.com/hasherezade/antianalysis_demos)
*  [@jthuraisamy](https://github.com/jthuraisamy) for [SysWhispers2](https://github.com/jthuraisamy/SysWhispers2)


# LICENSE: [GNU General Public License v3.0](https://github.com/ORCA666/EVA2/blob/main/LICENSE)


# My Empty Ethereum Wallet (No jokes) : 0x1B4944030818392D76672f583884F4A125A4415e
![120064592-a5c83480-c075-11eb-89c1-78732ecaf8d3](https://user-images.githubusercontent.com/66519611/123219351-791d0680-d4d5-11eb-8248-e34069d0ad6d.png)



