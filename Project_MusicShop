package Music_shop;

import java.util.Scanner;
import java.util.Random;

class MusicShop {
    Scanner sc = new Scanner(System.in);
    Random random = new Random();
    int generateRandomReceiptNumber() {
        return 1000000 + random.nextInt(9999999);
    }

    /**
     *
     */
    void RentBuy()
    {
        System.out.println("WOULD YOU LIKE TO BUY OR RENT AN INSTRUMENT TODAY?");
        System.out.println("PRESS 1 TO BUY      :::::::::::::::::     PRESS 2 TO RENT");
        int x = sc.nextInt();

        if(x==1)
        {
            Buy();
        }
        else if(x==2)
        {
            rent();
        }
        else
        {
            System.out.println("WRONG INPUT");
        }
        int receiptNumber = generateRandomReceiptNumber();
        System.out.println("Your unique 2" +
                "payment receipt number is: " + receiptNumber);
        System.out.println("THANK YOU FOR SHOPPING");
    }

    void Buy()
    {
        System.out.println("WHAT WOULD YOU LIKE TO BUY?");
        System.out.println("PRESS 1 FOR ACOUSTIC GUITAR");
        System.out.println("PRESS 2 FOR UKULELE");
        System.out.println("PRESS 3 FOR PIANO");
        int y = sc.nextInt();
        if(y==1)
        {
            Guitar();
        }
        else if(y==2)
        {
            ukulele();
        }
        else if(y==3)
        {
            piano();
        }
        else
        {
            System.out.println("INVALID INPUT");
        }
    }

