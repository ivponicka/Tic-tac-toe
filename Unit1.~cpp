//---------------------------------------------------------------------------

#include <vcl.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;

char i1,i2,i3,i4,i5,i6,i7,i8,i9; // areas/images 1-9, content: i1='b' (blank), 'x' or 'o'
char player;

void check(){
     if((i1==i2 && i2==i3 && i1!='b') ||
        (i4==i5 && i5==i6 && i4!='b') ||
        (i7==i8 && i8==i9 && i7!='b') ||
        (i1==i4 && i4==i7 && i7!='b') ||
        (i2==i5 && i5==i8 && i2!='b') ||
        (i3==i6 && i6==i9 && i3!='b') ||
        (i1==i5 && i5==i9 && i1!='b') ||
        (i3==i5 && i5==i7 && i3!='b'))
     {
       char * message;
       if (player=='x') message="Circle wins! YAAAY!";
       else message="Cross wins! YAAAY!";
       Application->MessageBox(message, "END OF GAME", MB_OK);
     }
}

//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------

void __fastcall TForm1::FormCreate(TObject *Sender)
{
    Image1->Picture->LoadFromFile("Img/blank.bmp");
    Image2->Picture->LoadFromFile("Img/blank.bmp");
    Image3->Picture->LoadFromFile("Img/blank.bmp");
    Image4->Picture->LoadFromFile("Img/blank.bmp");
    Image5->Picture->LoadFromFile("Img/blank.bmp");
    Image6->Picture->LoadFromFile("Img/blank.bmp");
    Image7->Picture->LoadFromFile("Img/blank.bmp");
    Image8->Picture->LoadFromFile("Img/blank.bmp");
    Image9->Picture->LoadFromFile("Img/blank.bmp");
    turn->Picture->LoadFromFile("Img/osmall.bmp");

    i1='b'; i2='b'; i3='b';
    i4='b'; i5='b'; i6='b';
    i7='b'; i8='b'; i9='b';

    player='o';
    Image1->Enabled=true;
    Image2->Enabled=true;
    Image3->Enabled=true;
    Image4->Enabled=true;
    Image5->Enabled=true;
    Image6->Enabled=true;
    Image7->Enabled=true;
    Image8->Enabled=true;
    Image9->Enabled=true;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image1Click(TObject *Sender)
{
  if(i1=='b') {
     if(player=='o'){
       Image1->Picture->LoadFromFile("Img/o.bmp");
       i1='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image1->Picture->LoadFromFile("Img/x.bmp");
       i1='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image1->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image2Click(TObject *Sender)
{
if(i2=='b') {
     if(player=='o'){
       Image2->Picture->LoadFromFile("Img/o.bmp");
       i2='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image2->Picture->LoadFromFile("Img/x.bmp");
       i2='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image2->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image3Click(TObject *Sender)
{
if(i3=='b') {
     if(player=='o'){
       Image3->Picture->LoadFromFile("Img/o.bmp");
       i3='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image3->Picture->LoadFromFile("Img/x.bmp");
       i3='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image3->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image4Click(TObject *Sender)
{
if(i4=='b') {
     if(player=='o'){
       Image4->Picture->LoadFromFile("Img/o.bmp");
       i4='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image4->Picture->LoadFromFile("Img/x.bmp");
       i4='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image4->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image5Click(TObject *Sender)
{
if(i5=='b') {
     if(player=='o'){
       Image5->Picture->LoadFromFile("Img/o.bmp");
       i5='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image5->Picture->LoadFromFile("Img/x.bmp");
       i5='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image5->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image6Click(TObject *Sender)
{
if(i6=='b') {
     if(player=='o'){
       Image6->Picture->LoadFromFile("Img/o.bmp");
       i6='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image6->Picture->LoadFromFile("Img/x.bmp");
       i6='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image6->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image7Click(TObject *Sender)
{
if(i7=='b') {
     if(player=='o'){
       Image7->Picture->LoadFromFile("Img/o.bmp");
       i7='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image7->Picture->LoadFromFile("Img/x.bmp");
       i7='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image7->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image8Click(TObject *Sender)
{
if(i8=='b') {
     if(player=='o'){
       Image8->Picture->LoadFromFile("Img/o.bmp");
       i8='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image8->Picture->LoadFromFile("Img/x.bmp");
       i8='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image8->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Image9Click(TObject *Sender)
{
if(i9=='b') {
     if(player=='o'){
       Image9->Picture->LoadFromFile("Img/o.bmp");
       i9='o';
       player='x';
       turn->Picture->LoadFromFile("Img/xsmall.bmp");

     }
     else {
       Image9->Picture->LoadFromFile("Img/x.bmp");
       i9='x';
       player='o';
       turn->Picture->LoadFromFile("Img/osmall.bmp");
     }
     Image9->Enabled=false;
     check();
  }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button1Click(TObject *Sender)
{
    Application->Terminate();
}
//---------------------------------------------------------------------------
