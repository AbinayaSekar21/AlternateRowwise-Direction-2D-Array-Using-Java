# AlternateRowwise-Direction-2D-Array-Using-Java

for(int i=0;i<rows;i++){
            if(i%2==0){
                for(int j=0;j<cols;j++){
                    System.out.print(arr[i][j]+" ");
                }
            }
            else{
                for(int j=cols-1;j>=0;j--){
                    System.out.print(arr[i][j]+" ");
                }
            }
          //  System.out.println();
        }
