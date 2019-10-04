
---
layout: post
title: We used conversions
catagories: project
---
I use conversions at some point. Here is the code to prove it that may be mine:

            const double PoundsToDollars = 1.23;
            const double DollarsToPounds = 0.81;
            Console.WriteLine("enter username");
            string username = Console.ReadLine();
            Console.WriteLine("press 1 for pounds to dollars, or 2 for dollars to pounds");
            int option = Convert.ToInt32(Console.ReadLine());
            double convertvalue = Convert.ToDouble(Console.ReadLine());
            switch (option)
            {
                case (1):
                    {
                        double finalvalue = convertvalue * PoundsToDollars;
                        Console.WriteLine(finalvalue + " is how many dollars you would have.");
                        Console.ReadLine();
                        break; 
                    }


                case (2):
                    {
                        double finalvalue = convertvalue * DollarsToPounds;
                        Console.WriteLine(finalvalue + " is how many pounds you would have.");
                        Console.ReadLine();
                        break;

                    }
