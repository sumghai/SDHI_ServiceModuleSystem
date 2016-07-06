Sum Dum Heavy Industries Service Module System - Mod Parts Pack

Version:	3.2	(KSP 1.1.3)

Author: 	Robin "sumghai" Chang	sumdumghai@gmail.com

License:	Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
			http://www.creativecommons.org/licenses/by-sa/4.0/

Disclaimer:	This parts pack is for an alpha game - Use at own risk. 
			If your computer blows up, it's not my problem.



===Dependencies===

 - AnimatedDecouplers (Starwaster), for umbilical animation on decoupling, as well as adding stock drag occlusion support for the Boost Protect Cover and Service Module side fairings

 - ModuleManager (sarbian), for applying patches for functionality/features provided by dependencies and third-party add-ons

 - Wenkel Corporation RealChute Parachute Systems (stupid_chris), for parachute functionality


===Supported Third-Party Addons===

 - Deadly Reentry Continued (Starwaster) - if installed, the SDHI Heat Shield will protect the Mk1-2 Pod from the heat and stresses of atmospheric reentry; most other Service Module components will also consistently be burned up when deorbited

 - Ship Manifest and Connected Living Spaces API (Papa_Joe) - if installed, crew transfer will be realistically limited to through the parachute-equipped docking ports

 - TAC Life Support (TaranisElsu / danfarnsy) - if installed, will add a total of Kerbin eight day's worth of life support provisions to the Mk1-2 Pod and Service Module, plus Carbon Extractors and Water Filters 


===How To Install===

1. Ensure that you have all of the aforementioned dependencies installed

2. Remove any previous version of the SDHI SMS add-on

3. Download

4. Extract the .ZIP archive and copy the GameData folder provided into your KSP root directory

The parts should then be located under the SDHI/Service Module System folder



===Usage===

 - This parts pack is specifically designed for use with the stock Mk1-2 Command Pod

 - For assembly and configuration instructions, refer to http://github.com/sumghai/SDHI_ServiceModuleSystem/wiki/How-to-assemble-&-configure-a-complete-SDHI-CSM-stack

 - A Launch Escape System is included in this pack, which has better performance than the LES from the stock game; it also comes with a built-in Solid Fuel-powered RCS thruster to allowing mid-abort course corrections



===Uninstallation Instructions===

Remove the SDHI folder and all its contents from the GameData folder.

If you have other SDHI part packs you wish to keep, just remove the Service Module System subfolder.


===Release Notes===
3.2 - 8 July 2016
---------------------------

WARNING: This is a craft and save-breaking update; it is recommended you abort / recover existing SDHI craft before installing this update

Changes / Fixes:
 - Compatibility Patch for KSP 1.1.3
 - All models have been re-scaled to actual size in-game
 - Side fairings have been overhauled
 	 - They now split into thirds rather than halves, and include built-in solid rocket jettison motors to help push the panels away cleanly after separation
 - The parachute-equipped IACBM docking port has been updated to match the new design from FusTek Station Parts
 	 - The ports will now enforce docking orientation angles at 90 degree increments
 - Updated support for tg626's Kerbal Optical Alignment System (KOAS) mod, previously known as the Docking Target mod
     - This adds an inline docking camera and target to the parachute-equipped SDHI Clamp-o-Tron docking port


3.1.1 - 23 April 2016
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 1.1
 - Added support for DennyTX's OLDD docking camera plugin to both parachute-equipped docking ports
 - All parts now have search tags
 - Improved heat shield texture and normal map
 - The fairingless LV-909 "Terrier" Liquid Fuel Engine has now been deprecated
     - This is because the stock LV-909 now includes the ability to hide the engine shroud
     - Existing crafts will not break, but users are encouraged to switch over to using the stock engine for new crafts
 - The fuel cell in the Service Module and Avionics Ring can now be toggled using Action Groups
 - The Launch Escape System (LES) has been reassigned to the more sensible Advanced Landing tech tree ndoe
     - This is a Level 6 node, which puts it on par with the other SDHI SMS parts
 - Tweaked the ModuleAnimateGeneric parameters used to prevent the Mk 1-2 Pod Umbilical Port from being toggleable outside VAB/SPH editor scene
     - KSP 1.1 fixed some typos in the parameters used in KSP 1.0.5


3.1 - 13 February 2016
---------------------------

