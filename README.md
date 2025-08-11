<img width="1229" height="898" alt="image" src="https://github.com/user-attachments/assets/c35738c1-ff99-4f56-8832-4fa8225c696d" /># unity-open-OBS-by-coding
Well, sometimes unity can not open OBS successfully, and OBS shows some errors about documents like en-US.ini or something. To solve this problem, just need change the dress of OBS exe.

So, steps are blow.  
Let us look at the script.

It is a easy script,and u just bind a button and click the button, that everything will be done.
And let us talk about the error,shows "can not find en-US.ini""can not load locale" or something.

At that time, we need to find the OBS.Ink, than copy its address, and put in obsPath in inspector in unity.
Which means the obsPath in script must be set to public, so you can change it.
<img width="2221" height="113" alt="image" src="https://github.com/user-attachments/assets/25ddb286-a0a5-4dbe-8d82-ee6e6a5914c3" />
The last step is click the button, wait a min, OBS will be opened.
