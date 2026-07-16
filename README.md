# -
private int number = 0;  void Start() {     StartCoroutine(CountUp()); }  IEnumerator CountUp() {     while (number&lt;1488)      {         number++;         Debug.Log(number);          yield return new WaitForSeconds(0.01f);     }     Debug.Log("хахахаххаха посхалко"); }