WARNING: This is a craft and save-breaking update; it is recommended you abort / recover existing SDHI craft before installing this update

Changes / Fixes:
 - Compatibility Patch for KSP 1.0.5
 - A dedicated Launch Escape System (LES) is now included in the parts pack
    - The LES runs on Solid Fuel, and is capable of lifting a Mk 1-2 Pod, heat shield and Pod Boost Protective Cover up to 2.0 km in altitude, making pad aborts viable compared to the stock LES
    - The LES also includes built-in RCS thrusters that are powered by its own independent Solid Fuel reserve, allowing mid-abort course corrections
 - Added support for tg626's Docking Target mod, which adds a cosmetic docking alignment target mesh to all Clamp-O-Tron docking ports
 - Dropped support for HotRockets! plugin
    - The plugin is currently not compatible/updated for KSP 1.0.5
    - The fairingless LV-909 engine will now only have stock engine FX
 - Dropped support for Klockheed Martian Special Parts plugin
    - The plugin is no longer being maintained
    - The Heat Shield's flotation collar no longer works
 - Mk1-2 Pod Aeroshroud jettison motor thrustTransforms relocated to the sides of the shroud
    - The thrustTransforms were previously located under the skirt of the shroud itself, which would overheat nearby parts such as the Service Module and Heat Shield
    - Shroud texture modified to include jettison motor nozzles and warning label decals
 - Mk 1-2 Pod Umbilical Port no longer toggleable outside VAB/SPH editor scene
    - This long-standing bug was fixed with the introduction of scene-specific animation toggling in KSP 1.0.5 (courtesy of SQUAD developer NathanKell)
 - Rebalanced part costs to be in line with stock parts (courtesy Kerbas-ad-astra)
    - Avionics Ring now has higher entry/per part cost, lower mass and adjusted CoM offset
    - Service Module now has higher entry/per part cost, lower mass and adjusted CoM offset
    - Service Module Adapter now has lower entry/per part cost, lower mass and lower breaking force/torque
 - SDHI Heat Shield characteristics updated for KSP 1.0.5's thermal model
 - Side fairings and Mk1-2 Pod Aeroshroud colliders reworked using convex rather than concave meshes
 - Side fairings now decouple from the Service Module itself rather than the Service Module Adapter
 - The Service Module and Avionics Ring now have built-in support for MechJeb and RemoteTech
 - The Service Module and Avionics Ring decoupler will wait until the umbilical has fully extended before releasing the Mk1-2 Pod

Bugs/Known Issues
 - Part testing contracts are generated in Career Mode
    - This not intended behaviour, since the SDHI SMS is intended to be tested as a complete assembled stack rather than in piecemeal
    - A future update might include a proper contract for testing the SDHI SMS


3.0.1 - 10 July 2015
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 1.0.4
 - Heat shield is now compatible with 1.0.4's updated thermal system
    - Deadly Reentry support has also been updated accordingly, and the corresponding patch is now compatible with DRE 7.2.x
 -  Fallback patch for stock parachute behaviour has been updated
    - Deployment altitude increased to 1000m
    - Minimum air pressure required to open reduced to 0.04 kPa
    - Both values are comparable to stock parachute part performance
    - Note: RealChute is still the recommended default

Bugs/Known Issues
 - Mk 1-2 Pod Umbilical Port is now also toggleable outside of the VAB/SPH editor scenes
    - This is due to a limitation with the current stock KSP ModuleAnimateGeneric behaviour, but is not game-breaking.
 - Part testing contracts are generated in Career Mode
    - This not intended behaviour, since the SDHI SMS is intended to be tested as a complete assembled stack rather than in piecemeal
    - A future update might include a proper contract for testing the SDHI SMS
    
    
3.0 - 11 June 2015
---------------------------

WARNING: This is a potentially craft and save-breaking update; it is recommended you abort / recover existing SDHI craft before installing this update

