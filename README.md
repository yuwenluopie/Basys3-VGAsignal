# Basys3-VGAsignal
--A VGA Controller Design based on Basys3. <br>
--The aim of the design is to generate controllable colourful pattern (3x4 squares) on the screen using VGA port of Digilent Basys 3” FPGA board.<br>
--The design is implemented in 'Vivado'and 'Multisim'.<br>
--All functions asked in Labs is completed.<br>
--CE264 Digital Systems Design.<br>
--Thanks for XLR, a beautiful girl living nearside door,to teach me and give me encourage!<br>

## Using tips
This is flow chart show the design idea for this project
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;www.iodraw.com\&quot; modified=\&quot;2022-05-03T02:54:35.609Z\&quot; agent=\&quot;5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/101.0.4951.41 Safari/537.36 Edg/101.0.1210.32\&quot; etag=\&quot;1owJXkaoS0t1zwbw_wsg\&quot; version=\&quot;13.3.6\&quot; type=\&quot;device\&quot;&gt;&lt;diagram id=\&quot;MnnARWXf5bvv-frp1m58\&quot; name=\&quot;第 1 页\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"></div>
<script type="text/javascript" src="https://www.iodraw.com/diagram/js/viewer.min.js"></script>
The top module of this experiment consists of seven sub-modules, and their relationship is shown in flow chart. In this flow chart, the purple block represents hardware, the blue block represents the native integrated system on Basys3 board, the yellow block represents the self-designed sub-module, and the red line represents physical connection.
