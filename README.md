# 5010-Assignment3

'''
  let x = 0
function setup() {
  createCanvas(1200,200)
}
function draw() {
  if( frameCount < 120 ) {
	// first five seconds assuming 60 fps
	x += 1
  }else if( frameCount < 240 ) {
    // seconds 5-10
    x += 4 
  }else{
    x += int(random(5,20))
  }
   
  
translate(random(-1, 1), random(-1, 1))
  background(
    random(200, 255),
    random(0, 40),
    random(0, 40)
  )
  
  noStroke()
  fill(255,random(150, 255), random(150, 255))
  textSize(100+random(-10,10))
  textFont("boldface")
  text(x+" Bugs were Found", 10, 170)

  fill(255)
  textSize(40)
  text("Whenever a deadline is approaching.", 10, 50)
}
'''
