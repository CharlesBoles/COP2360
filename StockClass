//define stock class
public class Stock
{ 
  public decimal CurrentPrice { get; set; }
  public decimal SharesOwned { get; set; } 

  public decimal Worth => CurrentPrice * SharesOwned; 
}

class Program 
{ 
  //Where program starts
  static void Main() 
  { 
    //make instance of stock
    Stock stock = new Stock 
    {
      CurrentPrice = 50.00m,
      SharesOwned = 100 
    }; 

     // Show stock info
      Console.WriteLine($"Current Price: ${stock.CurrentPrice}");
      Console.WriteLine($"Shares Owned: {stock.SharesOwned}");

      // Investment value
       Console.WriteLine($"Total Worth: ${stock.Worth}");
  }
}
