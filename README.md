# HTML
````
#include <stdlib.h>
#include <stdio.h>
#include <string>
#include <iostream>

using namespace std;

//*********************************************************************//
//algorithm that takes username , prints queries and displays results // 
//********************************************************************//
int main()
{
    string user ,password,confirm_password,confirm_user ;
  
    int resquest_question ();
    int star_form();
    int reboot();



    cout<< "\ncreat a new user\n";

    cin >> user ; 
    system ("clear");

    cout << "\ncriate a new password\n";
    cin >> password;

    system ("clear");


    while (user != confirm_user)
    {

        cout << "\nenter your user\n";
        cin >> confirm_user; 
        system("clear");
    
     //********************//
    //user authentication // 
   //********************//


         if (user == confirm_user)
    {
        cout<<" \ncorrect user\n";
        system("clear");


    }else{

        cout<<"ERRO 404";
        system("clear");

    }

    }

    while (password!=confirm_password)
    {
        cout <<"\nenter your password\n";
        cin >> confirm_password; 
        system("clear");


     //************************//
    //password authentication // 
   //************************//

    if (confirm_password == password)
    {
    cout << "\ncorrect password\n";
    system("clear");


    }else{ 

        cout << "\nerro 404\n";
        system ("clear");

    }
    }

    cout << "\nlogin complete\n";
    system("clear"); 

    star_form();


    return 0;
}
     //*******************//
    //funcion's questions// 
   //*******************//

int resquest_question (){

    string question; 
    int point = false;
        
        
        cout << "\nwelcome to quiz\n";
     
     //*********************//
    //start question's quiz// 
   //*********************//
        
        cout<< "\nwhats is extension of c++ language\n";
        cin >> question;

        if(question=="cpp")
        {
            point++;
            system("clear");
        }else{
            
            system("clear");
        }

        question;

        cout<< "\nwhats is extension of javascript language\n";
        cin >> question;

        if(question=="js")
        {
            point++;
            system("clear");
        }else{

            system("clear");
            
        }
        

        question;
     //*******************//
    //end question's quiz// 
   //*******************//

       cout <<"\n  you haved "; 
       cout << point;
       cout <<"\n Congratulations\n";

    
}


     //*******************//
    //funcion's star form// 
   //*******************//


int star_form (){

    int reboot();



    string resquest,star;

    //************************************//
    //star resquest star or resquest exit//
    //**********************************//

    cout << "\ndo you want to start the questionnaire\n";
    cout << "\nwrite yes for continue  or no for exit\n";
    cin >> resquest;
    system("clear");
        if (resquest=="yes")
    {
        int resquest_question();
        resquest_question();
    }else{

        reboot();
        

    }
    
}

     //**********************//
    //funcion's kill program// 
   //**********************//

int reboot(){

    string resquest_reboot; 

    cout << "\ndo you exit program\n"; 
    cout<< "\nwrite 'yes'\n";
    cin >> resquest_reboot;


    while (resquest_reboot!="yes")


    if (resquest_reboot=="yes")
    {
        system("clear");
        main();
    }
    

}

````



