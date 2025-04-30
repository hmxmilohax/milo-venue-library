# milo-venue-library

## How to make a proper Pull Request
<ins>**If you are planning on making a pull request to add your venue to this repo, there are a few things to take into count.**</ins>



1. **Directory suggested format**\
	When formatting your directory, it should look something like this\
	![reference_image_og](https://github.com/user-attachments/assets/4e343d05-9759-498a-8c88-504830b353e2)
	- Do not leave loose files like textures around the blend file, put them in their own separate folder beside the Blend file.
	- When making a pull request, make sure you delete "**filename.blend1**" to remove excess bloat.
	- Make sure any duplicate textures or materials are removed before making a pull request.



2. **Console parity**\
	If you are going to make a pull request for your custom Rock Band 3:tm: Venue, please make sure that it works on both Xbox 360 and Playstation 3. (In this case Wii is not accounted for.)\
	We will do testing ourselves to make sure they work, but if they don't, they will be rejected until fixed.



3. **Hardware/Software limits**\
	Limit your venues to 40-50k polygons, this ensures they work at all on console. **This limit is total amount, not per object!**\
	Textures should not be any larger than 512x512.\
> 1024x1024 is supported, but only if you *absolutely* need extra detail! Consider using multiple materials instead.



4. **QC (Quality Control) of your venues.**\
	Make sure that your milos are not corrupted. If they are, there are a multitude of reasons they are.\
	1. You are on an old version of MiloEditor and saved one too many times within the same session.
  	   - FIX: Update [MiloEditor](https://github.com/ihatecompvir/MiloEditor)
	2. You deleted the **uniq2** folder that's required.
  	   - FIX: Replace the milo and start over because that folder is needed.
	3. Your PS3 version of the venue is crashing but your Xbox version is not.
  	   - This is due to normal textures being encoded to the wrong format that PS3 RB3 cannot read properly.
	     - FIX: Update [glTFMilo](https://github.com/ihatecompvir/glTFMilo) and re-convert the glTF to Milo.



# Credits
Personal thanks to these lovely folks for writing this readme.\
[MetricCepheid](https://github.com/MetricCepheid) - Wrote the readme\
[ihatecompvir](https://github.com/ihatecompvir)\
[jnack](https://github.com/jnackmclain)\
[kerneltrap8](https://github.com/kernaltrap8)\
[lunalawl](https://github.com/lunalawl)\
[RazQ](https://github.com/razq)
