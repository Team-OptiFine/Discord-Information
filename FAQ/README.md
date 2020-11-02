<!--
source: https://github.com/Team-OptiFine/OptiBot/blob/38692ca84ed61804f2ecbb9b955726ae5d59354d/modules/util/faq.js

-->

<div align="center">
  <h1>General</h1>
</div>

### When is `[version/feature/something else]` gonna be done!?!?
When it's done. These things take time, and unfortunately, it is simply not realistic for us to give an official estimate on any OptiFine-related project.

### What are "Preview Versions", and where can I get them?
"Preview Versions" are OptiFine's "beta" or "alpha" releases. They're usually buggy and unstable, and NOT recommended for regular usage. However, if you'd like to use these versions (especially to help find bugs), you can head to https://optifine.net/downloads and click on "Preview Versions" next to the given version of Minecraft you'd like to use. Do note that Preview Versions are only temporary, and will be removed from the website after the given version has been tested and stabilized. Preview versions are not guaranteed to be available for any version of the game.

### I'm trying to download OptiFine, but the download button won't show. What do I do?
This is usually caused by ad-blockers. Temporarily disable yours, or switch to ~~the arguably superior~~ uBlock Origin: https://github.com/gorhill/uBlock#installation

Additionally (as strange as it might sound), some antiviruses may also block the download button from showing in some cases. In this case, simply disable your antivirus temporarily before trying to download OptiFine again. **Don't forget to re-enable it when you're done!**

### What is "MCP"?
Mod Coder Pack, or MCP, is a tool that helps to decompile and recompile Minecraft. This allows a majority of mods to exist, including Forge and OptiFine. For technical details, you can check out these links:

https://technical-minecraft.fandom.com/wiki/MCP
https://minecraft.gamepedia.com/Programs_and_editors/Mod_Coder_Pack

### Why does OptiFine still use MCP as opposed to the new official Mojang mappings?

The Mojang mappings are officially stated as being for "internal, reference purposes" and are completely unclear as to how they can be used. As such, many major Minecraft mod entities like Forge, Fabric, and of course OptiFine are all staying away from using these mappings at all until this issue is resolved by Mojang's legal team.

