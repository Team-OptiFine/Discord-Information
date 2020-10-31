<div align="center">
  <h1>General</h1>
</div>

### When is `[version/feature/something else]` gonna be done!?!?
When it's done. These things take time, and unfortunately, it is simply not realistic to give an official estimate on any OptiFine-related project.

### What are "preview Versions", and where can I get them?
"Preview Versions" are OptiFine's "beta" or "alpha" releases. They're usually buggy and unstable, and NOT recommended for regular usage. However, if you'd like to use these versions (especially to help find bugs), you can head to https://optifine.net/downloads and click on "Preview Versions" next to the given version of Minecraft you'd like to use. Do note that Preview Versions are only temporary, and will be removed from the website after the given version has been tested and stabilized. Preview versions are not guaranteed to be available for any version of the game.

### I'm trying to download OptiFine, but the download button won't show. What do I do?
This is usually caused by ad-blockers. Temporarily disable yours, or switch to ~~the arguably superior~~ uBlock Origin: https://github.com/gorhill/uBlock#installation

### Does OptiFine work on snapshots?
No. OptiFine does not get developed for snapshot versions of Minecraft, and there are no plans for such projects.

### How do I use OptiFine on Minecraft: Bedrock/Pocket Edition?
You cannot. OptiFine is purely a [Minecraft: Java Edition](https://minecraft.net/store/minecraft-java-edition) mod. Anything that claims to be OptiFine for Bedrock/Pocket Edition is completely fraudulent, and may even be malware. Please be careful of what you're downloading.

### Why are there two numbers for FPS?
OptiFine changes the FPS counter to display the both the average *and* minimum FPS, where vanilla only shows the average. This gives a much more accurate representation of your games performance, since the minimum framerate reflects how smooth the game might actually feel to play.

### How do I enable V-Sync?
In Video Settings, drag the "Max Framerate" slider all the way to the left.

### Why doesn't Discord detect Minecraft when using OptiFine?
To be completely honest, we don't know. However, you *can* try this as a workaround:

1. Make sure the game is currently open and running.
2. Open the settings menu in Discord, and head to the "Game Activity" tab.
3. Click "Add it!" underneath the box labeled "No game detected."
4. Select "Minecraft `[version]`"
5. Click "Add game" and you're done!

#### WARNING: Do NOT enable Discord overlay.
For some reason, this is almost guaranteed to crash your game when OptiFine is installed. We honestly don't know why.

Additionally, there's a chance this whole workaround *may* not work for you at all. Generally, your mileage will vary here, unfortunately. We *still* don't know why. Sorry.

### What is "MCP"?
Mod Coder Pack, or MCP, is a tool that helps to decompile and recompile Minecraft. This allows a majority of mods to exist, including Forge and OptiFine. For technical details, you can check out these links:

https://technical-minecraft.fandom.com/wiki/MCP
https://minecraft.gamepedia.com/Programs_and_editors/Mod_Coder_Pack

### Why does OptiFine still use MCP as opposed to the new official Mojang mappings?

The Mojang mappings are officially stated as being for "internal, reference purposes" and are completely unclear as to how they can be used. As such, many major Minecraft mod entities like Forge, Fabric, and of course OptiFine are all staying away from using these mappings at all until this issue is resolved by Mojang's legal team.

For more information, check out this article written by [@cpw](https://twitter.com/voxcpw): https://cpw.github.io/MinecraftMappingData

### Why isn't OptiFine open-source?
The core of OptiFine consists of many, various changes to Minecraft's rendering code. Rather than simple patches, these are significant reorganizations. This means publishing the full source code of OptiFine would be a direct violation of Minecraft's EULA. Technically, it would be possible to extract the actual changes as patches, which can then be published to GitHub as source code. However, there are a number of issues with this idea. First, OptiFine is built on a custom version of Mod Coder Pack. This non-standard version of MCP is used to allow OptiFine to start development on new versions of the game much, much earlier. During this time, official MCP mappings are either completely missing, or otherwise very unstable. Unfortunately, according to the MCP license and Terms of Usage, modified versions of MCP scripts are not allowed to be distributed. This means that, even if OptiFine patches were released, nobody else would be able to collaborate on the code, defeating the entire purpose of going open-source. Even if somehow *all of that* was solved, this would still mean significantly changing how OptiFine development is handled. sp614x does not work on the mod using patches, which means he would have to either merge the patches manually, or completely change his entire workflow to use patches. Changing the development process like this would not be a trivial task in the slightest.

In summary, due to a *multitude* of legal and technical complications, sp614x cannot make OptiFine open-source.

### Since OptiFine isn't open-source, what happens if the developer disappears, or just gives up and quits?
First of all, it's almost certainly *not* gonna happen any time soon. Regardless, if it ever comes down to it, Java programs are not difficult to decompile. If sp614x ever went missing, virtually anyone with the right knowledge could decompile OptiFine in its entirety, compare it to decompiled vanilla Minecraft code, and extract the patches.

Alternatively (that being, the much better outcome), if sp614x ever decides to quit, he is willing to publish OptiFine's patches to GitHub. With that said, there are currently no plans to stop OptiFine development. Either way, OptiFine can live again.

### Why hasn't Mojang adopted OptiFine as an official part of the game?
The original story most people know of is this:

> Mojang *did* try to buy OptiFine, but they did not want the entirety of the mod, which lead to the deal falling through. 

The reality is, Mojang and Microsoft cannot accept the modifications OptiFine has made, due to a legal policy held between both Mojang and Microsoft that does not allow for external code to be accepted outside of their internal development team. Therefore, there's nothing that OptiFine *could* do to get it added into vanilla Minecraft. It has nothing to do with the zoom or shader features that most people think is the reason this never happened. Really, it's a matter of legal policies that cannot be bypassed.

<div align="center">
  <h1>Donations & Capes</h1>
</div>

### How do I change my donation E-mail?
Unfortunately, it is currently not possible to change donation E-mails. We don't know if this functionality will be added in the future.

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

Custom capes for everyone would require some form of moderation to prevent these types of capes being uploaded and used. Given how many people have donator capes, and how many would likely start submitting the type of garbage listed above, this is simply, completely unrealistic.

In addition, you might be aware that there are already a few custom capes in existence. These capes were only gifted to a very small number of people for very specific, individual reasons. Please **do not** ask for one yourself. sp614x himself has stated that he will not be adding any more custom capes.

### My cape was stolen! What do I do?
First of all, please note: __**Administrators CAN NOT and WILL NOT move capes for you!!!**__

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
If you've only recently made a donation, in some cases it may take up to several days before the donation is fully processed and your cape can be activated. If you do not receive your cape within a week of donating, please try following the steps listed above before contacting sp614x.

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

Please note that *some* versions of OptiFine are NOT compatible with Forge at all. This includes most versions between 1.13-1.14.4. Again, check the compatible versions before trying to use Forge.

### Is OptiFine compatible with Fabric?
Officially, no. OptiFine does not plan to add native support for Fabric as it currently does for Forge. However, there is a third-party mod that adds compatibility for OptiFine on Fabric. You can check it out here: https://www.curseforge.com/minecraft/mc-mods/optifabric

<div align="center">
  <h1>Shaders</h1>
</div>

### What are "internal" shaders?
"Internal" shaders enable OptiFine's shader system without loading any special shader programs (or "packs"). This can be used to test if shaders work at all on your computer (could be useful if you have potentially outdated hardware), or they can be used to simply "disable" shaders without having to reload a significant amount of resources.

### Do shaders support NVIDIA RTX?
No, and for the foreseeable future, they will not. NVIDIA RTX is a very new technology, and unfortunately, the version of OpenGL that Minecraft runs on is too outdated to use it. While some shader packs are developing some form of path tracing (such as SEUS PTGI), this should not be mistaken for RTX technology.

To be clear, this does NOT mean RTX cards cannot run shaders at all. This only means that shaders cannot utilize the new RT cores found in the 20-series graphics cards.

### Can I use shaders without OptiFine?
As far as we're aware, no. Currently, OptiFine is the only known mod that provides support for shader packs. Unfortunately, the original Shaders Mod (of which OptiFine shaders are based off of) no longer seems to be available to download.

<div align="center">
  <h1>Discord</h1>
</div>

### How do I get the Donator role?
DM (direct message) OptiBot#8057 with the following command for detailed instructions: `!help dr`

### How do I get the Shader Developer/Texture Artist/Modder role?
These roles are given to users that show proficiency in their given field. If you feel you qualify for one or more of these roles, simply ask any online moderator for assistance. You can summon a moderator with this command: `!modping`

To speed things along, you should include the shader pack/resource pack/mod you've created or contributed to. This would usually be downloads links that include screenshots and proof of your contribution.
