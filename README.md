# extraEnd

public String extraEnd(String str) {
  String answerString = "";
  for(int i=0; i < 3; i++){
    answerString+= str.substring(str.length()-2);
  }
  return answerString;
}
