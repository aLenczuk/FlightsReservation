
public class Flight
{
	private String direction;
	private int seatsNumber;
	private int id;


	public Flight(String direction, int seatsNumber, int id) {
		this.direction = direction;
		this.seatsNumber = seatsNumber;
		this.id = id;
	}

	public int getId(int id){
		return id;
	}
	
	public int getId()
	{
		return id;
	}

	public void setId(int id)
	{
		this.id = id;
	}

	public String getDirection()
	{
		return direction;
	}

	public void setDirection(String direction)
	{
		this.direction = direction;
	}

	public int getSeatsNumber()
	{
		return seatsNumber;
	}

	public void setSeatsNumber(int seatsNumber)
	{
		this.seatsNumber = seatsNumber;
	}

}
