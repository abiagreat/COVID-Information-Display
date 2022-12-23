# COVID-Information-Display

Code in Java:


Country.java


public class Country 

{
   
   private String name;
   
   private String countryCode;
   
   private int newConfirmed;
   
   private int newDeaths;
   
   private int newRecovered;
   
   private int totalConfirmed;
   
   private int totalDeaths;
   
   private int totalRecovered;

    public Country 
    
    (String name, String countryCode, int newConfirmed, int newDeaths, int newRecovered, 
    
    int totalConfirmed, int totalDeaths, int totalRecovered)
    
    {
    
    this.name = name;
    
    this.countryCode = countryCode;
    
    this.newConfirmed = newConfirmed;
    
    this.newDeaths = newDeaths;
    
    this.newRecovered = newRecovered;
    
    this.totalConfirmed = totalConfirmed;
    
    this.totalDeaths = totalDeaths;
    
    this.totalRecovered = totalRecovered;
    
    }
    
    public int getNewConfirmed() 
    
    {
    
    return newConfirmed;
    
    }    
    
    public int getNewDeaths()
    
    {
    
    return newDeaths;
    
    }

    public int getNewRecovered() 
    
    {
    
    return newRecovered;
    
    }

    public int getTotalConfirmed() 
    
    {
    
    return totalConfirmed;
    
    }

    public int getTotalDeaths() 
    
    {
    
    return totalDeaths;
    
    }

    public int getTotalRecovered() 
    
    {
    
    return totalRecovered;
    
    }
    
    public String getName()
    {
    
    return name;
    
    }
    
    public String getCountryCode() 
    
    {
    
    return countryCode;
    
    }

}


MainPage.java:

  public MainPage() 
  
  {
  
  Country usa = new Country("United States of America", "USA", 24257,267,17556,6300622,189208,2333551);
  
  Country india = new Country("India", "IN", 75809, 1133, 73521, 4280422, 72775, 3323950);
  
  Country brazil = new Country("Brazil", "BR", 10273, 310, 27046, 4147794, 126960, 3549201);
  
  Country russia = new Country("Russian Federation", "RF", 5106, 50, 2317, 1027334, 17818, 840997);
  
  Country peru = new Country("Peru", "PE", 6275, 151, 15829, 689977, 29838, 522251);
  
  Country colombia = new Country("Colombia", "CO", 5327, 203, 11050, 671848, 21615, 529279);
  
  Country safrica = new Country("South Africa", "ZA", 845, 115, 2664, 639362, 15004, 566555);
  
  Country mexico = new Country("Mexico", "MX", 3486, 223, 6665, 637509, 67781, 531334);
  
  Country spain = new Country("Spain", "ES", 26560, 98, 0, 525549, 29516, 150376);
  
  Country argen = new Country("Argentina", "AR", 9215, 270, 8256, 488007, 10129, 357388);
  
  initComponents();
  
  }

