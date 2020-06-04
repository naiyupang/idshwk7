python LSBSteg.py encode -i ori.png -o output.png -f 1.txt  
python LSBSteg.py decode -i output.png -o 2.txt  
先cd到LSBSteg.py所在的路径下  
用第一条指令把1.txt中的信息，即57117140隐藏到ori.png中，得到含有隐秘信息的图片，output.png  
用第二条指令从output.png图片中提取隐秘信息，并输出到2.txt文件中  
