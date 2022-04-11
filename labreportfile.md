__Step 1: Installing VSCode__
![Image](https://lh3.googleusercontent.com/wGw4oLEZXQManp6zUI-m0SwRgZK2DL7YabChRyFnaP9ONhBO6yOLff4FaO10--t7a9Foov2q5P9m4aEROw18FQsHNWv9Js5Fb8H61-sXF22BS2OsiYxb2wZLKyJNbqztOd3PPn3SWqJ7s_DFkRsiSyuYwjCBSYysSO8lcK88SX_nfB2m5YSHQwi_IeG9UucnbrYIjkwsKs0WVHidhVQ_b8ot0ozqRNKbFnDWjdabONKEqyUObRmIuwDgqGuOuZtFoz8baSKhGy07PjwE_PAD55wOLmpONBm6-cjFM4059efWZU0Y9FPqRjSCb6JiS4-pMtzmtKKhEPO3ckN3QDEchTn_N9glWgNPEfv5D0PcC7zI8IBsD37MjE5XL2-zTQnFZQaWPvvOYWduJSby1WJuck6QS4xyrAQ8MkKFqtcTiSJFI8Pv5G11DVdIgEk1r4LVpijAl2WuqgH1dqm5jkyyHLmQlbPyZV6c8V6jChphZWX9vz4kDNk8sgU8wJJBvPd3IlfnT-mMIY9t7DpRdqOmjQGEKpNyKJLcZXjO6Bve3b5dWMudQL0hfQzjz4nc6LUc1e1RG8MotrlcCCuTGs3s0HKGbK6xDmzGhGpb_jCAcAEb7lxPU2wu0GeDz1cJAJpBbUpEX7pDmNdtNzMiirX4DRZwgq1_Czjnb9irNWV0F1tbEkTHGHMvbxHjqBVUuMbrQ918gtK5B1O6u4AGtoh1vZTznT2OLI5Ui2UHvpe5vdBeyEPf_WtWxo5X0bf_FAOd1PonA164YUytHV00Qi7QGUvjzh_Dvi1q1zcpCQ=w2098-h1312-no?authuser=0)
To download VSCode, we need to:
* Look up VSCode on a browser
* Find the URL https://code.visualstudio.com/
* Download the current version of VSCode for the users specific OS
* Once the download is complete, we can open up VSCode and it should come with a couple prompts

Step 2: Remotely Connecting
![Image](https://lh3.googleusercontent.com/BVDjtp5J0kde-96YcVdTSxHi0JHYBE-Pry4NEiYYk5Sj8M0n32vY0m8nGka_MJK9QES1fMDYx9cfNd6BhgTGDmcVFNoOBFJxxhdUXIchDAW6uSZbxdO3nxX54mNp2rIUslF1_3_SGpn0IfLe2Dxt0MKnkZvyOtEmZHS2ZB23IkxsSK4GLRw9t_3v2P2Mp-xY3rHjEL4X86RYhBZFebvePk40E5qtjKp6aKhB245lixTz-qqzZhQwA1fq_DDM_tTeJO0EDxc0yBKthviytnGhTOlD3S1I3E6bgic0Z-uC8GebjuGRAk7qyUdIDAA4I7onyLb3-I9N4U95Fj0ELGfbO48d8ZAOJzWKe0eFeP023mCP_zC2R-5p95LmfFDqOPlh5S0OJKZL0GiUTpJJP5eXCkAtkwuwNEdgmK5cqPRZeJ6re-izUfn_7PE1D9j2cK2X2mb5SjwB74oBNl762Ny6qiWVNkif3uSjieqJFJhi0W_oQ-COelFI0RVqMhFMASULSp3ZvWvU6bsGs4RoC3ucivBjDsW0su5miu_w4dw3UClZLzGWYMJ6S19FfZ6-DEfHP9ze9fkTMvDt8agI8xVFbfgfuszxKYCUGri1kFCaliTeR66-ig22SJURtA7586v_l-BQOdvy0--nbXxulBqw-LzXlkwGTSlxzENiHsu45qkYpco4abTMrQ2iTBeQncxwszLA6O5G8D_t4MZ2lbUjKFZJSWfQBhS9kh41bGzZ09yqtMmZqqN2PcDaJWtv1OkszOWbKWjR6Y-w0XYOqKIDjJrMgO1MUeWR16_tNw=w976-h452-no?authuser=0)
* First you need to install OpenSSH, through the link https://sdacs.ucsd.edu/~icc/index.php 
* Next, on the VSCode, we can make a new file so we can go into terminal, which can be access through the top tab
Terminal -> New Terminal Menu Option)
* Once you are in the terminal, you will need to type in the command
 $ ssh cs15lsp22zz@ieng6.ucsd.edu *The zz you need to replace with your own course-specific account letters
* This step is for first time users doing this, in which case there will be a message saying
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?
* In which case, you will just type yes, which would then get you to the photo that I have posted above.

Step 3: Trying some commands
![Image](https://lh3.googleusercontent.com/dZyKkkQatu13od4UbgHbV6Pt1LgKIB_WYwzE-YD9ZlOXV5yBmvd97EhDxIWfpghGckZxJpJ41F-KncMrqUAzFi7sj4S0G2YMhD8rGJhZfMC0tScE7FCFglOF-vYL4tFlAFIXiyr89TOno6v0vQAxEoZHu3lVG0dAib1qmEd2bMF9LQKhgbOdMu_N-mIaPtkVm1LNrMYd-uhamEKp_PeYzGpqtp8F5sJ0wClRM2S1eckz4WgPiqQDWtqtFOL2FgaqiQ4EY4k6zQqggusOR6MTShLDMYnVl70bar4Fasu3ADePJdfmghyJmV7EKGKK2PzNlwmrBo_KGWH1S0KPoRyVZEOAWxfIBtcO3mXzherK7hkEbFpNO7d3szijlC_q1iUncjqp_-4q8EHfqwhNgCYK_cFo2OSnQdMZTo_4Y7on7ZWfUGJac8GXG577CanjcNlDAVU4e8SeUvW76N1WHj5b6BLWk0dAfg7SAXP1S3ZzEIi7AUkUFbSsUAS2nuS1bprD7azwALRhd4Zv9r-NNPvJmuIe0ISTKLMmgJUeINmzpOHj7qclgLE--KrQHrQ_kqUltMKG1QVRn6gjWjCQAhMlHg-paYiuUi-gRQmea07vDXu2cj3BJ03SdDkt1AHs-gGMLENpOK-ll4XQJ04_WksA1MBsqBCLScFsSFJOB4-G_IyCRKOYxvaUeryED5izsjUUVYAQHoEh0G9JC6bFvU9bsUH3cFaV1Uw9MLcG8gxDrGIilto2quM4RzENo74dlJ-YWNg9yfyqkJ1OgxAcpKGpCWSjnLihIOF8WoIFbQ=w1198-h234-no?authuser=0)
* This step can be different, as for my example,  I have used the command ls and cd perl5 to show that I am in the remote connection, but there is many other commands that someone can use such as
  * cd
  * ls
  * cp
  * cat
  * And more!

Step 4: Moving Files with scp
![Image](https://lh3.googleusercontent.com/U79LDehmCc0rizL9jsdLofMUGYBtQ2cb2RmcxE-BQulPP__9hpVKp0RnlkS-dkFiiid-ufUZ4QcVDp2evtY_EgTUUVsAqoS_sKuJhvJlLnr4-lXpAx94hP75BeENpi1LVtT_S2RfQs2s9-P1p8aSGxZVpB8iAOpUPWDvYbwWXYteOPqPlWr7OwkMEpIf-4ef1m8OiCJvBmBdUs3eRbtwhjFmar0icH_V-L9Wc5gYczmeFoybcrcBjyN4RXQ2pqneD9S1MguZx20B1RqctzaeTEQWDD5s761bQ-caZASeSe3VVeZ-3DxMYq6bw4Dyscugd-vcEGF5EWiRPoKeYTIwxBjb4Srv1zpyxvh1IgxIAVwobUuCnkDYultvD7dnjElRCbOc-YTNA6m7wVGabe090zf8dBEt7ZttpPcQoJNa4XIQjKXveBj38LrsjGhyIfPT19PPCPzga9KH0ZxzirE79y-a7eNG7jZigtIMqVbwjlJnCkK1ML-JMdcp-eXfxwVHJ6Hg9fhivmDZmvikNp9HRZUIHd7ypUZMgnlb1FvuVf-2g2STZvVTen_5_1d2W1XvoMrlOgXHSjHKkO_ldMdejPoTGBq6eSgpTlKaCRSsutwmb9BdEnFf26oDAZX8gQYtaUYpjR8ajSZCy-8v1Aa18DeLJvq46dYZBCVaw23hVLRK2v_R1JgNAHlq9_5853BQdBByMX82OU4BR7KkhYG5hREKc-X9sD1j7XFwDibOcsnjjiPioM-ntne0qXmSbpbo7dK-BcT9HAH0Qeea-i4O6ujse19Ky4vk7vLvqQ=w2098-h546-no?authuser=0)
If we would like to move a file with our remote connection, we can do this with a file, for example, a java file. 
* In the terminal command, we can write the command
  Scp zz.java cs15lsp22zz@ieng6.ucsd.edu:~/*the zz for the .java could be whatever java file you would name, and the second for the zz would be for your own course-specific account letters
* Once you write this command, it will prompt you with a password for the ucsd account you are remotely connecting to. 
* After this, you can log into the remote connection with the  
  $ ssh cs15lsp22zz@ieng6.ucsd.edu to then check for the file using ls, which should then reveal the file you moved into the remote connection.

Step 5: Setting an SSH key
![Image](https://lh3.googleusercontent.com/ueZDp_w8Ikw21LLs4Bj3kTane2F3IWUYE2yrIjKeK6OowGTBmJttMc1tncHM-LnIEAmKLMyCtguTlPV0TmdoUWZ6aWKaXxkVGz380fdnHpCg17_j4ph8Y5drKP5xo1qQZ1rFwwcrYGzvtMNg9Tf93QZtDzkcgNIcINoln4boYcyRUNZOp3XCaAtWWC6j7x35ZEUAsROm3DsPPiVjSS_CtA0uruNOfwPH1BzB2rH7oCj5P_swEF0BxwpkUhvjON80opHdRv4twb9p-n21xokrDdfzUdl6D3QTBHXtnKSNL2YjWXE9QBftiBkZOqa0wHp5l4KfLvA5Wn9tLcLF0G_JfoV2OLhIOQAk2OiSZPGhaDdSmC_OoUL4qnn0Q9mKUReX-vClbinSYGrqq4J2M5M7EDXokIAr7V4y8v5P01kgNSvrg1gm_kiIVzQZiklXF4GM15_l-v84KL9BWQKeEF4tMkHslrKGLfmX4Ltr_mAWjXWQOSqultrnqiIUAmOLk_kZTMQrhTVZD9nUc0O9avHK0Dj9k_28fijiZzSyEghYCiSoCBQ1i9tFwCFuYrid46mrPUGfNd3BmWeWBh0iTlSJcPEph6btZYKsz5175ZTj5GehJT2YZL3lXyA2mgItxdrsuJcyKmF0m3D89-bdU66n4AESMBd_ObP0Ub9kwYhqLyUIVpUHC8dWvIGNslenoD8nyejUxAYp287HZlIAEOBTrI-tLbQYWUjwDk9eZFO3trArQvoLQZvPW7DMXVlEnBPxTfKMpSW4q2W8FPna4dCfSMy5-3rTisRwlAxRxQ=w1248-h840-no?authuser=0)
* On the terminal for VSCode *or normal terminal on your OS*, write the command
  $ ssh-keygen
* Which then prompts
  Generating public/private rsa key pair.
  Enter file in which to save the key (/Users/<user-name>/.ssh/id_rsa): /Users/<user-name>/.ssh/id_rsa // replace the <user-name> with your own user-name
* Next prompts for a passphrase that you should make
  Enter passphrase (empty for no passphrase):
* Which then prompts for the password again to make sure you didn’t make a mistake
  Enter same passphrase again: 
* Which once put in, will give you a message like this.
  Your identification has been saved in /Users/<user-name>/.ssh/id_rsa.
  Your public key has been saved in /Users/<user-name>/.ssh/id_rsa.pub.
  The key fingerprint is:
  SHA256:jZaZH6fI8E2I1D35hnvGeBePQ4ELOf2Ge+G0XknoXp0 <user-name>@<system>.local
  The key's randomart image is:
  +---[RSA 3072]----+
  |                 |
  |       . . + .   |
  |      . . B o .  |
  |     . . B * +.. |
  |      o S = *.B. |
  |       = = O.*.*+|
  |        + * *.BE+|
  |           +.+.o |
  |             ..  |
  +----[SHA256]-----+
* Once on this step, we have our ssh key that we need to copy over to the .ssh directory to our account on the server
  $ ssh cs15lsp22zz@ieng6.ucsd.edu
  <Enter Password>
  # now on server
  $ mkdir .ssh
  $ <logout>
  # back on client
  $ scp /Users/<user-name>/.ssh/id_rsa.pub cs15lsp22zz@ieng6.ucsd.edu:~/.ssh/authorized_keys
  # You use your username and the path you saw in the command above

Step 6: Optimizing Remote Running
![Image](https://lh3.googleusercontent.com/qBeyP_h-g6AWl71wJiYXCi3tnx2BgQTBH4s-q_noL76wTa34ovY2wNiYNOTxjX9CuQeVku2jGXgzpVCtMlZ-KOb2hSEu1ffWgmKRR1q9fMScWZXf2HPKv7r852EzaKjnkoskG1SVfA4ai43nCHKjZo_zKC7EZ5cTrKV54_DMbVrjDBtI5UpHfsXP3lRoAHFtKKJbJTw8GB7pcXiHOWlRXPbn2OULHpLSNgjfK3tNFIpttcyVrV08A1fUjvdZQNE6MAGL_JcNPvvFqmzYi6Mg07CoaG0EIP8sUP-ffVHaNISP2YEkYQkye2pkQTSsMQu8HAQ_nURjS-VyQwFCVpvvgc3l5tzKqNcoazccmZ9bbEvDRuC-bchPM0qRjMbqD508oVDDJnCbYh9cq9lzUfCOOyX8KM0iihxo5umDTCoUi0gAW1gdYuTQZImO5NJDRiu6ojM3rxhGKFGKATXQ7LTLHtko2mMEBzFhHb-Vgm7GpS3SaKuAa16fB-uuk3VQAmroH5vYGjB8e6dAs0mrc1Ffc7YlwiTrAbPSFhYYVTooxh81uYZNnyTPPUU8dvnAsC2wMLVUFggYgpfNTCml_VRNZN2APK4vJFNtiMLskQqzjEYadqN1hmTzRQvt6TmI4BAiNkw82sIqWt6QcscVhrBsV6UeJ-_4rfhC-hc6OH9lNRu8ngaTHUwZdodh9x5ogzCHz3VwqauXRM75OwLh6cUHwY6LTGgBD24zjvdhbDZP3HauIxwC_3z8QSfjCum8eCUi8G5JocCv-FtrKA99F_45_PhEt0huvmu0MnI2UA=w1252-h130-no?authuser=0)
* For this step, this can help modifying files by using the commands
  $ ssh cs15lsp22zz@ieng6.ucsd.edu "ls"
* This helps get us to the home directory on the remote server 
  $ cp zz.java Otherzz.java; javac Otherzz.java; java zz
* This helps us run multiple commands to make modifying or moving files easier and faster to not have to log on, and deal with multiple commands on the terminal
