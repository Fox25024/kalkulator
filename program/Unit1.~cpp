//---------------------------------------------------------------------------

#include <vcl.h>
#include <math.h>
#include <windows.h>
#pragma hdrstop

#include "Unit1.h"

float x,y,w;
String znak;
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;
//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)                              
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image12Click(TObject *Sender)
{
        Edit1->Text="0";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image2Click(TObject *Sender)
{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }

        if(Edit1->Text=="0")
        {
                Edit1->Text="";
        }
        String LCD;
        LCD=Edit1->Text;
        LCD=LCD+"1";
        Edit1->Text=LCD;

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image3Click(TObject *Sender)

{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }

        if(Edit1->Text=="0")
        {
                Edit1->Text="";
        }
        String LCD;
        LCD=Edit1->Text;
        LCD=LCD+"2";
        Edit1->Text=LCD;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image4Click(TObject *Sender)

{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }

if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"3";
Edit1->Text=LCD;        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image5Click(TObject *Sender)

{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }

if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"4";
Edit1->Text=LCD;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image6Click(TObject *Sender)

{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }

if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"5";
Edit1->Text=LCD;        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image7Click(TObject *Sender)

{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }
if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"6";
Edit1->Text=LCD;        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image8Click(TObject *Sender)

{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }

if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"7";
Edit1->Text=LCD;        
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image9Click(TObject *Sender)
{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }
if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"8";
Edit1->Text=LCD;

}
//---------------------------------------------------------------------------



void __fastcall TForm1::Image10Click(TObject *Sender)
{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }
if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"9";
Edit1->Text=LCD;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image11Click(TObject *Sender)
{
        if(znak=="pier")
        {
        Edit1->Text="";
        znak="1pier";


        }
if(Edit1->Text=="0")
{
Edit1->Text="";
}
String LCD;
LCD=Edit1->Text;
LCD=LCD+"0";
Edit1->Text=LCD;
}
//---------------------------------------------------------------------------


void __fastcall TForm1::Image15Click(TObject *Sender)
{
        x=StrToFloat(Edit1->Text);
        Edit1->Text="";
        znak="1+";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image14Click(TObject *Sender)
{
        if((znak=="+")||(znak=="-")||(znak=="*")||(znak=="/")||(znak=="^")||(znak=="2pier")) //kolejne liczenie
        {
                if(znak=="+")
                {
                        w=w+y;
                        Edit1->Text=w;
                }
                else if(znak=="-")
                {
                        w=w-y;
                        Edit1->Text=w;
                }
                else if(znak=="*")
                {
                        w=w*y;
                        Edit1->Text=w;
                }
                else if(znak=="/")
                {
                        w=w/y;
                        Edit1->Text=w;
                }
                else if(znak=="^")
                {
                        w=pow(w,y);
                        Edit1->Text=w;
                }
                else if(znak=="2pier")
                {
                        w=pow(w,1.0/y);
                        Edit1->Text=w;
                }
                  //koniec drugiego liczenia




        }

        else  //pierwsze liczenie
        {
        y=StrToFloat(Edit1->Text);
        if(znak=="1+")
        {
                w=x+y;
                Edit1->Text=w;
                znak="+";
        }
        else if(znak=="1-")
        {
                w=x-y;
                Edit1->Text=w;
                znak="-";
        }
        else if(znak=="1*")
        {
                w=x*y;
                Edit1->Text=w;
                znak="*";
        }
        else if(znak=="1/")
        {
                if(y==0)
                {
                        ShowMessage("Nie dziel przez zero wprowadŸ now¹ liczbe");
                }
                else
                {
                        w=x/y;
                        Edit1->Text=w;
                        znak="/";
                }
        }
        if(znak=="1^")
        {
                w=pow(x,y);
                Edit1->Text=w;
                znak="^";
        }
        if(znak=="1pier")
        {
                if(y==0)
                {
                        ShowMessage("Podano nie odpowiedni stopieñ pierwiastka");
                }
                else
                {
                         w=pow(x,1.0/y);
                         Edit1->Text=w;
                         znak="2pier";
                }

        }
        } //konie pierwszego liczenia
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image16Click(TObject *Sender)
{
        x=StrToFloat(Edit1->Text);
        Edit1->Text="";
        znak="1-";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image17Click(TObject *Sender)
{
        x=StrToFloat(Edit1->Text);
        Edit1->Text="";
        znak="1*";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image18Click(TObject *Sender)
{
        x=StrToFloat(Edit1->Text);
        Edit1->Text="";
        znak="1/";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image19Click(TObject *Sender)
{
        x=StrToFloat(Edit1->Text);
        Edit1->Text="";
        znak="1^";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image21Click(TObject *Sender)
{
float r,wyn=0;
r=StrToFloat(Edit1->Text);
for(int i=r; i>0; i--)
{
        wyn=wyn+r;
        r--;
}
Edit1->Text=wyn;

}
//---------------------------------------------------------------------------


void __fastcall TForm1::Image22Click(TObject *Sender)
{
x=StrToFloat(Edit1->Text);
w=pow(x,0.5);
Edit1->Text=w;

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image23Click(TObject *Sender)
{
x=StrToFloat(Edit1->Text);
Edit1->Text="Podaj stopieñ";
znak="pier";


}
//---------------------------------------------------------------------------

void __fastcall TForm1::Image24Click(TObject *Sender)
{
        if(znak=="pier")
        {
                Edit1->Text="";
                znak="1pier";


        }

        
        String LCD;
        LCD=Edit1->Text;
        LCD=LCD+",";
        Edit1->Text=LCD;
}
//---------------------------------------------------------------------------


