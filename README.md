# The Ryzen Mobile BIOS Repository

# NOTICE

I am **NOT** responsible for **ANY** damage caused to your laptop through running these files.

So long as you aren't stupid, you won't be able to damage your laptop, just make sure the model numbers match.

### Upgrading your BIOS

1. Find your laptop manafacturer & model.

2. Find the corrosponding model on this repo. If you can't find it - we don't have it.

3. Select a BIOS higher than the one currently installed.

4. Download the .exe & run it.

### Downgrading your BIOS

*This is more involved. Professional users only recommended.*

**DOES NOT WORK ON ASUS LAPTOPS**

1. Find your laptop manafacturer & model.

2. Find the corrosponding model on this repo. If you can't find it - we don't have it.

3. Select the BIOS you wish to move to.

4. Download the .exe and unzip the .exe using 7-zip, save into a fresh folder.

5. Open *platform.ini* with Notepad.

6. Search for `bios_version_check`, set the flag from `flag=1` to `flag=0`

7. Save & close *platform.ini*.

8. Run the .exe in the folder called *H2OFFT-W.exe*

### Contributing

Fork, edit & simply send in a pull request.

### Help

You can get help on a [**discord server**](https://discord.gg/qEAfkuA) that I'm part of.