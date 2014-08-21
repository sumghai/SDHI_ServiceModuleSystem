Sum Dum Heavy Industries Service Module System - Mod Parts Pack

Version:	2.1.1	(KSP 0.24.2)

Author: 	Robin "sumghai" Chang	grnlead@hotmail.com

License:	Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
		http://www.creativecommons.org/licenses/by-sa/4.0/

Disclaimer:	This parts pack is for an alpha game - Use at own risk. 
		If your computer blows up, it's not my problem.



===Dependencies===

 - AnimatedDecouplers plugin (Starwaster), for umbilical animation on decoupling

 - Firespitter plugin (Snjo), for tweakable IACBM docking port guidance fin and Boost Protective Cover crew access hatch animations

 - Klockheed Martian Special Parts plugin (dtobi), for self-inflating floation collar functionality

 - ModuleManager plugin (sarbian), for applying patches for functionality/features provided by dependencies and third-party add-ons

 - RealChute Parachute Systems plugin (stupid_chris), for parachute functionality


===Supported Third-Party Addons===

 - Deadly Reentry Continued plugin (NathanKell) - if installed, the SDHI Heat Shield will protect the Mk1-2 Pod from the heat and stresses of atmospheric reentry; most other Service Module components will also consistently be burned up when deorbited

 - Ferram Aerospace Research plugin (ferram4) - if installed, the Boost Protective Cover and Service Module Fairings will properly shield other components from aerodynamic stresses experienced during launch, reducing drag and making your rockets more efficient at getting into orbit

 - HotRockets! plugin (Nazari1382) - if installed, the LV-909 variant included in the Service Module pack will display improved particle effects in its exhaust

 - Ship Manifest plugin (Papa_Joe) and Connected Living Spaces API plugin (codepoet) - if installed, crew can be transferred between vessels that use the parachute-equipped docking ports included in the Service Module pack

 - TAC Life Support (TaranisElsu) - if installed, will add a total of Kerbin eight day's worth of life support provisions to the Mk1-2 Pod and Service Module, plus Carbon Extractors and Water Filters 


===How To Install===

1. Ensure that you have all of the aforementioned dependencies installed

2. Remove any previous version of the SDHI SMS add-on

3. Download

4. Extract the .ZIP archive and copy the GameData folder provided into your KSP root directory

The parts should then be located under the SDHI/Service Module System folder



===Usage===

 - This parts pack is specifically designed for use with the stock Mk1-2 Command Pod

 - For assembly and configuration instructions, refer to http://github.com/sumghai/SDHI_ServiceModuleSystem/wiki/How-to-assemble-&-configure-a-complete-SDHI-CSM-stack

 - No Launch Escape Systems or Escape Towers are included in this pack; either build your own using stock parts, or try the ones from KSPX or BFGfreak's Prilla LES add-ons.



===Uninstallation Instructions===

Remove the SDHI folder and all its contents from the GameData folder.

If you have other SDHI part packs you wish to keep, just remove the Service Module System subfolder.


===Release Notes===
2.1.1        21 August 2014
---------------------------

Changes / Fixes:
 - Fixed TAC Life Support patch so that it only applies if TAC LS is actually installed.


2.1          7 August 2014
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 0.24.2
 - Native TAC Life Support compatibility
    - Increased Mk1-2 Pod Food and Waste storage capacities
    - Added Water, Oxygen, WasteWater and CarbonDioxide storage to Service Module
    - Added Carbon Extractors and Water Filters to both Service Module and Avionics Ring
    - A combined Command Pod / Service Module would thus contain up to eight Kerbin days' worth of provisions for its three crew
 - Fixed HotRockets! patch dependency checking
    - If HotRockets! is not installed, LV-909 Liquid Fuel Engine (Fairingless) will revert gracefully to stock effects
 - RealChutes 1.2.4 compatibility fix
    - SDHI TextureLibrary and ProceduralChute removed from parachute-equipped docking ports as they are no longer required
    - Fixed missing drogue canopy texture
    - WARNING: This is a craft and save-breaking change; it is recommended you abort / recover existing SDHI craft before installing this update


