# Basys3-VGAsignal
--A VGA Controller Design based on Basys3. <br>
--The aim of the design is to generate controllable colourful pattern (3x4 squares) on the screen using VGA port of Digilent Basys 3” FPGA board.<br>
--The design is implemented in 'Vivado'and 'Multisim'.<br>
--All functions asked in Labs is completed.<br>
--CE264 Digital Systems Design.<br>
--Thanks for XLR, a beautiful girl living nearside door,to teach me and give me encourage!<br>

# How to use this project?
1. Make sure that you have some knowledge of PLD / Multisim / Basys3 board.
2. Read  “**Basys3-Reference** **Manual”** and “**PLD datasheets”** in **Literature Support carefully **.
3. Read **‘Project reseach report**’ (which writen by me) in Literature Support. I given many details of this project  this report.
4. The circuit reading order may be ‘7-segment’ → ‘VGA Display’ → ‘VGAcontroller’, if you are a newbie
5. Try to transfer circuit diagram into PLD and burn in your Basys3 board.
6. Done!
PS. If you have any question about this project, you can send a email: nicoyu191@gmail.com 

## Preformance
https://www.youtube.com/watch?v=GE7h9XSa9vw&feature=youtu.be or https://www.bilibili.com/video/BV1H34y1e7oi?share_source=copy_web)

## Overview
This is flow chart show the design idea for this project
![XmindofVGA](https://user-images.githubusercontent.com/88228465/166400132-911be76d-f2ba-4990-b8dd-f23b497a98b7.jpg)<br>
The top module of this experiment consists of seven sub-modules, and their relationship is shown in flow chart. In this flow chart, the purple block represents hardware, the blue block represents the native integrated system on Basys3 board, the yellow block represents the self-designed sub-module, and the red line represents physical connection.
