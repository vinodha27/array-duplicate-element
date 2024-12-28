# array-duplicate-element
int[] a={2,3,6,1,7,9,9,2,23,71,4};
        for(int i=0;i<=a.length-1;i++)
        {
            for(int j=i+1;j<=a.length-1;j++)
            {
                if(a[i]==a[j] && i!=j)
                {
                      System.out.println(a[i]+" duplicate number");
                }
            }
        }
