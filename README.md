# Github-Container-Package-Examples
This Repository contains several Container packages, all published by multiple yml workflow files, using `IMAGE ID` for the names. We will use each yml workflow file for a seperate package being published to github. Please see the diagram below to see how this repository works:

![image](https://github.com/user-attachments/assets/5dee0a41-054b-407a-9285-133e79cee522)

Package A (or as I like to call it, `Example Package 1`) is getting deployed with the workflow file main.yml. Then there’s Package B, which is rolling out with main2.yml, and it just keeps going from there.

You can totally set each package to point to a specific directory for storing its code. I didn’t bother with that in my setup, but honestly, it’s a pretty smart move. By organizing your packages into their own folders, you make everything way easier to manage. It helps keep things tidy and makes it simpler to handle updates down the line. Plus, it just feels good to have a clean project structure, you know?