    void Guitar()
    {
        System.out.println("HERE ARE SOME GUITAR BRANDS YOU WOULD LOVE TO PLAY  : ");
        System.out.println("PRESS 1 TO BUY YAMAHA GUITARS STARTING FROM 99$");
        System.out.println("PRESS 2 TO BUY CORT GUITARS STARTING FROM 89$");
        System.out.println("PRESS 3 TO BUY FENDER STARTING FROM 69$");
        int z = sc.nextInt();
        switch(z)
        {
            case(1) : System.out.println("HERE ARE SOME YAMAHA GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("YAMAHA C40 CLASSICAL NATURAL FOR 99$" + ":::: PRESS 1 TO BUY");
                System.out.println("YAMAHA FS80C NATURAL FOR 109$" + ":::: PRESS 2 TO BUY");
                System.out.println("YAMAHA F280 BLACK FOR 119$" + ":::: PRESS 3 TO BUY");
                int a = sc.nextInt();
                switch(a)
                {
                    case(1) : System.out.println("YAMAHA C40 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 99$ ");
                        break;
                    case(2) : System.out.println("YAMAHA FS80C IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 109$ ");
                        break;
                    case(3) : System.out.println("YAMAHA F280 BLACK IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 119$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(2) : System.out.println("HERE ARE SOME CORT GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("CORT AF500C NATURAL FOR 89$" + ":::: PRESS 1 TO BUY");
                System.out.println("CORT AD180 NATURAL FOR 99$" + ":::: PRESS 2 TO BUY");
                System.out.println("CORT EARTH 60ce OP FOR 109$" + ":::: PRESS 3 TO BUY");
                int b = sc.nextInt();
                switch(b)
                {
                    case(1) : System.out.println("CORT AF500C NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 89$ ");
                        break;
                    case(2) : System.out.println("CORT AD180 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 99$ ");
                        break;
                    case(3) : System.out.println("CORT EARTH 60ce OP IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 109$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(3) : System.out.println("HERE ARE SOME FENDER GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("FENDER SA 135C FOR 79$" + ":::: PRESS 1 TO BUY");
                System.out.println("FENDER SA 150C FOR 89$" + ":::: PRESS 2 TO BUY");
                System.out.println("FENDER CD-60 FOR 99$" + ":::: PRESS 3 TO BUY");
                int c = sc.nextInt();
                switch(c)
                {
                    case(1) : System.out.println("FENDER SA 135C IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 79$ ");
                        break;
                    case(2) : System.out.println("FENDER SA 150C  IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 89$ ");
                        break;
                    case(3) : System.out.println("FENDER CD-60 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 99$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            default :
                System.out.println("INVALID INPUT");
        }
    }
    void ukulele()
    {
        System.out.println("HERE ARE SOME UKULELE BRANDS YOU WOULD LOVE TO PLAY  : ");
        System.out.println("PRESS 1 TO BUY YAMAHA UKULELE STARTING FROM 17.99$");
        System.out.println("PRESS 2 TO BUY LANIKAI UKULELE STARTING FROM 29.99$");
        System.out.println("PRESS 3 TO BUY FENDER UKULELE STARTING FROM 39.99$");
        int z = sc.nextInt();
        switch(z)
        {
            case(1) : System.out.println("HERE ARE SOME YAMAHA UKULELE YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("YAMAHA INT-UK21-LD  NATURAL FOR 17.99$" + ":::: PRESS 1 TO BUY");
                System.out.println("YAMAHA RVL-UK21 BLACK FOR 20.99$" + ":::: PRESS 2 TO BUY");
                System.out.println("YAMAHA GL1 FOR 26.99$" + ":::: PRESS 3 TO BUY");
                int a = sc.nextInt();
                switch(a)
                {
                    case(1) : System.out.println("YAMAHA INT-UK21-LD  NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 17.99$ ");
                        break;
                    case(2) : System.out.println("YAMAHA RVL-UK21 BLACK IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 20.99$ ");
                        break;
                    case(3) : System.out.println("YAMAHA GL1 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 26.99$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;


            case(2) : System.out.println("HERE ARE SOME LANIKAI UKULELE YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("LANIKAI LU21 NATURAL FOR 20.99$" + ":::: PRESS 1 TO BUY");
                System.out.println("LANIKAI LU-11 FOR 22.99$" + ":::: PRESS 2 TO BUY");
                System.out.println("LANIKAI MA5T OP FOR 28.99$" + ":::: PRESS 3 TO BUY");
                int d = sc.nextInt();
                switch(d)
                {
                    case(1) : System.out.println("LANIKAI LU21 NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 20.99$ ");
                        break;
                    case(2) : System.out.println("LANIKAI LU-11 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 22.99$ ");
                        break;
                    case(3) : System.out.println("LANIKAI MA5T OP IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 28.99$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }

            case(3) : System.out.println("HERE ARE SOME FENDER UKULELE YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("FENDER VENICE SOPRANO FOR 39.99$" + ":::: PRESS 1 TO BUY");
                System.out.println("FENDER FULLERTONE TELE FOR 47.99$" + ":::: PRESS 2 TO BUY");
                System.out.println("FENDER AVALON FOR 54.99$" + ":::: PRESS 3 TO BUY");
                int o = sc.nextInt();
                switch(o)
                {
                    case(1) : System.out.println("FENDER VENICE SOPRANO IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 39.99$ ");
                        break;
                    case(2) : System.out.println("FENDER FULLERTONE TELE IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 47.99$ ");
                        break;
                    case(3) : System.out.println("FENDER AVALON IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 54.99$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            default :
                System.out.println("INVALID INPUT");
        }
    }
    void piano()
    {
        System.out.println("HERE ARE SOME PIANO BRANDS YOU WOULD LOVE TO PLAY  : ");
        System.out.println("PRESS 1 TO BUY YAMAHA PIANO STARTING FROM 999$");
        System.out.println("PRESS 2 TO BUY KAWAI PIANO STARTING FROM 13999$");
        System.out.println("PRESS 3 TO BUY GROTRIAN PIANO STARTING FROM 24999$");
        int z = sc.nextInt();
        switch(z)
        {
            case(1) : System.out.println("HERE ARE SOME YAMAHA PIANO YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("YAMAHA ARIUS YDP-145 NATURAL FOR 999$" + ":::: PRESS 1 TO BUY");
                System.out.println("YAMAHA ARIUS YDP-165R FOR 1599$" + ":::: PRESS 2 TO BUY");
                System.out.println("YAMAHA CLP-725 FOR 5999$" + ":::: PRESS 3 TO BUY");
                int a = sc.nextInt();
                switch(a)
                {
                    case(1) : System.out.println("YAMAHA ARIUS YDP-145  NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 999$ ");
                        break;
                    case(2) : System.out.println("YAMAHA ARIUS YDP-165R IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 1599$ ");
                        break;
                    case(3) : System.out.println("YAMAHA CLP-725 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 5999$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");

                }
                break;
            case(2) : System.out.println("HERE ARE SOME KAWAI PIANO YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("KAWAI KDP 120 FOR 13999$" + ":::: PRESS 1 TO BUY");
                System.out.println("KAWAI US50 FOR 20999$" + ":::: PRESS 2 TO BUY");
                System.out.println("KAWAI CA28G FOR 29999$" + ":::: PRESS 3 TO BUY");
                int l = sc.nextInt();
                switch(l)
                {
                    case(1) : System.out.println("KAWAI KDP 120 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 13999$ ");
                        break;

                    case(2) : System.out.println("KAWAI US50 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 20999$ ");
                        break;

                    case(3) : System.out.println("KAWAI CA28G IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 29999$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");

                }
                break;
            case(3) : System.out.println("HERE ARE SOME GROTRIAN PIANO YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("GROTRIAN G113 FOR 24999$" + ":::: PRESS 1 TO BUY");
                System.out.println("GROTRIAN WGS116 FOR 29999$" + ":::: PRESS 2 TO BUY");
                System.out.println("GROTRIAN G118 FOR 35999$" + ":::: PRESS 3 TO BUY");
                int  g= sc.nextInt();
                switch(g)
                {
                    case(1) : System.out.println("GROTRIAN G113 SOPRANO IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 24999$ ");
                        break;

                    case(2) : System.out.println("GROTRIAN WGS116 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 29999$ ");
                        break;

                    case(3) : System.out.println("GROTRIAN G118 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE 35999$ ");
                        break;

                }
                break;
            default :
                System.out.println("INVALID INPUT");
        }
    }

    void rent()
    {
        System.out.println("WHAT WOULD YOU LIKE TO BUY?");
        System.out.println("PRESS 1 FOR ACOUSTIC GUITAR");
        System.out.println("PRESS 2 FOR UKULELE");
        System.out.println("PRESS 3 FOR PIANO");
        int y = sc.nextInt();
        if(y==1)
        {
            GuitarRent();
        }
        else if(y==2)
        {
            ukuleleRent();
        }


        else if(y==3)
        {
            pianoRent();
        }
        else
        {
            System.out.println("INVALID INPUT");
        }
    }

    void GuitarRent()
    {
        System.out.println("HERE ARE SOME GUITAR BRANDS YOU WOULD LOVE TO PLAY  : ");
        System.out.println("PRESS 1 TO RENT YAMAHA GUITARS STARTING FROM 6$");
        System.out.println("PRESS 2 TO RENT CORT GUITARS STARTING FROM 9$");
        System.out.println("PRESS 3 TO RENT FENDER STARTING FROM 12$");
        int z = sc.nextInt();
        switch(z)
        {
            case(1) : System.out.println("HERE ARE SOME YAMAHA GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("YAMAHA C40 CLASSICAL NATURAL FOR 6$ PER DAY" + ":::: PRESS 1 TO RENT");
                System.out.println("YAMAHA FS80C NATURAL FOR 9$" + ":::: PRESS 2 TO RENT");


                System.out.println("YAMAHA F280 BLACK FOR 12$" + ":::: PRESS 3 TO RENT");
                int a = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int rg1=sc.nextInt();
                switch(a)
                {
                    case(1) : System.out.println("YAMAHA C40 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 6*rg1 + "$");
                        break;
                    case(2) : System.out.println("YAMAHA FS80C IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 9*rg1 + "$" );
                        break;
                    case(3) : System.out.println("YAMAHA F280 BLACK IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 12*rg1 + "$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(2) : System.out.println("HERE ARE SOME CORT GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("CORT AF500C NATURAL FOR 9$" + ":::: PRESS 1 TO RENT");
                System.out.println("CORT AD180 NATURAL FOR 12$" + ":::: PRESS 2 TO RENT");
                System.out.println("CORT EARTH 60ce OP FOR 14$" + ":::: PRESS 3 TO RENT");


                int b = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int rg2=sc.nextInt();
                switch(b)
                {
                    case(1) : System.out.println("CORT AF500C NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 9*rg2 + "$");
                        break;
                    case(2) : System.out.println ("CORT AD180 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 12*rg2 + "$ ");
                        break;
                    case(3) : System.out.println("CORT EARTH 60ce OP IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 14*rg2 + "$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(3) : System.out.println("HERE ARE SOME FENDER GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("FENDER SA 135C FOR 14$" + ":::: PRESS 1 TO RENT");
                System.out.println("FENDER SA 150C FOR 16$" + ":::: PRESS 2 TO RENT");
                System.out.println("FENDER CD-60 FOR 19" + ":::: PRESS 3 TO RENT");
                int c = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");


                int rg3=sc.nextInt();
                switch(c)
                {
                    case(1) : System.out.println("FENDER SA 135C IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 14*rg3 + "$ ");
                        break;
                    case(2) : System.out.println("FENDER SA 150C  IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 16*rg3 + "$ ");
                        break;
                    case(3) : System.out.println("FENDER CD-60 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 19*rg3 + "$ ");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            default :
                System.out.println("WRONG INPUT");
        }
    }
    void ukuleleRent()
    {
        System.out.println("HERE ARE SOME UKULELE BRANDS YOU WOULD LOVE TO PLAY  : ");
        System.out.println("PRESS 1 TO RENT YAMAHA UKULELE STARTING FROM 1$");


        System.out.println("PRESS 2 TO RENT LANIKAI UKULELE STARTING FROM 3$");
        System.out.println("PRESS 3 TO RENT FENDER UKULELE STARTING FROM 5$");
        int z = sc.nextInt();
        switch(z)
        {
            case(1) : System.out.println("HERE ARE SOME YAMAHA UKULELE YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("YAMAHA INT-UK21-LD  NATURAL FOR 1$" + ":::: PRESS 1 TO RENT");
                System.out.println("YAMAHA RVL-UK21 BLACK FOR 3$" + ":::: PRESS 2 TO RENT");
                System.out.println("YAMAHA GL1 FOR 5$" + ":::: PRESS 3 TO RENT");
                int a = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int u1 = sc.nextInt();
                switch(a)
                {
                    case(1) : System.out.println("YAMAHA INT-UK21-LD  NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 1*u1 + "$ ");
                        break;
                    case(2) : System.out.println("YAMAHA RVL-UK21 BLACK IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 3*u1 + "$ ");
                        break;
                    case(3) : System.out.println("YAMAHA GL1 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 5*u1 + "$ ");


                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(2) : System.out.println("HERE ARE SOME LANIKAI GUITARS YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("LANIKAI LU21 NATURAL FOR 3$" + ":::: PRESS 1 TO RENT");
                System.out.println("LANIKAI LU-11 FOR 5$" + ":::: PRESS 2 TO RENT");
                System.out.println("LANIKAI MA5T OP FOR 7$" + ":::: PRESS 3 TO RENT");
                int d = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int u2 = sc.nextInt();
                switch(d)
                {
                    case(1) : System.out.println("LANIKAI LU21 NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 3*u2 + "$ ");
                        break;
                    case(2) : System.out.println("LANIKAI LU-11 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 5*u2 + "$ ");
                        break;
                    case(3) : System.out.println("LANIKAI MA5T OP IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 7*u2 + "$ ");
                        break;


                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(3) : System.out.println("HERE ARE SOME FENDER UKULELE YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("FENDER VENICE SOPRANO FOR 5$" + ":::: PRESS 1 TO BUY");
                System.out.println("FENDER FULLERTONE TELE FOR 7$" + ":::: PRESS 2 TO BUY");
                System.out.println("FENDER AVALON FOR 11$" + ":::: PRESS 3 TO BUY");
                int o = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int u3 = sc.nextInt();
                switch(o)
                {
                    case(1) : System.out.println("FENDER VENICE SOPRANO IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 7*u3 + "$ ");

                        break;
                    case(2) : System.out.println("FENDER FULLERTONE TELE IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 9*u3 + "$ ");
                        break;
                    case(3) : System.out.println("FENDER AVALON IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 11*u3 + "$ ");


                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            default :
                System.out.println("INVALID INPUT");
        }
    }
    void pianoRent()
    {
        System.out.println("HERE ARE SOME PIANO BRANDS YOU WOULD LOVE TO PLAY  : ");
        System.out.println("PRESS 1 TO RENT YAMAHA PIANO STARTING FROM 399$");
        System.out.println("PRESS 2 TO RENT KAWAI PIANO STARTING FROM 5999$");
        System.out.println("PRESS 3 TO RENT GROTRIAN PIANO STARTING FROM 11999$");
        int z = sc.nextInt();
        switch(z)
        {
            case(1) : System.out.println("HERE ARE SOME YAMAHA PIANO YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("YAMAHA ARIUS YDP-145 NATURAL FOR 399$" + ":::: PRESS 1 TO RENT");
                System.out.println("YAMAHA ARIUS YDP-165R FOR 999$" + ":::: PRESS 2 TO RENT");
                System.out.println("YAMAHA CLP-725 FOR 1499$" + ":::: PRESS 3 TO RENT");


                int a = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int p1=sc.nextInt();
                switch(a)
                {
                    case(1) : System.out.println("YAMAHA ARIUS YDP-145  NATURAL IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 399*p1 +"$");
                        break;
                    case(2) : System.out.println("YAMAHA ARIUS YDP-165R IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 999*p1 +"$");
                        break;
                    case(3) : System.out.println("YAMAHA CLP-725 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 1499*p1 +"$");
                        break;
                    default :
                        System.out.println("INVALID INPUT");

                }
                break;
            case(2) : System.out.println("HERE ARE SOME KAWAI PIANO YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("KAWAI KDP 120 FOR 5999$" + ":::: PRESS 1 TO RENT");
                System.out.println("KAWAI US50 FOR 7999$" + ":::: PRESS 2 TO RENT");
                System.out.println("KAWAI CA28G FOR 12999$" + ":::: PRESS 3 TO RENT");


                int l = sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int p2=sc.nextInt();
                switch(l)
                {
                    case(1) : System.out.println("KAWAI KDP 120 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 5999*p2 +"$");
                        break;

                    case(2) : System.out.println("KAWAI US50 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 7999*p2 +"$");
                        break;

                    case(3) : System.out.println("KAWAI CA28G IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 12999*p2 +"$");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            case(3) : System.out.println("HERE ARE SOME GROTRIAN PIANO YOU WOULD LIKE TO HAVE YOUR HANDS ON : ");
                System.out.println("GROTRIAN G113 FOR 11999$ " + " :::: PRESS 1 TO RENT");
                System.out.println("GROTRIAN WGS116 FOR 13999$ " + " :::: PRESS 2 TO RENT");
                System.out.println("GROTRIAN G118 FOR 17999$" + ":::: PRESS 3 TO RENT");


                int  g= sc.nextInt();
                System.out.println("HOW MANY DAYS WOULD YOU LIKE TO RENT IT?");
                int p3=sc.nextInt();
                switch(g)
                {
                    case(1) : System.out.println("GROTRIAN G113 SOPRANO IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 11999*p3 +"$");
                        break;

                    case(2) : System.out.println("GROTRIAN WGS116 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 13999*p3 +"$");
                        break;

                    case(3) : System.out.println("GROTRIAN G118 IS A GREAT CHOICE ");
                        System.out.println("YOUR TOTAL WILL BE : " + 17999*p3 +"$");
                        break;
                    default :
                        System.out.println("INVALID INPUT");
                }
                break;
            default :
                System.out.println("INVALID INPUT");
        }
    }




    public static void main(String args[])
    {
        MusicShop obj = new MusicShop();
        System.out.println("------WELCOME TO BEETHOVENS MUSIC SHOP------");
        System.out.println("--------------------------------------------------");
        System.out.println("  ");
        obj.RentBuy();
        System.out.println("   ");

        System.out.println("THANK YOU FOR SHOPPING");
    }
}
