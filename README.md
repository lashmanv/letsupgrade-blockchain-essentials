https://rinkeby.etherscan.io/address/0xFA1177E3CB219B2e5bC0c66CFC0D780f0aE00Ff9
pragma solidity ^0.4.17;
contract healthcare{
     string public name;
     string public mail;
     int public mobno;
     string public docname;
     int public docid;
     string public symptoms;
     string public medication;
     
     function healthcares(string newname, string newmail, int newmobno, string newdocname, int newdocid,string newsymptoms,string newmedications)public{
         mail=newmail;
         name=newname;
         mobno=newmobno;
         docname=newdocname;
         docid=newdocid;
         symptoms=newsymptoms;
         medication=newmedications;
     }

     function setdetails(string newname, string newmail, int newmobno, string newdocname, int newdocid,string newsymptoms,string newmedications)public{
          mail=newmail;
         name=newname;
         mobno=newmobno;
         docname=newdocname;
         docid=newdocid;
         symptoms=newsymptoms;
         medication=newmedications;
     }
     function  getDetails()public view returns(string,string,int,string,int,string,string){
         return(name,mail,mobno,docname,docid,symptoms,medication);
     }
     }

https://rinkeby.etherscan.io/address/0xFA1177E3CB219B2e5bC0c66CFC0D780f0aE00Ff9
pragma solidity ^0.4.17;
contract carnumber{
    string public ownername;
    int public registernumber;
    string public carmodel;
   
     function carnumbers(string newownername, int newregisternumber, string newcarmodel)public{
         ownername = newownername;
         registernumber = newregisternumber;
         carmodel = newcarmodel;
     }
     
     function setdetails(string newownername, int newregisternumber, string newcarmodel)public{
          ownername = newownername;
         registernumber = newregisternumber;
         carmodel = newcarmodel;
     }
     
     function  getDetails()public view returns(string,int,string){
         return(ownername,registernumber,carmodel);
     }
         
         
}
