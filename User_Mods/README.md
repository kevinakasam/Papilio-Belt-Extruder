# User Mods

This respository is to share your Mods (Mods of my Mods are called Mods in the following). You can add them by submitting a pullrequest.
All my Mods have a sperate folder, that may include further subfolders, please sort your content as described below:

## Table structure

*Thanks to the [Voron_User](https://github.com/VoronDesign/VoronUsers) Repo for this table shematic! 
Update the following table with the information about your mod:
- Your name
- A link to your sub-folder
- A short description of your mod
- The extruder compatibility. Use `:heavy_check_mark:` for :heavy_check_mark:,`:x:` for :x: and `:grey_question:` for :grey_question:

like so:
`
| Creator | [Mod title](link) | Description | :x: | :x: |`

| Creator | Mod title | Description | Papilio | Papilio Lite |
| --- | --- | --- | --- | --- | 
| KevinAkaSam |[XOL2_Mounts](./KevinAkaSam/XOL2_Mounts)| XOL2 Mounts for the Papilio (Lite) including Tap  | :heavy_check_mark: | :heavy_check_mark: |
|  |[Stealthburner_Mount](./KevinAkaSam/Stealthburner_Mount)| Stealthburner Mount for the Papilio Lite  | :x: | :heavy_check_mark: |
| adamstorm | [Filament Sensors](./adamstorm/Filament%20Sensors) | Top Cover with filament sensors | :x: | :heavy_check_mark: |
| cobre | [A4T Extruder Adapters](./cobre/A4T%20Extruder%20Adapters) | Adapter to use Papilio extruder with A4T toolhead | :grey_question: | :heavy_check_mark: |
| hawk16zz | [PapLite Combo Mount](./hawk16zz/Combo_SM_LGX_lite_for_Frank2.0) | Extra mounting options for the PapLite with Frank2.0 | :x: | :heavy_check_mark: |
|  | [PapLite Strain Relief](./hawk16zz/Mountable_LGX_Lite_strain_relief) | Cable Strain Relief Bracket for PapLite | :x: | :heavy_check_mark: |
|  | [PapLite Front EBB36](./hawk16zz/Front_EBB36_PapLite) | Mount to attach a EBB36 to the Front of the PapLite | :x: | :heavy_check_mark: |
| n4t3 | [Papilio Top Cover HGX Collet](./n4t3/Papilio_HGX_Collet) | Top Cover to attach HGX Collet to top | :x: | :heavy_check_mark: |
|  | [Papilio Top Cover M6 Bowden Dual](./n4t3/Papilio_M6_Bowden_Dual) | Top Cover to attach M6 Bowden Coupler to top and bottom | :x: | :heavy_check_mark: |
|  | [Papilio Top Cover M6 Bowden](./n4t3/Papilio_M6_Bowden) | Top Cover to attach M6 Bowden Coupler to top | :x: | :heavy_check_mark: |
| theFPVgeek | [FlexiPap](./theFPVgeek/FlexiPap) | Modified Papilio Lite TPU Cover and HGX 1.x geared Upper Base for <95A flexible filaments | :x: | :heavy_check_mark: |

## How to create a pull request 

1. Create a fork of the respository
    - You can find a Button labeled `Fork` at the top right. Clinking on that creates a copy aka fork of this respository in your GitHub account.

2. Create a new folder
    - Navigate into the Mod folder you want to upload your Mod to.
    - Click on `Add file` -> `Create new file`. Then type `YourNickname/YourModName/README.md` to create your folder (click on `commit new file`).
    - If you plan to upload more than one Mod, add simply add more subfolders in your folder like `YourNickname/YourFirstModName/README.md` and `YourNickname/YourSecondModName/README.md` and so on. 
    - Please use short folder names.

3. Edit README and add your files
    - Click on the README.md and then on the pencil on the right top/center to edit the README. Add all required information as described below.
    - Click on `Add file` -> `Upload files` to upload all your Mod files.
    - The stock title of a commit is `Add files via upload` replace that with the title of your Mod.

4. Edit the main README.md of the Mod
    - Navigate back to the Mod folder you made your Mod for. Edit this file and add your mod to the alphabetic table by adding a new line with `| Creator | [Mod title](link) | Description | | :x: | :x: |`
    - The `link` for the `[Mod title](link)` should look like that: `./YourNickname/YourModName` just like you did above
    - Example: `| KevinAkaSam | [Modifius](./KevinAkaSam/Modifius) | Modifius adds ...  | :grey_question: | :grey_question: |`
    - Note `Modifius` is just an idea, yours may be called `Adaption to bearing size xy`

5. Submit the Pullrequest
    - Navigate back to this respository (not the one you forked) and click on `Pull requests` next to `<> Code` `© Issues`
    - Click on the green square on the right `New pull request`
    - A new dialog/window opens and starts with:
        >Compare changes
        >
        >Compare changes across branches, commits, tags, and more below. If you need to, you can also `compare across forks`.
    - Click on the `compare across forks` and at the line below select your forked respository as `head respository`
    - Add you Mod name as title of the pullrequest, add the information to the form and click on  `Create Pull Request` at the very end.
    - If you did anything right we will merge your pullrequest :)
 
## Create a folder

To add your work create a folder that has the following structure:

    - Main respository `User-Mods` 
        - Nickname Subfolder eg. `KevinAkaSam`
            - Modname Subfolder eg. `Modifius`
            - Modname Subfolder eg. `Modimedi`
        - Nickname Subfolder eg. `SamAkaKevin`
            - Modname Subfolder eg. `Mod_A`
            - Modname Subfolder eg. `Mod_B`
