# COAL
COAL Project Only


Download and install NASM, AFD and DOSBOX, according to the instructions, in your NASM folder.
AFD: https://drive.google.com/file/d/1eXnD3JEwBelFiJT6iIk7gluudV2Fu_iX/view?usp=sharing
NASM: https://drive.google.com/file/d/1ZoeE2MxjNaK7DdJKCacYfAJyn006MI_F/view?usp=sharing
Dosbox: https://drive.google.com/file/d/1DnaDIk4RoGBFDP1y4Dr3q89xwM3gx1d1/view?usp=sharing
 
1: https://drive.google.com/file/d/1N3lWL8hsN0ZbhF3tlNwCWWwjJ_eHQqk6/view?usp=sharing
Tutorial part 2: https://drive.google.com/file/d/10p8qyaOVOwF5lDighrMKE-uNYQX-
c3bL/view?usp=sharing

You can also download all the three files by using the following link
http://wetolearn.blogspot.com/2013/09/setting-up-afd-nasm-and-dosbox-for-8086.html

After installations double click “DOSBox 0.74-2 Options.bat” file and at the end of the file paste
following lines:
MOUNT C D://COAL//NASM
C:
(We are mounting C drive to our folder where we have saved AFD and we will save our .asm file in this
directory)

Save the project file in your NASM folder e.g. “D:\COAL\NASM”:

Go to NASM installation directory ( e.g. “D:\COAL\NASM”). Copy the Project file into that folder.

Open DOSBox (by double clicking dosbox.exe),Write following command and press enter:
nasm project.asm -o project.com -l project.lst

finally type this and enter to play the game:
Afd project.com
