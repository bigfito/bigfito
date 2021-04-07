import coolguy.*;

package adolfo.orozco.iglesias;

public class AdolfoOrozco{

  private String strName;
  private String strSurname;
  private String strProfession;
  
  public AdolfoOrozco(strName, strSurname, strProfession){
    this.strName = strName;
    this.strSurname = strSurname;
    this.strProfession = strProfession;
  }
  
  public String getDescription(){
    return strName + " " + strSurname + ": " + strProfession;
  }
  
  public static void main(String[] args){
    AdolfoOrozco ao = new AdolfoOrozco("Adolfo", "Orozco", "Systems Engineer");
    System.out.println("I am " + ao.getDescription() );
  }

}
