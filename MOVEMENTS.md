Class rc_boat{

  int forward = 12;    // forward pin
  int left = 10;       // left pin
  int right = 9;       // right pin not in use because boat unable to turn right without losing   trash

  void setup(){                
    pinMode(forward, OUTPUT);
    pinMode(left, OUTPUT);
    pinMode(right, OUTPUT);
  }

  void go_forward(){
    digitalWrite(forward,HIGH);   // set motor too high for forward angle
  }

  void go_left(){
    digitalWrite(left,HIGH);     // set motor too high for left angle
    digitalWrite(right,LOW);     // set motor too low for right angle
  }

  Boolean trash= !!!!!!!!!!!!!!!
  
// the loop() method runs continuously
  void loop(){
    if (trash==true){
    	go_forward()
    }else{
    	go_left() 
    }
  }
}

  
 
