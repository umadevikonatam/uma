public class Solution1 {
	public int sumdigits(String s) {
		int sum=0;
		for(int i=0; i<s.length(); i++) {
			char c = s.charAt(i);
			if(Character.isDigit(c)) {
				String st = new String();
				st = s.substring(i,i+1);
				sum = sum + Integer.parseInt(st);
	}
}
	return sum;  
	}
}
