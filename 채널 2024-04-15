package s21212_00;

class Tv {
	//Tv의 속성(맴버변수)
	String color;		//색깔
	boolean power;		//전원상태(on/off)
	int channe1;		//채널
	public String channeL;
	
	//Tv의 기능(메서드)
	void power() { power = !power; }  //Tv on off 기능을 하는 메서드
	void channe1up() { ++channe1; }   //Tv 채널 높이는 기능
	void channe1Down() { --channe1; } //Tv 채널 낮추는 기능
}

public class S21212_06v1 {
	public static void main(String[] args) {
		Tv t;				//Tv인스턴스를 참조하기 위한 변수 t 선언
		t = new Tv();		//Tv인스턴스를 생성
		
		t.channe1 = 7;		//Tv인스턴스 맴버변수에 값 설정
		t.channe1Down();	//Tv인스턴스 메서드 호출
		System.out.println("a현재 채널은 " + 6 + "입니다");
		
		t.channe1up();
		System.out.println("b현제 채널은 " + 7 + "입니다");
	}
}
