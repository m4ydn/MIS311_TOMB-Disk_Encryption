# MIS311_TOMB-Disk_Encryption


<p><em><strong><span style="font-family: Helvetica; font-size: 20px;">Presentation video link:</span></strong></em></p>
<p><strong><span style="font-family: Helvetica; font-size: 20px;"><em><a href="https://drive.google.com/file/d/1a9ZCcXNw_X-jzZ4bCDqcHxBW0MrmV-_2/view?usp=sharing">https://drive.google.com/file/d/1a9ZCcXNw_X-jzZ4bCDqcHxBW0MrmV-_2/view?usp=sharing</a><br></em></span></strong></p>
<p><br></p>
<hr>
<p><span style="font-family: Helvetica;"><br></span></p>
<p><span style="font-family: Helvetica;"><strong><em><span style="font-size: 24px;">Introduction</span></em></strong></span></p>
<p><span style="font-family: Helvetica;"><em><span style="font-size: 17px;">Disk encryption is a technology that transforms the information contained in it into an unreadable code that cannot be easily deciphered to protect it from unauthenticated persons. Disk encryption uses disk encryption software or hardware that encrypts every bit of data going to the disk or any part of the disk. It prevents unauthenticated persons from accessing the data memory.</span></em></span></p>
<p><span style="font-family: Helvetica;"><span style="font-size: 17px;"><em>Full Disk Encryption or Whole Disk Encryption technology is said to encrypt everything except the master boot record or similar space, a boot disk, the operating system boot code. Some hardware-based full disk encryption systems encrypt the entire boot disk, including the master boot record.</em></span></span></p>
<p><span style="font-family: Helvetica;"><br></span></p>
<p><span style="font-family: Helvetica;"><strong><em><span style="font-size: 22px;">Security concerns</span></em></strong></span></p>
<p><span style="font-family: Helvetica;"><em>Most full-disk encryption projects are vulnerable to a cold boot attack, in which the encryption keys are stolen by cold-booting the operating system of the currently running machine and hijacking the data in memory before its contents are lost. This attack is based on the data magnetization feature of computer memory, the magnetization feature is stated as it takes a few minutes for the computer to shred data bits after power is turned off.[3] The Trusted Platform Module is also ineffective against this attack, because the operating system keeps in memory the decryption keys used to access the disk.</em></span></p>
<p><span style="font-family: Helvetica;"><em>All software-based encryption systems are vulnerable to various side-channel attacks, such as acoustic cryptoanalysis and hardware keylogger attacks. On the other hand, self-encrypting devices are not vulnerable to such attacks, as the hardware encryption key is never left to the control of the disk.</em></span></p>
<p><span style="font-family: Helvetica;"><br></span></p>
<p><span style="font-family: Helvetica;"><strong>Tool: TOMB</strong></span></p>
<p><span style="font-family: Helvetica;"><span style="font-size: 20px; color: red;"><em>https://github.com/dyne/Tomb</em></span></span></p>
<hr>
<p><span style="font-family: Helvetica;"><br></span></p>
<p><span style="font-family: Helvetica;"><strong><em><span style="font-size: 22px;">Installation</span></em></strong></span></p>
<p><span style="font-family: Helvetica;">Tomb needs a few programs to be installed on a system in order to work:</span></p>
<ul>
    <li><span style="font-family: Helvetica;">zsh</span></li>
    <li><span style="font-family: Helvetica;">net</span></li>
    <li><span style="font-family: Helvetica;">sudo</span></li>
    <li><span style="font-family: Helvetica;">gnupg</span></li>
    <li><span style="font-family: Helvetica;">cryptsetup</span></li>
    <li><span style="font-family: Helvetica;">pinentry-curses (and/or -gtk-2, -x11, -qt)</span></li>
</ul>
<hr>
<p><span style="font-family: Helvetica;"><br></span></p>
<p><span style="font-family: Helvetica;"><strong><em><span style="font-size: 22px;">Using</span></em></strong></span></p>
<ul>
  
    Once installed one can proceed creating a tomb, for instance:
  
![Ekran Alıntısı](https://user-images.githubusercontent.com/85017128/123321581-d481df80-d53b-11eb-93cb-4f0d91cc9147.PNG)


    When this is done, the tomb can be opened with
  
  ![2](https://user-images.githubusercontent.com/85017128/123322060-76093100-d53c-11eb-8aa7-53a28f78fb65.PNG)



![3](https://user-images.githubusercontent.com/85017128/123120444-fb151d00-d44c-11eb-87fe-1eca0cddf0b8.PNG)</span></p>



    The key can also be hidden in an image, to be used as key later

![4](https://user-images.githubusercontent.com/85017128/123120446-fb151d00-d44c-11eb-920f-516668e92ef4.PNG)



![5](https://user-images.githubusercontent.com/85017128/123120448-fbadb380-d44c-11eb-96c0-9e65222811bd.PNG)

    Type the password you created

![6](https://user-images.githubusercontent.com/85017128/123322219-b1a3fb00-d53c-11eb-9bb7-60ca7f648a15.PNG)


![7](https://user-images.githubusercontent.com/85017128/123120425-f8b2c300-d44c-11eb-83c0-ffc0d4e5b0bf.PNG)
