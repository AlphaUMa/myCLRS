#2.1-1

  PASS

#2.1-2

##### INSERTION-SORT



	for j=2 to A.length

        	key=A[j]

       	 i=j-1

    while i>0 and A[i]<key

        A[i+1]=A[i]

        i=i-1

        A[i+1]=key



#2.1-3

    for i=1 to n

        if(v==A[i])

        return i

    return NIL



#2.1-4

    key=0

    for i=1 to n

        c[n]=(A[n]+B[n]+key)%2

        if(A[n]+B[n]==2)

            key=1

        else key=0

     A[n+1]=key


