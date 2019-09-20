---
layout: post
title: We used sequence
catagories: project
---
we used sequence. Well done us!!!!
this is my legitimate code that is mine and not copied from Ryan Gill: 
    Console.WriteLine("How many children are there? ");
            int child = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("How many sweets do they each have? ");
            int sweet = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("How many ducks were there?");
            int duck = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("How many sweets did each child give each duck? ");
            int sweetGive = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine(@"There were " + child + " children each with a bag containing " + sweet +
                "sweets. They walked past " + duck + " ducks. Each child gave " + sweet + " sweets "
                + "to each of the ducks and ate one themself. They decided to put the rest into a pile.");
            Console.WriteLine("They counted the pile and found it contained " + ((sweet * child) - (duck * sweetGive)) + " sweets.");

            Console.ReadLine();

