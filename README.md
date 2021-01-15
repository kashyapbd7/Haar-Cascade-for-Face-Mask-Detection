# FaceMask-Haar-Cascades



Here is the list of some pretrained model along with their training parameters. This is goo practise for computer vision begineers for facial mask recognition.



Hardware

Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz (12 CPUs), ~2.6GHz
GeForce RTX 2060



1)Cascade0.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 600 -numStages 12 -precalcValBufSize  
6000 -precalcIdxBufSize 6000 -minHitRate 1 -maxFalseAlarmRate 0.1

2)Cascade1.xml -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 600 -numStages 12 -precalcValBufSize  
6000 -precalcIdxBufSize 6000 -minHitRate 1 -maxFalseAlarmRate 0.1 -mode ALL    

3)cascade2.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 600 -numStages 12 -precalcValBufSize  
6000 -precalcIdxBufSize 6000 -minHitRate 1 -maxFalseAlarmRate 0.1 -mode ALL -bt DAB

4)cascade3.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 6000 
-numStages 8 -precalcValBufSize  6000 -precalcIdxBufSize 6000 -minHitRate 1 -maxFalseAlarmRate 0.1 -mode ALL 

5)Cascade4.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 1000 -numStages 12 -precalcValBufSize 
 6000 -precalcIdxBufSize 6000 -minHitRate 1 -maxFalseAlarmRate 0.1 -mode ALL  

6)Cascade5.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 900 -numStages 10 -precalcValBufSize  
12000 -precalcIdxBufSize 12000 -minHitRate 1 -maxFalseAlarmRate 0.1 -mode ALL 

7)Cascade6.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 900 -numStages 10 -precalcValBufSize  
12000 -precalcIdxBufSize 12000 -minHitRate 1 -maxFalseAlarmRate 0.1 -featuretype 
LBP

8)Cascade7.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 1000 -numStages 12 -precalcValBufSize  12000 -precalcIdxBufSize 12000 -minHitRate 1 -maxFalseAlarmRate 0.1 -mode ALL

9)Cascade8.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 800 -numStages 12 -precalcValBufSize  12000 -precalcIdxBufSize 12000 -minHitRate 1 -maxFalseAlarmRate 0.1 

10)Cascade.xml - -data cascade/ -vec pos1.vec -bg negative.txt -w 24 -h 24  -numPos 400 -numNeg 1000 -numStages 12 -precalcValBufSize  6000 -precalcIdxBufSize 6000 -minHitRate 0.999 -maxFalseAlarmRate 0.1 
