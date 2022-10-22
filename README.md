# newcodingpage
new repo
package com;

class Problem4 {
	public static void main(String[] args) {
		int[] a={1,2,8,9,12,46,76,82,15,20,30};
		int count1=0,count2=0,count3=0,count4=0,count5=0,count6=0,count7=0,count8=0,count9=0;
		for(int i=0;i<a.length;i++){
			if(a[i]%1==0){
				count1++;
			}
			if(a[i]%2==0){
				count2++;
			}
			if(a[i]%3==0){
				count3++;
			}
			if(a[i]%4==0){
				count4++;
			}
			if(a[i]%5==0){
				count5++;
			}
			if(a[i]%6==0){
				count6++;
			}
			if(a[i]%7==0){
				count7++;
			}
			if(a[i]%8==0){
				count8++;
			}
			if(a[i]%9==0){
				count9++;
			}
		}
		System.out.println("1:"+count1+", 2:"+count2+", 3:"+count3+", 4:"+count4+", 5:"+count5+", 6:"+count6+", 7:"+count7+", 8:"+count8+", 9:"+count9);
	}
}
