package S21212_java90;

public class S21212_wrapper_00 {
	public static void main(String[] args) {
		// wrapper(포장) class
		// 자바는 기본 타입 byte, char, shot, int, long, float, double, boolean
		// 기본 타입의 값을 내부에 두고 포장 할 수 있다 이런 객체를 wrapper(포장) 객체라고 한다.
		// 포장클래스는 Byte, Character, Shot, Integer, Long, Float, Double, Boolean
		// 기본 타입의 값을 포장 객체로 만드는 것을 박싱(Boxing)
		// 반대로 포장에서 기본 타입의 값을 얻어 내는 것을 언박싱(Unboxing)
		int i1 = 126;
		int i2 = 126;

		System.out.println("---기본 타입 int----------------------------------------");
		System.out.println("기본 값 i1: " + i1 + " HashCode:" + System.identityHashCode(i1));
		System.out.println("기본 값 i2: " + i2 + " HashCode:" + System.identityHashCode(i2));

		// 기본 박싱
		Integer is1 = new Integer(126);
		Integer is2 = new Integer(126);
		System.out.println("---기본 박싱 Integer----------------------------------------");
		System.out.println("i1: " + i1 + " HashCode:" + System.identityHashCode(i1));
		System.out.println("i2: " + i2 + " HashCode:" + System.identityHashCode(i2));
		is2 = is2 + is1;
		System.out.println("i2: " + i2 + " HashCode:" + System.identityHashCode(i2));

		// 기본 언박싱
		int si1 = is1.intValue();
		int si2 = is1.intValue();
		System.out.println("--기본 언박싱 Integer---------------------");
		System.out.println(" si1: " + si1 + "hashCode:" + System.identityHashCode(is1));
		System.out.println(" si2: " + si2 + "hashCode:" + System.identityHashCode(is2));

		si2 = si2 + si1;
		System.out.println(" si1: " + si2 + "hashCode:" + System.identityHashCode(is2));
	}
}
