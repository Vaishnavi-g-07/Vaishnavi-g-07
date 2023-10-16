- 👋 Hi, I’m @Vaishnavi-g-07
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Vaishnavi-g-07/Vaishnavi-g-07 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.Arrays;
import java.util.Random;

public class Demo {

	public static void main(String[] args) {
		int [] a= {1,2,3,4,5,6,7};
		Random r=new Random();
		for(int i=0;i<a.length;i++) {
			int swap=r.nextInt(a.length);
			int temp=a[swap];
			a[swap]=a[i];
			a[i]=temp;
		}
System.out.println(Arrays.toString(a));
	}

}
