# hello-world-1
just another repository
public int doThings(String numberString) {
  try {
    int i = Integer.parseInt(numberString);
  } catch(Exception e) {
    System.out.println(e);
  }
  return i;
}

