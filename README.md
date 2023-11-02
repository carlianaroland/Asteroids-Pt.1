
public class VectorShape { // base class
	private Shape shape;  // all of the attributes/ private data members, they should only be able to be accessed through their accessor!!
	private boolean alive;
	private double x;
	private double y;
	private double velX;
	private double velY;
	private double moveAngle;
	private double faceAngle;
	
	public VectorShape() { //constructor!! initializing values of private attributes
		this.shape = null;
		this.alive = false;
		this.x = 0.0;
		this.y = 0.0;
		this.velX = 0.0;
		this.velY = 0.0;
		this.faceAngle = 0.0;
		this.moveAngle = 0.0;
		
	}
	
	public Shape getShape() { // accessor | be sure to include the return type next to the private or public statement!!
		return this.shape;  // private data members (this.shape) should only be accessed through accessor, which in this case is getShape
	}
	
	
	public void setShape(Shape shape) { // mutator for the getShape accessor
		this.shape = shape;
	}
	
	
	public boolean isAlive() { // accessor
		return this.alive;
	}
	
	
	public void setAlive(boolean alive) {  // mutator for isAlive accessor
		this.alive = alive;
	}
	
	
	public double getX() { // accessor
		return this.x;
	}
	
	
	public void setX(double x) { // mutator
		this.x = x;
	}
	
	
	public double getY() { // accessor 
		return this.y;
	}
	
	
	public void setY(double y) { // mutator
		this.y = y;
	}
	
	
	public double getVelX() { // accessor
		return this.velX;
	}
	
	
	public void setVelX(double velX) { // mutator
		this.velX = velX;
	}
	public double getVelY() { // accessor
		return this.velY;
	}
	
	
	public void setVelY(double velY) { // mutator
		this.velY = velY;
	}
	
	
	public double getMoveAngle() { // accessor
		return this.moveAngle;
	}
	
	
	public void setMoveAngle(double moveAngle) { // mutator
		this.moveAngle = moveAngle;
	}
	
	
	public double getFaceAngle() { // accessor
		return this.faceAngle;
	}
	
	
	public void setFaceAngle(double faceAngle) {  // mutator
		this.faceAngle = faceAngle;
	}
	
	
	public void incX(double i) { // incrementation of this.x
		this.x += i;
	}
	
	
	public void incY(double i) { // incrementation
		this.y += i;
	}
	
	
	
	public void incVelX(double i) { // incrementation
		this.velX += i;
	}
	
	
	public void incVelY(double i) { // incrementation
		this.velY += i;
		
	}
	
	
	public void incMoveAngle(double i) { // incrementation
		this.moveAngle += i;
	}
	
	
	public void incFaceAngle(double i) { // incrementation
		this.faceAngle += i;
	}
	
}
