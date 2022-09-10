Well, most users of WorldSystem don't want to use the standard worlds and want to add their own.
In the following, I will explain how to do this.

First of all, you need to put your Minecraft worlds to the folder, where WorldSystem searches for templates, this is 
**/plugins/WorldSystem/WorldSources.**

![The worlds in right place](https://i.ibb.co/bRb4Y9L/worldtypes.png) 



I have two different world types as templates: Flatmap & Watermap

After we have done this, we have to tell WorldSystem the names of our Worlds on configure them.
Open the config.yml with a text-editor or like me in the terminal via nano.

![WorldSystem config](https://i.ibb.co/3TbtNq5/pre-1.png)

Under the point **templates** you can set the two template worlds. On the first, so we have to set the name of our world here, in my case Flatmap & Watermap.

After this, we can decide, whether the user is allowed to choose from the templates. If you want your users to be allowed to choose from which world they want to take, set the point **multi_choose** to true, if not set it to false.

After we have done this we are almost done.
We only have to tell WorldSystem the default world, the user gets when multichoose is set to false.
We just have to put the name of the world under the point default.

After this, we are done and can reload our server to use the template worlds.

![WorldSystem Config after setup](https://www.bilder-upload.eu/upload/f189d5-1553885858.png)

**In a nutshell:**
> Put the worlds into worldsources folder
> Put the names in the config.yml under the point templates.
> Set multichoose in config.yml to true or false.
> Set the default world name under the point default.

