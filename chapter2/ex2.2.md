

#2.2-1

    O(n^3)

#2.2-2

#####SELECTION-SORT

     for i=1 to A.length-1

        min=i

        for j=i to A.length

           if(A[j]<min)

                min=j

                tmp=A[j]

                A[j]=A[min]

                A[min]=tmp

##### best status:
                tij=0,θ(n);
##### worst status:
                tij=n-i,θ(n^2)
#2.2-3
##### best status:
                θ(1)
##### worst status:
                θ(n)
#####average:
                the probability to be checked is 1/n,
                so we should try at least n times to check one time:n*1/n=1;
                so the average:n


