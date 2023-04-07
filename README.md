# CTDL-GT_binary_search_2.cpp
Tìm kiếm nhị phân 
Nguồn tham khảo: https://gochocit.com/ky-thuat-lap-trinh/thuat-toan-tim-kiem-nhi-phan-binary-search
Ví dụ : 
Tìm x=4 trong mảng đã được sắp xếp tăng dần bên dưới : 

                3  4  5  6  7  8  9

Xác định left=0 và right=6 trên mảng đang xét : 

                3  4  5  6  7  8  9
             left                 right 

Xác định được mid=(left+right)/2=3 trong mảng đang xét và a[mid]=6 : 

                3  4  5  6  7  8  9
                        mid

Giá trị x=4 nhỏ hơn a[mid]=6 nên right=mid-1=2, left vẫn là 0. Mảng con đang xét hiện giờ là a[left],…,a[right] : 

               3    4    5    6    7    8    9
             left    right   mid

Xác định lại mid=(left+right)/2=1 và a[mid]=4 : 

              3     4     5   
                   mid

Tìm được x=4 trong mảng con : 

              3    4     5    
                  mid
Tìm thấy x = a[mid]