2.0          27 July 2014
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 0.24.x
 - Native integration for Connected Living Space (CLS) API
    - Parachute-equipped docking ports will allow crew passage if Ship Manifest is installed
 - Native Deadly Reentry Continued support
    - Heat shield will protect command pod during atmospheric reentry
    - All other parts should burn up reliably when deorbited
 - Native HotRockets! particle effects support for LV-909 Liquid Fuel Engine (Fairingless)
 - Consolidated Service Module and Avionics Ring textures / subdirectories
 - Native FAR support for Boost Protective Cover
    - NOTE: When first installing FAR and/or SDHI, you must delete CustomFARPartClassification.cfg from your GameData\FerramAerospaceResearch\ folder in order for FAR to properly rebuild its part classification definitions to include the SDHI parts)
 - Reduced docking port spotlight range and intensities, as they are not intended for general illumination
 - Fixed Service Module rescaling bug that occurs on scene reload
 - RealChutes 1.2.2.2 compatibility fix
    - WARNING: This is a craft and save-breaking change; it is recommended you abort / recover existing SDHI craft before installing this update

Features:
 - New Command Pod-Service Module Umbilical interface on Service Module and Avionics Ring
    - Stock Mk1-2 Command Pod now has option to show / hide SDHI Umbilical port
    - Umbilical will animate when decoupler is triggered
    - Requires Starwaster's AnimatedDecouplers plugin
 - Boost Protective Cover now has toggleable crew access hatch, compatible with FASA launch towers
    - Opening the hatch allows Kerbals on EVA to board the command pod, while closed hatches prevent Kerbals from getting out
 - Boost Protective Cover can now be adorned with mission flag / logo
 - Self-inflating floatation collar built into Heat Shield
    - Triggers automatically on splashdown to keep the pod afloat while awaiting recovery
    - Requires dtobi's Klockheed Martian Special Parts plugins


1.9          5 April 2014
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 0.23.5
 - Fixed IACBM 1.25m - Parachute version docking light colors


1.8          20 March 2014
---------------------------

Changes / Fixes:
 - Reduced drag on Service Module, so that when it decouples from the Mk1-2 Command Pod just before re-entry it is less likely to bump back into it
 - Set Boost Protective Cover decoupler force to 0, as the ejection force is made redundant by the cover's own solid rocket motors


1.7          13 January 2014
---------------------------

Changes / Fixes:
 - Dropped FusTek_Sumghai.DLL in favour of external dependency on Snjo's Firespitter plugin
    - You will need to download and install the latest version of Firespitter yourself
    - This change now allows the IACBM guidance fins to be tweakable within the VAB/SPH


1.6          24 December 2013
---------------------------

Changes / Fixes:
 - Added new 0.23 EFFECTS{} for parachute sounds (stupid_chris)
 - Tweaked main parachute deployment altitude slightly; the mains will now deploy almost immediately after drogues are cut, instead of after a (decidedly terrifying) period of free-fall. 


1.5          8 December 2013
---------------------------

Changes / Fixes:
 - Compatibility upgrade to take advantage of new features in RealChute v0.3
    - Parachute drag is now dependent on effective canopy area rather than stock drag
    - Command Pod assembly will now hang under parachute anchor realistically without the need for the CoMOffset hack, and as such the latter has been removed


1.4          24 November 2013
---------------------------

Changes / Fixes:
 - Parachute-equipped docking ports now use stupid_chris's RealChute Parachute Systems plugin
    - Drogues will now auto-cut properly before automatically deploying the main chutes
    - Docking port lights can now be toggled normally during parachute deployment
    - This is not included in the pack, so you will need to download it separately
 - Updated drogue parachute textures to distinguish them from the main parachutes



