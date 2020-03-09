 mean(DartPoints$Length) 
 
[1] 49.33077

mean(DartPoints[, 5])

[1] 49.33077

mean(DartPoints[,"Length"])

[1] 49.33077

summary(DartPoints$Length)

   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
   
  30.60   40.85   47.10   49.33   55.80  109.50 
  
summary(DartPoints$Length)

   Min. 1st Qu.  Median    Mean 3rd Qu.    Max.
   
  30.60   40.85   47.10   49.33   55.80  109.50 
  
 options(digits=3)
 
 numSummary(DartPoints[, 5:11])
 
           mean    sd   IQR   0%   25%  50%   75%  100%  n NA
           
Length    49.33 12.74 14.95 30.6 40.85 47.1 55.80 109.5 91  0

Width     22.08  5.16  6.60 14.5 18.55 21.1 25.15  49.3 91  0

Thickness  7.27  1.53  2.00  4.0  6.25  7.2  8.25  10.7 91  0

B.Width   13.75  2.95  3.80  7.1 11.70 13.6 15.50  21.2 69 22

J.Width   15.40  2.73  3.95 10.6 13.12 15.6 17.08  21.2 90  1

H.Length  13.41  4.01  5.80  5.8 10.50 12.5 16.30  23.3 91  0

Weight     7.64  4.21  5.50  2.3  4.55  6.8 10.05  28.8 91  0

The patterns exist in skewing. One examplke is the Mean is always larger than the Median.
Another pattern exists in the progression of the 'quarters' (1-3) which tells us that each
'quarter' gets larger than the one before. Only two segments don't have Widths.
They are 22 for the B. Width and 1 for the J. Width. I would use lines (in this notation) 17, 18, 19, 22, and 23 only since the variables don't have inconsistencies 
as found in line 20 and 21. 