Changes / Fixes:
 - Compatibility Patch for KSP 1.0.x
 - The Service Module's fuel cell now uses the new stock ModuleResourceConverter system, and has the same performance as its stock standalone counterpart
 - Stack attachment node directions have been updated to conform with 1.0.x stricter definitions
    - The Node Resizer plugin is no longer required when attaching the Heat Shield to the pod, Service Module or Avionics Ring
 - All textures have been converted to DDS format for faster loading and reduced memory usage
 - A bright patch on the Pod Boost Protective Cover has been fixed
 - The Heat Shield is now compatible with the new stock reentry system
    - Ablative darkening is not used in SDHI SMS, and has been disabled
    - Deadly Reentry is still supported, and the corresponding patch is now compatible with DRE 7.x
 - The fairingless LV-909 engine has been updated to have similar performance to its stock counterpart
 - The Service Module colliders have now been fixed, so that surface-attached parts like solar panels and RCS thrusters should no longer float out from the lower propulsion trunk segment
 - The Service Module Adapter textures have been reworked to be visually consistent with the Service Module upper ring itself
 - The Pod Boost Protective Cover and Service Module Fairings are now fully compatible with the new stock aerodynamics system
    - This requires the latest version of the AnimatedDecouplers plugin, which provides special versions of the standard decoupler/jettison PartModules in order for the stock ModuleCargoBay to know when to update its drag occlusion behaviour
 - Removed Ferram Aerospace Research MM patch for Pod Boost Protect Cover
    - The latest versions of FAR now intrinsically and automatically handle drag occlusion for hollow parts, making such patches redundant
 - Fixed HotRockets! MM patch for the fairingless LV-909 engine

Bugs/Known Issues
 - Mk 1-2 Pod Umbilical Port is now also toggleable outside of the VAB/SPH editor scenes
    - This is due to a limitation with the current stock KSP ModuleAnimateGeneric behaviour, but is not game-breaking.
 - Part testing contracts are generated in Career Mode
    - This not intended behaviour, since the SDHI SMS is intended to be tested as a complete assembled stack rather than in piecemeal
    - A future update might include a proper contract for testing the SDHI SMS


2.4        27 December 2014
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 0.90.0
 - Added Editor Part List Filter By Manufacturer Icon for SDHI
 - Heat shield floatation collar powered by Klockheed Martian Special Parts now considered an optional feature instead of a depedency

Bugs/Known Issues
 - In the VAB/SPH editor scenes, When surface-attaching solar panels and other small parts to the ribbed propulsion trunk segment of the Service Module, the parts will sometimes appear to be suspended a fair distance away from the surface
    - The problem generally occurs when angle snap is enabled, possibly due to editor scene changes in KSP 0.90.0
    - No known fix
 - Part testing contracts are generated in Career Mode
    - This not intended behaviour, since the SDHI SMS is intended to be tested as a complete assembled stack rather than in piecemeal
    - A future update might include a proper contract for testing the SDHI SMS


2.3        10 October 2014
---------------------------

Changes / Fixes:
 - Compatibility Patch for KSP 0.25.x
 - Updated references and scaling factors in stock parts used by SDHI (such as the Fairingless LV-909 and Clamp-O-Tron Docking Port - Parachute version)
 - Replaced FSanimateGeneric with new stock KSP ModuleAnimateGeneric
    - IACBM fins, Boost Protect Cover hatch and Mk 1-2 Pod Umbilical Port remain toggleable in the VAB/SPH editor scenes
    - Firespitter plugin is no longer required, and has been dropped from the list of dependencies
 - Added fallback patch for stock parachute behaviour if RealChute is absent
    - Note: RealChute is still the recommended default
    - Stock parachute behaviour only deploys main chutes, and should only be used in an emergency as it may cause sudden or craft-damaging deacceleration upon deployment  

Bugs/Known Issues
 - Mk 1-2 Pod Umbilical Port is now also toggleable outside of the VAB/SPH editor scenes
    - This is due to a limitation with the current stock KSP ModuleAnimateGeneric behaviour, but is not game-breaking.


2.2.1        30 August 2014
---------------------------

Changes / Fixes:
 - Updated TAC Life Support patch for compatibility with new v0.10 version


2.2          29 August 2014
---------------------------

Changes / Fixes:
 - Added Node Resizer support
    - This dynamically changes the stack nodes of the Avionics Ring and Heat Shield to size 0 while in the VAB/SPH editor scenes, allowing for easier attachment (and thus fixing the "bouncing" attachment node bug)
    - When entering the flight scene, this automatically switches the node size back to 2 to ensure a strong structural connection as usual
 - New meshes, graphics and better details for the FusTek Karmony hatch on the IACBM parachute-equipped docking port
    - This is for compatibility / visual consistency with future versions of FusTek Station Parts


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
