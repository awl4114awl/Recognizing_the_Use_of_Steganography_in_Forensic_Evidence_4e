<p align="center">
<img src="https://i.imgur.com/t23TXuR.png" height="50%" width="50%" alt="daubert standard"/>
</p>

<h1>Lab 2: Recognizing the Use of Steganography in Forensic Evidence</h1>

Introduction

Steganography is the practice of hiding private or sensitive information within something that appears to be nothing out of the usual. The word steganography comes from ancient Greece (steganos), where hiding hidden messages within seemingly harmless messages became an art form. Over the years, steganography has taken on many clever and effective analog forms. One example that is often depicted in movies is invisible ink, which is not actually ink at all but a liquid, such as vinegar, that dries invisibly on paper but reappears when heated by a small flame. Another analog method is newspaper code. Popular among the working class of the Victorian era, newspaper code consisted of holes poked just above specific letters in a newspaper, such that when the dots were transferred and written together, the secret message would be revealed.

 

In the digital age, steganography can be used for digital watermarking, hiding data within images, or to identify the source of a given image or document (embedded copyright). Businesses sometimes employ steganography when they want to supplement the protection of encryption. In countries where encryption is not permitted, steganography can often be used instead. While cryptography involves special encoding and decoding of messages or information, steganography replaces useless or unused data with bits of different, invisible information. This hidden information can be plain text, cipher text, or even images. Special software, such as the tools used in this lab, is needed to apply or decipher steganography.

 

In a forensic investigation, investigators will explore a targeted machine in search of steganographic evidence, but when they do this, they risk changing the very data they seek, potentially invalidating evidence. For this reason, they will often make a copy of an evidence drive and conduct the investigation on that image. In this lab, you will use a variety of free tools to discover possible steganographic activity in image and audio files located on a suspect’s drive image. You will properly identify and extract embedded data in a carrier image and document your findings.



Lab Overview

SECTION 1 of this lab has three parts, which should be completed in the order specified.

 

    In the first part of the lab, you will use Paraben’s E3 to detect the presence of known steganography tools on a suspect’s drive image.

    In the second part of the lab, you will export files from the suspect’s drive and use the StegExpose tool to detect the presence of steganographically-concealed data in an image file.

    In the third part of the lab, you will use the OpenPuff steganography tool to extract the concealed data from the image file.

SECTION 2 of this lab allows you to apply what you learned in SECTION 1 with less guidance and different deliverables, as well as some expanded tasks and alternative methods. You will experiment with different steganography tools and file formats.

 

Finally, you will explore the virtual environment on your own in SECTION 3 of this lab to answer a set of questions and challenges that allow you to use the skills you learned in the lab to conduct independent, unguided work - similar to what you will encounter in a real-world situation.



Learning Objectives

Upon completing this lab, you will be able to:

 

    Conduct searches using hash codes to detect the presence of steganographic software on an evidence drive.

    Use specialized tools to search for hidden data embedded in image and audio files.

    Identify the use of steganographic data concealment techniques for covert communication and potential injected data.

    Extract steganographically sequestered data from identified files while conserving their integrity.

    Report on key details of hidden files and their relevance to a forensic investigation.



Topology

This lab contains the following virtual machines. Please refer to the network topology diagram below.

 

    vWorkstation (Windows: Server 2019)

 

1622666045223_mceclip29.png



Tools and Software

The following software and/or utilities are required to complete this lab. Students are encouraged to explore the Internet to learn more about the products and tools used in this lab.

 

    Paraben’s E3
    StegExpose
    OpenPuff
    S-Tools
    Xiao
    OpenStego



Deliverables

Upon completion of this lab, you are required to provide the following deliverables to your instructor:

 

SECTION 1

 

    Lab Report file, including screen captures of the following:

 

    Search result and its description
    StegExpose results
    Suspicious file in Microsoft Paint
    Contents of the file extracted by OpenPuff

 

    Any additional information as directed by the lab:

 

    Record the passphrase saved in the ReadMe file.
    Describe the contents of the hidden file. How might it be relevant to a forensic investigation?

 

SECTION 2

 

    Lab Report file, including screen captures of the following:

 

    Search result and its description
    WAV file sizes and hash values in E3
    Contents of the hidden file extracted by S-Tools
    Contents of the hidden file extracted by Xiao

 

    Any additional information as directed by the lab:

 

    Identify the image file with concealed data according to the StegExpose steganalysis tool.
    Describe the contents of the two hidden files. How might they be relevant to a forensic investigation?

 

SECTION 3

 

    Lab Report file, including screen captures of the following:

 

    First file extracted by OpenStego
    Second file extracted by OpenStego

 

    Any additional information as directed by the lab:

 

    Record the names of the files that contain concealed data.


<br />
<p align="center">
<img src="https://i.imgur.com/kjRZxxb.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/xw68nXe.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/PX6sTaZ.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/M2YjOpI.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/LHUhEPI.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/k6gMRk4.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/YWZgwFd.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/X3psriY.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/Sqld8vd.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/OUVeIu3.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/OElvKiH.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/3qq4la5.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/s3RZhBa.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/5B9OS22.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/dOiMSCl.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/SRnVH0h.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/DSvgUzL.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/jEB3mKA.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/jMBMcQC.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/mUMMxGZ.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/QcaYJgU.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/5v9MzAu.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/aqioX72.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/riBEthQ.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/FJ711kz.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/vHUGroH.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/yCXs5gR.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/M9JfBTM.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/MfHwqXm.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/ELn0iWy.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/QwNsVJw.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/X85U6xy.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
<img src="https://i.imgur.com/hydvDTk.png" height="80%" width="80%" alt="daubert standard"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