For more information, check out this article written by [@cpw](https://twitter.com/voxcpw): https://cpw.github.io/MinecraftMappingData

### Why isn't OptiFine open-source?
The core of OptiFine consists of many, various changes to Minecraft's rendering code. Rather than simple patches, these are significant reorganizations. This means publishing the full source code of OptiFine would be a direct violation of Minecraft's EULA. Technically, it would be possible to extract the actual changes as patches, which can then be published to GitHub as source code. However, there are a number of issues with this idea. First, OptiFine is built on a custom version of Mod Coder Pack. This non-standard version of MCP is used to allow OptiFine to start development on new versions of the game much, much earlier. During this time, official MCP mappings are either completely missing, or otherwise very unstable. Unfortunately, according to the MCP license and Terms of Usage, modified versions of MCP scripts are not allowed to be distributed. This means that, even if OptiFine patches were released, nobody else would be able to collaborate on the code, defeating the entire purpose of going open-source. Even if somehow *all of that* was solved, this would still mean significantly changing how OptiFine development is handled. <!--OB-replace-->**@sp614x**<!--OB-<@202558206495555585>--> does not work on the mod using patches, which means he would have to either merge the patches manually, or completely change his entire workflow to use patches. Changing the development process like this would not be a trivial task in the slightest.

In summary, due to a *multitude* of legal and technical complications, <!--OB-replace-->**@sp614x**<!--OB-<@202558206495555585>--> cannot make OptiFine open-source.

### Since OptiFine isn't open-source, what happens if the developer disappears, or just gives up and quits?
First of all, it's almost certainly *not* gonna happen any time soon. Regardless, if it ever comes down to it, Java programs are not difficult to decompile. If <!--OB-replace-->**@sp614x**<!--OB-<@202558206495555585>--> ever went missing, virtually anyone with the right knowledge could decompile OptiFine in its entirety, compare it to decompiled vanilla Minecraft code, and extract the patches.

Alternatively (that being, the much better outcome), if <!--OB-replace-->**@sp614x**<!--OB-<@202558206495555585>--> ever decides to quit, he is willing to publish OptiFine's patches to GitHub. With that said, there are currently no plans to stop OptiFine development. Either way, OptiFine can live again.

### Why hasn't Mojang adopted OptiFine as an official part of the game?
The original story most people know of is this:

> Mojang *did* try to buy OptiFine, but they did not want the entirety of the mod, which lead to the deal falling through. 

The reality is, Mojang and Microsoft cannot accept the modifications OptiFine has made, due to a legal policy held between both companies that does not allow for external code to be accepted outside of their internal development team. Therefore, there's nothing that OptiFine *could* do to get it added into vanilla Minecraft. While most people assume it's because of something like the zoom or shader features that this never happened, it's really just a matter of legal policies that cannot be bypassed.

### Can I include OptiFine in my modpack/custom launcher/custom client?

Sorry, but no. If you need OptiFine in any of your projects, you can direct users to our website.

<div align="center">
  <h1>Donations & Capes</h1>
</div>

### Will OptiFine capes be affected by the upcoming account migration?
We are seeing this question a lot. Unfortunately, we simply do not have enough information about the technical changes (such as possible changes to usernames or the UUID system) to definitively answer this. As always, we will keep you informed should anything major happen.

### What happens if I have a vanilla cape AND an OptiFine cape active at the same time?
OptiFine capes override all official/vanilla capes by default. To change this, open Minecraft with a recent version of OptiFine and navigate to `Options > Skin Customization > OptiFine Cape > Open Cape Editor`. From here, you can deactivate (or re-activate) your OptiFine cape.

### I moved my cape to another account, but it just disappeared! What do I do?
OptiFine capes are immediately disabled when transferred to prevent abuse. The cape can be activated again by the new cape owner by opening the game and navigating to `Options > Skin Customization > OptiFine Cape > Open Cape Editor`. From here, the cape can be activated once again.

### How do I change my donation email?
Unfortunately, it is currently not possible to change donation emails. We don't know if this functionality will be added in the future.

### Can donations be refunded?
Yes, donations can be refunded within 30 days of payment. You must email Paymentwall at [support@paymentwall.com](mailto:support@paymentwall.com) to begin the refund process. Make sure you have your receipt available!

### Why does it say my banner cape design is invalid?
There are two possible reasons:
1. You've gone over the 8 pattern limit (does not include the base color)
2. Your banner design includes the Mojang logo.

### Will I have to move my cape if I change my Minecraft username?
Usually, no. OptiFine will update your username automatically, but this process may take up to 24 hours. If you need the cape sooner, you can move it manually at https://optifine.net/login

### How do I get a fully custom OptiFine cape?
You cannot, for various reasons:

1. Minecon capes.
2. Mojang staff capes.
3. Any other vanilla Minecraft cape.
4. NSFW and NSFL imagery.
5. Offensive imagery.
6. Copyrighted imagery.

Custom capes for everyone would require some form of moderation to prevent these types of capes being uploaded. Given how many people have donator capes, and how many would likely start submitting the type of things listed above, this is simply and completely unrealistic.

In addition, you might be aware that there are already a few custom capes in existence. These capes were only gifted to a very small number of people for very specific, individual reasons. Please **do not** ask for one yourself. <!--OB-replace-->**@sp614x**<!--OB-<@202558206495555585>--> himself has stated that he will not be adding any more custom capes.

### My cape was stolen! What do I do?
First of all, please note: **Administrators CAN NOT and WILL NOT move capes for you!!!**

With that said, login at https://optifine.net/login, and simply update the username for the cape. Make sure it is also marked as locked. If you cannot move the cape, just lock it for now and wait 24 hours before trying to update the username. **If you're not the person who made the donation for the cape, you will have to ask the original donator to perform these actions.** If your friend gave you the cape, ask them.

In a majority of cases, the following steps are probably not be necessary. However, if you want to be absolutely sure you're safe, this is the way to go: **First, scan your computer, and change your passwords IMMEDIATELY.** This should include your Email account, your Minecraft/Mojang account, and your OptiFine.net account. Ideally, it should also be in that exact order. All of this is to ensure no strangers have access to any of these relevant accounts. After the passwords have been updated, log in at https://optifine.net/login and follow the same steps mentioned above.

### Why isn't my cape showing?
There are several possible reasons that your donator cape may not display in-game. 

#### 1. Capes are disabled through in-game options.
Check that both of these options are turned ON.
```Skin Customization... > Cape: ON```
```Video Settings... > Details... > Show Capes: ON```

#### 2. Your cape has been automatically deactivated.
This can happen if your cape was recently transferred to your account.

In options, navigate to the following:
```Skin Customization... > OptiFine Cape... > Open Cape Editor```
From here, the OptiFine cape editor should open in your web browser. Here, you can see if your cape has been deactivated, and an option to reactivate it.

#### 3. You recently changed your Minecraft username.
OptiFine capes are linked your account at all times, even when changing your username. Capes will automatically update to your new username within a 24-48 hour period, but if needed, you can simply update the username manually.

#### 4. Your internet is not loading capes due to caching.
There is a *very* slim chance that your internet service provider may be caching certain things "for your convenience." There have been a small number of cases where this was the issue, and the only solution was to temporarily switch to a mobile network. The cape should reappear on the normal connection within several days.

#### 5. Your donation is still being processed.
If you've only recently made a donation, in some cases it may take up to several days before the donation is fully processed and your cape can be activated. If you do not receive your cape within a week of donating, please try following the steps listed above before contacting <!--OB-replace-->**@sp614x**<!--OB-<@202558206495555585>-->.

### Are OptiFine capes being removed due to Mojang's EULA changes?
Short answer: For now, no.

Long answer: We are fully aware of the commercial usage guidelines recently published by Mojang, and what it states about capes. However, it should be noted that the actual terms discussing capes have not been changed in over 3 years (as of writing). We have not yet heard anything new from sp614x himself, and all things considered, we can assume that OptiFine is in the clear. For the time being, **OptiFine is not planning on changing anything related to capes.** Of course, should anything change, we will inform you all as soon as possible.

### I tried opening the cape editor and nothing happens. Why won't it work?
This is a relatively common issue with early versions of OptiFine's new cape editor. For now, you can use this as a workaround:
1. Attempt to open the cape editor in-game at least once. **Make sure your game stays open from this point forward!**
2. Open your `.minecraft` directory. (On Windows, this is typically located at `C:\Users\[YOUR NAME]\AppData\Roaming\.minecraft`)
3. Navigate to the `logs` folder.
4. Find the file `latest.log` and open it with any text editor. If you don't have file extensions enabled, this will appear as a text file called `latest`.
5. Scroll to the bottom of the log and find the text "Couldn't open url"
6. This text will be immediately followed by the URL you need. Copy and paste it into your browser, without the quotes.
7. Edit your cape as desired.

<div align="center">
  <h1>Compatibility</h1>
</div>

### Can I force OptiFine to install on a different, newer version of Minecraft?
No. Each version of OptiFine is specifically developed for a single version of the game. Even if you *somehow* managed to force install OptiFine on a different version, it would more than likely crash immediately, or at the VERY least, have a multitude of bugs and other issues.

### Why won't OptiFine work on my cracked/custom/third-party launcher?
Generally, your mileage will vary when using anything other than the official Mojang launcher, of which OptiFine was designed to be used with.

For users with cracked/pirated launchers, **we will not help you.** Buy the game first.

### Why can't I use OptiFine with Forge?
Normally, you should be able to. Most versions of OptiFine are compatible with Forge. However, you must use a specific version of the modloader. You can find which version of Forge you need to use by checking the Forge version listed next to the OptiFine version on https://optifine.net/downloads. Alternatively, you can check the OptiFine changelogs, which can be found in the same area.

Please note that *some* versions of OptiFine are NOT compatible with Forge at all. This includes most versions between 1.13-1.14.4. Some versions may also state "Internally compatible with Forge", but this does NOT mean you can load and play OptiFine with Forge.

### Is OptiFine compatible with Fabric?
Officially, no. OptiFine does not plan to add native support for Fabric like it currently does for Forge. However, there is a third-party mod that adds compatibility for OptiFine on Fabric. You can check it out here: https://www.curseforge.com/minecraft/mc-mods/optifabric

<div align="center">
  <h1>Using OptiFine</h1>
</div>

### How can I get the best performance with OptiFine?
OptiFine comes with many optimizations that should increase overall performance without much setup. However, depending on your computer's hardware, you can usually further increase performance by tweaking the in-game options and finding the trade-off between quality and performance that works best in your case. The new options provided by OptiFine include tooltips that explain how each option works, and how to best configure most settings.

### I have a powerful graphics card, but Minecraft keeps using integrated graphics. How do I fix this?
Note that these instructions only work for modern versions of Windows 10.

1. Open the Settings app.
2. Navigate to System > Display, and scroll down until you see "Graphics Settings".
3. Select "Browse", then locate and add `javaw.exe`.
   - The location of this file will vary, but you can usually find it at `C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin`.
4. Select "Java(TM) Platform SE Binary", and then select "Options".
5. Set the graphics preference to "High Performance", and then save.

Video Instructions: https://i.hiitsdevin.dev/captures/hid_152649.mp4 (Thanks to <!--OB-replace-->**@Devin**<!--OB-<@564848790478127139>-->  for making this!)

### How much RAM should I allocate to Minecraft?
Before answering, we'd like to first inform you of the *very* common misconception that more RAM = better. This is NOT true, and in fact, this can result in overall *worse* performance if you allocate too much RAM to the game. This is due to how Java handles something called "garbage collection", which is basically how the game deals with data it is no longer actively using. When giving Java too much RAM, this means the garbage collector will have much more data it needs to remove all at once, which results in massive lag spikes and stuttering framerates.

With that said... it depends. The amount of RAM you need to allocate will depend on how many mods you're using, your preferred render distance, and various other factors. You should only allocate enough RAM to the point where Minecraft's memory usage tops out at **~70%**, and never falls below **~50%**. You can view Minecraft's memory usage by pressing F3 while in-game, and looking at the top-right of the screen. You should see a line starting with "Mem:" followed by the percentage.

### Why are there two numbers for FPS?
OptiFine changes the framerate counter to display the both the average *and* minimum FPS, where vanilla only shows the average. This gives a much more accurate representation of your games performance, since the minimum framerate reflects how smooth the game might actually feel to play.

### How do I enable V-Sync?
In Video Settings, drag the "Max Framerate" slider all the way to the left.

<div align="center">
  <h1>Resource Packs</h1>
</div>

### Why can't I use apostrophes or commas when making CIT textures?
Special characters like these must use unicode escape sequences. For example, apostrophes would be `\u0027` and commas would be `\u002c`.

### How do I use OptiFine for snapshot versions of Minecraft?
You cannot. OptiFine does not get developed for snapshot versions of Minecraft, and there are no plans for such projects.

### How do I use OptiFine on Minecraft: Windows 10 Edition/Pocket Edition?
*Note: For the sake of simplicity, these versions will be collectively referred to by their official name: ["Bedrock Edition"](https://minecraft.gamepedia.com/Bedrock_Edition)*

**You cannot.** OptiFine is purely a [Minecraft: Java Edition](https://minecraft.net/store/minecraft-java-edition) mod. The Bedrock Edition of Minecraft is NOT supported by OptiFine, as it uses an entirely different game engine and internally bears little resemblance to Java Edition. Anything that claims to be OptiFine for Bedrock/Pocket Edition is completely fraudulent, and may even be malware. Please be careful of what you're downloading.

<div align="center">
  <h1>Shaders</h1>
</div>

### What are "Internal" shaders?
"Internal" shaders enable OptiFine's shader system without loading any special shader programs (or "packs"). This can be used to test if shaders work at all on your computer (which could be useful if you have potentially outdated hardware), or they can be used to simply and quickly "disable" shaders without having to reload a significant amount of resources.

### Why does my game look brighter/shadeless when using "Internal" shaders?
Most likely you have the shaders option "Old Lighting" disabled. You can find this option on the right panel of the shader packs menu.

### Do shaders support NVIDIA RTX?
No, and for the foreseeable future, they will not. NVIDIA RTX is a very new technology, and unfortunately, the version of OpenGL that Minecraft runs on is too outdated to use it. While some shader packs are developing some form of path tracing (such as SEUS PTGI), this should not be mistaken for RTX technology.

To be clear, this does NOT mean RTX cards cannot run shaders at all. This only means that shaders cannot utilize the new RT cores found in the 20-series graphics cards.

### Can I use shaders without OptiFine?
As far as we're aware, no. Currently, OptiFine is the only known mod that provides support for shader packs. Unfortunately, the original Shaders Mod (of which OptiFine shaders are based off of) no longer seems to be available to download.

<div align="center">
  <h1>Discord</h1>
</div>

### Why doesn't Discord detect Minecraft when using OptiFine?
To be completely honest, we don't know. However, you *can* try this as a workaround:

1. Make sure the game is currently open and running.
2. Open the settings menu in Discord, and head to the "Game Activity" tab.
3. Click "Add it!" underneath the box labeled "No game detected."
4. Select "Minecraft `[version]`"
5. Click "Add game" and you're done!

#### WARNING: Do NOT enable Discord overlay.
For some reason, this is almost guaranteed to crash your game when OptiFine is installed. We honestly don't know why.

Additionally, there's a chance this whole workaround *may* not work for you at all. Your mileage will vary here, unfortunately. We *still* don't know why. Sorry.

### How do I get the Donator role?
DM (direct message) <!--OB-replace-->**@OptiBot**<!--OB-<@468582311370162176>--> or use the following command in the <!--OB-replace-->**#optibot**<!--OB-<#626843115650547743>--> channel for detailed instructions: `!help dr`

**Remember,

### How do I get the Shader Developer/Texture Artist/Modder role?
These roles are given to users that show proficiency in their given field. If you feel you qualify for one or more of these roles, simply ask any online moderator for assistance. You can summon a moderator with this command: `!modping`

To speed things along, you should include the shader pack/resource pack/mod you've created or contributed to. This would usually be downloads links that include screenshots and proof of your contribution.

### How can I check the progress on upcoming OptiFine versions?
We post progress updates on our Twitter account [@OptiFineNews](https://twitter.com/OptiFineNews).

However, you can also find the progress report directly in our Discord server in the <!--OB-replace-->**#update-x-x-x**<!--OB-<#626843115650547743>--> channel, or by looking at the <!--OB-replace-->update progress voice channel<!--OB-<#663852011154047046>-->.