Class rc_boat:

int forward = 12 // forward pin
int left = 11 // left pin
int right = 10 //right pin not in use because boat unable to turn right without losing trash

void setup():  // initialize the digital pins as an outputs
  pinMode(forward, OUTPUT)
  pinMode(left, OUTPUT)

void go_forward():
  digitalWrite(forward,HIGH) // set motor too high for forward angle

void stop_car():
  digitalWrite(forward,LOW) // set motor too off for forward angle
  digitalWrite(left,LOW)

void go_left():
  digitalWrite(left,HIGH) // set motor too high for left angle

Void movement(){
  Boolean trash
  if trash==true:
  			go_forward()
  else:
  			go_left()