1.3          8 November 2013
---------------------------

Features:
 - New Part
    - SDHI 2.5m Avionics Ring
 - Avionics Ring is essentially the upper decoupler portion of the full Service Module, with a bonus battery, reaction wheel and toggleable integrated fuel-to-electricity converter
    - This is particularly useful for people who want to build their own Service Module, but also use the SDHI Heat Shield and Boost Protective Cover 


1.2          25 October 2013
---------------------------

Changes:
 - VAB/SPH: Moved SDHI 2.5m Service Module Adapter and SDHI 2.5m Service Module Fairing to Aero tab
 - R&D: Moved SDHI 2.5m Service Module Adapter to "Supersonic Flight" node
    - If you have unlocked this part previously in Career Mode, you will need to edit your persistence file to temporarily remove the adapter from the list of unlocked parts, and then re-unlock after restarting the game
 - Modified SDHI Mk1-2 Pod Boost Protective Cover collider to allow the Mk1-2 Pod underneath to be selected
    - Hover your mouse pointer over the "Cut To Rescue" graphic on the cover and right-click



1.1          17 October 2013
---------------------------

Changes:
 - Compatibility Patch for KSP 0.22+
 - All parts have now been assigned to the appropriate nodes in the Research & Development Tech Tree
    - Parts are in the same Tier Level as the Mk1-2 Command Pod (i.e. Tier 5)
    - "Specialized Construction" unlocks:
        - SDHI 2.5m Heat Shield
        - SDHI 2.5m Service Module Adapter
        - Clamp-O-Tron Docking Port - Parachute version
        - IACBM 1.25m - Parachute version
    - "Supersonic Flight" unlocks:
        - SDHI Mk1-2 Pod Boost Protective Cover
        - SDHI 2.5m Service Module Fairing
    - "Heavier Rocketry" unlocks:
        - SDHI 2.5m Service Module
        - LV-909 Liquid Fuel Engine (Fairingless)



1.0          12 October 2013
---------------------------

Features:
 - Initial release
 - New parts
    - SDHI Mk1-2 Pod Boost Protective Cover
    - Clamp-O-Tron Docking Port - Parachute version
    - IACBM 1.25m - Parachute version
    - SDHI 2.5m Heat Shield
    - SDHI 2.5m Service Module
    - LV-909 Liquid Fuel Engine (Fairingless)
    - SDHI 2.5m Service Module Fairing
    - SDHI 2.5m Service Module Adapter
 - Boost Protective Cover is ogive-shaped to fit stock Mk1-2 Pod and any surface-attached accessories underneath
    - Staging activates both the shroud decoupler and jettison solid rocket motors
    - If shroud jettison is to be triggered via action groups, both the decoupler and the solid motors must be manually mapped to the same action key
 - Docking Ports come with short-range illumination lamps and integrated drogue/main parachute system
    - Clamp-O-Tron variant is compatible with stock standard-sized docking ports
    - IACBM variant is compatible with the FusTek Station Parts Expansion add-on
 - Service Module comes with:
    - Non-staged CM-SM decoupler to prevent accidental Pod/Service Module seperation during flight (action groups or right-click context menu used instead)
    - Toggleable integrated fuel-to-electricity converter for use


Bugs/Known Issues
 - Drogue parachutes do not auto-cut until mains are fully deployed
    - This is due to the use of *two* ModuleParachutes, which is technically "hacky" by KSP standards
    - Unlike BobCat's Orion spacecraft, however, the parachute-equipped docking ports will use the greater of the two drag configurations, guaranteeing a safe landing
        - Warranty void if parachutes are deployed on a planetary body other than Kerbin
 - Docking Port Lights become untoggleable after parachute deployment
    - This is because of the way KSP handles animations; the game can only save the state of one animation at a time, and the docking ports need several animations to handle the various parachute deployment stages and the lights.
