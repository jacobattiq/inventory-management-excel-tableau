# Off-Shelves to Back On: A Dive into Inventory Management
My findings from analyzing a sample inventory dataset for a grocery store

A major aspect of supply chain within a company is inventory management. Without proper analysis and tools to keep track of what's in stock, supply chain inefficiencies are almost guaranteed to show up.

In this article, I will present my findings from analyzing a sample inventory dataset for a grocery store, outline the steps I took along the way to help them reconcile their inventory so departments such as logistics, sales, and marketing as accurate, up-to-date information on their products. 

Okay, here we go! 

## Early Stages of Project Development:
Steps I Took Toward Project Completion:

Outline the goals of the project and set a deadline.
Find a sample data set.
Clean and analyze data - Excel and Tableau are key here! 
Final touches and write the article you are reading right now!



I connected with someone on LinkedIn who helped me spark the idea for this project! 

At first, it was tough. I felt I couldn't get a grasp on what needed to be done. However, it's because I was lacking a plan!

I created a Google Doc with notes, steps I wanted to take, my thought process, and the technical skills I wanted to use - Excel (X/VLOOKUP, IFERROR, and filters) and Tableau for creating the tool. 

<img width="1144" height="430" alt="1745090838588" src="https://github.com/user-attachments/assets/017ef58c-b814-4110-83d1-91c45eafe945" />

Actual screenshot from my notes
I decided to take the returned products and merge them with the main dataset to show what products we had in stock and further investigate why they may have been returned. 

Once that was done, it was time to organize, analyze, and start building!

## Cleaning and Organizing Using Excel:
Excel is very powerful tool for data analysis. In fact, it is the most requested technical skill in the field, but it does come with limitations! I think Excel is best for organizing and cleaning data, when it comes to running queries or building visualizations, I leave that up to SQL, Tableau/Power BI, or Python! 

I started in Excel by using XLOOKUP (a simpler and far superior version of VLOOKUP). Then, I consolidated the "Returned Orders" with the main dataset. 

<img width="161" height="82" alt="1745091038199" src="https://github.com/user-attachments/assets/15bfa1e1-a650-4a7f-9e13-51c007ccdc5d" />

Creating an IFERROR statement as a backup if my XLOOKUP did not work out.
Article content
There were more rows, but just an idea of what I was seeing! 


That was about all I had to do in Excel! Tableau took care of the rest (I love Tableau, so this was a big plus for me).

## Building an Inventory Management Tool Using Tableau:
Tableau is my favorite way to analyze data. Combining a user-friendly UI, great online resources posted directly by Tableau, and the ability to post your work to an online forum are some of the many reasons I love it! 

To start, I added some conditions.

<img width="911" height="85" alt="1745256109186" src="https://github.com/user-attachments/assets/d4626c8c-f84f-456f-aa0f-af8ef4becdb2" />

A few I added! 
From there, I continued to keep adding until I had my desired criteria met for a well-rounded dataset! 

Finally, I merged two separate visualizes to create an interactive inventory management tool! By clicking on an individual returned order, it will show you all order details! 



Honestly, it's just easier if you check it out and play around with it! To view the tool I built, please click on this Tableau Public link:

https://public.tableau.com/views/InventoryManagmentTool/Inven_Reconcilliation?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Final Thoughts:
What I have learned from this project is that data analysis is not just presenting numbers but creating new processes and fostering improvement. I was kind of hard on myself, but not including any colorful graphs and fancy PivotTables. However, sometimes it's best to keep it simple. Cut out the fluff and be confident and proud about what you made and what it can provide.

If you made it to the end, thank you! Please reach out if you have questions or would like to chat! 
