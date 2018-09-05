# RetroArch-174-and-above-Cheats
Cheats for CPS1 and CPS2 Games under FBA Core/s

Note: Sometimes, depending on the Game, it will not follow a Hex Value. There are those Games where the Value must match, for example, the Time Remaining like in X-Men-COTA

Games or Cores that do NOT work when trying to Search for Cheats. To be Continued

Problem: You Initiate a Search. You return to the Game, and get hit, or let the Game Time run down. You go back into the Search and go to the Values or Less Than and try to enter that......but it says the Search has not yet been Initiated.....but you just did earlier!!!! So until there is a fix, so far, these Games/Roms will not work with the RetroArch Cheat Search/Creation Tool.

I have also Tested the Cheat Search/Creation on my Computer, but it gave the same result.

PrBoom - doom.wad

FBA -

1943 - 1943-The Battle of Midway

1944 - 1944-The Loop Master - Cheat Address System does not go high enough ( 0x921D51 )

sf - Street Fighter

sfzch - Street Fighter Zero (CPS Changer)

simpsons2p - The Simpsons - 2 Player


--------------------------------------------------------------------------------------------

Instructions to find and Make Cheats. Let us start with msh (Marvel Super Heroes), since it is what I am looking for currently:

1: After Running a Game, and getting everything ready, enter the RA Menu

2: Start by going into the Official FB Alpha Cheat Listings and open msh.ini . This must be done to better find the Cheats. For this, just think of the 0xFFxxxx as being 0x00xxxx . You will notice that when Searching, the The Cheat you are looking for will VERY closely match the Official Code......just will either be 1 less or more Digit Off from XxXXXXX# . So you just need to look for the X Results 0xFFXXX# that closely match. Hope I worded that correctly. LOL. Anyway.....onward Buttercup, there are Codes to find...

3: Go down to Cheats/Start or Continue Cheat Search/Start or Restart Cheat Search

4: From what I can gather, you wont need to adjust anything. Just look at the Official Codes for the Game you want, look at the Value, and if it is 2 Digits, just stay with a 8Bit Search. So just start the Search Process by Pressing X or O (Default). Just in case, give it a Minute before going back to the Game

