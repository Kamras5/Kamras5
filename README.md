# Kamras5
public class Event{
    
    private String date;
    private String startTime;
    private String endTime;
    private String place;
    
    public Event(String date, String sTime, String eTime ,String pl) {
        
        this.date = date;
        
        this.startTime = sTime;
        
        this.endTime = eTime;
        
        this.place = pl;
    }

      public void setDate(String d) {
         date = d;
    }
    public String getDate() {
         return date;
    }
    public void setsTime(String sT) {
         startTime = sT;
    }
    public String getsTime() {
         return startTime;
    }
    public void seteTime(String eT ) {
         endTime = eT;
     }
    public String getPr() {
         return endTime;
    }
    public void setPl(String p) {
         place = p;
    }
    public String getPl() {
         return place;
    }
}  

