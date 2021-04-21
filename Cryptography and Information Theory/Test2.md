Entropy: Balls in a Bin

Q1 - 5 Red, 3 Yellow, 4 Green. 1 event. Probability of choosing red ball?
	N = 5+3+4 = 12
	pr[r] = 5/12
	pr[y] = 3/12
	pr[g] = 4/12
	
Q2 - H of pick one ball (I suppose any)?
	H = -m*sum_i (p_i log2(p_i))
	m = 1 event
	p_i = 
	H = -[pr[r]*log2(pr[r]) + pr[y]*log2(pr[y]) + pr[g]*log2(pr[g])] = 
		= -[5/12*log2(5/12)+3/12*log2(3/12)+4/12*log2(4/12)] = 1.555
		
		
Q3 - Now we have m = 5 the same problem as Q2:
	
	H = -m * [pr[r]*log2(pr[r]) + pr[y]*log2(pr[y]) + pr[g]*log2(pr[g])] = 
		= - 5 *[5/12*log2(5/12)+3/12*log2(3/12)+4/12*log2(4/12)] = 7.773
		
Q4 - Entropy will be maximize as the probabilities are equal. Hence formula H = m*log2(N) (m = num events and N = num outcomes or 1/N = probability). 
    Thus we want all the ball have pr = 4/12 = 1/3 to get out.
	  
    Answer: recolor a red ball to yellow.
	
Q5 - 12 green balls. m = 5 event.
	N = 1 type of balls (green)
	pr[g] = 1
	H = -5*log2(1) = 0