5: Let the Timer run down a few Seconds, then return to the RA Menu. Go to the Cheats, then go down to 'Search Memory for Values'. You must focus on the Hex Value (##). Since the Official Codes show the Value at 0x99 for Inf Time, we must Search for the Time only in Numbers. No Hex Values used (A,B,C,D,E,F). Just 0-9. So whatever the Timer is at, set the Value for it. You will notice the Decimal Amount is MUCH HIGHER. Dont mind that.

6: Repeat until you get as few Results as possible. Should finally get only 1 Result left. Go down to 'Add the 1 Matches to Your List'.

7: Go back to the Cheat Menu Listings where the top shows "Start or Continue Cheat Search'. Press DPad Up so you see Cheat #0 .

8: You will see the Address is Noted down as 00004809. The Official Code Address is FF4808, meaning RA Address is 1 more than the FBA Listing. So this is the Correct Address you are looking for. 

9: Press O to go into the Code Editing Mode. We just need to go down to 'Value', and set it for 153 (00000099) . Go Up to the 'Description' and press O. For each Letter, press O to Enter that Letter. Enter the Name of the Cheat you want, then Press Start to Confirm. Press X to go back to the Cheat Listing Menu. Press DPad Left or Right to turn the Code On, go Up to 'Apply Changes' and Press O. Go Back to the Game to Confirm the Code Works.

10: If the Code works, go back to the Cheat Menu Listing, go down to 'Save Cheat File As' and Press O . Enter the Name you want it Designated as. For me, it will be msh to match the Rom Name.

11: Now, knowing how the Cheat Addresses are, we can use this to Add More Cheats without needing to Search for others each time. I have done this with ssf2 and ssf2t . Just requires a little work to figure out which is correct. 

12: go back to the 'Start or Continue Cheat Search' and enter that Menu. Go back down to 'Add the # Matches to Your List' and Press O to add it to your List.

13: For this, we will be looking at the "Infinite Energy PL1'. Go back to the Cheat Menu Listings, Press Up to see Cheat #1, and Press O to Enter that Cheat's Settings.

14: Go down to 'Memory Address' and since it is Less than the 'Inf Time' Address, Press and Hold DPad Left till you reach 4191. Now, from what I have seen, sometimes the last Digit is 1 Digit More that then the FBA Cheat Address, so we will set it for 16786(00004192). We must also go below that Line and adjust 'Browse Address: ########' Section to match 4192. But looking at this, this Section actually helps us figure out that the Address we are looking for is not Correct. This is still Guesswork, but if I am correct, this will be the right choice. Change the Address to 4190 since the "Prev:### Curr:###" Section matches the Decimal Values of what we are looking for. Go back up and change 'Memory Address" to 4190 as well. Go Up to 'Value' and change it to 144 (00000090) for a Full Health Bar. Go up to Description and Press O to go into the Naming Code, and put in "1p inf health" and press Start. Press X to go back to the Cheat Listings and hopefully that Changes we made will stick. If not, you must go back and change it again. I find changing the Addresses first, then Values, then Naming it typically helps.

15: Press DPad Left or Right to turn the Code On, go up to Apply Changes, and go back to the Game. Hopefully, this now works as we intended. SUCCESS!!!!!! Now do the same for the "Inf Super Code.....but this will require extra work. For this, it will have to be like xmvsf where the Level Gauge will need to be 144(90), but we will need to make another Code for the Level (1,2, or 3).

16: Actually, this is a little weird, so we must Search for it the normal way.

17: This will actually give us 8 Results and so far it will stay. So just "Add the 8 Matches to Your List".

17 - Extended: Go to the Cheat Listings and find the closest matching Address to what the FB Alpha Address is. In our case, let's test out 4194. It did show up before in the Modification I tried, but the Value did not match for some reason. Press O to Enter the Settings of the Cheat. Change the Value to 144(90) . It works. Interesting.

18: Go back to the Cheat Listings and time to weed out all the Incorrect Results. To do this, find a Incorrect Match, and Press O to Enter it's Setting Listings. Press DPad Up to go to "Delete This Cheat" and Press O. Keep doing this for the rest of the Codes that are Incorrect.

19: Now lets keep that Super at Max Level Number. Unleash that Super Art Move!!!!!! For this, you need to make it show either 2 or 1. Then VERY quickly get into the Menu. Search for the Number of whart the Level is at. 1 is obviously 1, same with 2, but the Infinity Symbol is 3 apparently. But we need it to continue Changing for each Search to narrow it down. 

19.1 : DAMN IT!!!!!!!!! Wont go lower than 3 Results left. Ggggrrrr. Add those 3. Delete all Results except for the one that shows 4199. This is the Code we want. Enter it's Menu and set the Value to 3. Set the Description as "1p super level 3" and Press Start. You should now have your Super Level at Max Always.

20: I hope that I have Written this as good as possible for Noobs as I can. Being a Noob myself at certain Levels, I hope this helps other Users.

21: NOTE - For those Users who have the 3DS with RetroArch Installed, I have noticed a Issue. For some reason, I can not start up a Search for Cheats for some reason. I have Tested this on my Android Device and found the File Structure is exactly the same. So you will need to Copy over the Cheats Directory from your Vita at "ux0:Data/RetroArch/Cheats" . I suggest taking the entire Directory. Place this in the 3DS RetroArch Folder. This may, or may not work. Hopefully this will get taken care of soon. Until then, just use Gateway Cheat System, NTR if possible or any other Cheat Searching/Creation tool available.

22: Hint for GB / GBC Cheats: If it shows up looking like the GameShark or RAW Address, just slightly rearranged, THAT is the Address you are looking for. 
Example: Street Fighter Alpha (GBC). RAW Address - CF09:63 (Address:Value) or GS - 016309CF (63 is Value, 09CF area)... RA Code Address is just 00000F09 with the Value being 99(63). So pretty easy to find, just find the one that closely matches :D
