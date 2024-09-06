# AlternateRowwise-Direction-2D-Array-Using-Java
for(int j=0;j<cols;j++){
            if(j%2==0){
                for(int i=0;i<rows;i++){
                    System.out.print(arr[i][j]+" ");
                }
            }
            else{
                for(int i=rows-1;i>=0;i--){
                    System.out.print(arr[i][j]+" ");
                }
            }
