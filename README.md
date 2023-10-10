<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<title>SubtleMods: SubtleD's Spell Tweaks</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link rel="stylesheet" href="style/g3readme_cam.css" type="text/css" />
<link href="style/g3icon.ico" rel="icon" type="image/bmp" />
</head>
<body>
<h1>SubtleMods: SubtleD's Spell Tweaks</h1>
<div class="section">
  <p><strong> Version 2.1 </strong><br />
  <strong> Languages:</strong> English</p>
  <p><strong>Author: <a href="http://forums.gibberlings3.net/index.php?showuser=6306">The Subtle Doctor</a></strong></p>
  <p><strong><a href="https://github.com/subtledoctor/SubtleD_Spell_Tweaks">Home page</a></strong></p>
  <p><strong><a href="https://www.gibberlings3.net/forums/topic/37238-subtlemods-subtleds-spell-tweaks/">Discussion Forum</a></strong></p>
  <p><strong><a href="https://github.com/subtledoctor/SubtleD_Spell_Tweaks/releases">Download</a></strong></div>
<h2>Overview</h2>
<div class="section">
  <p>This is just a bunch of small tweaks that I sometimes apply to my own game. A bunch of small tweaks (and a couple not-so-small ones) that I think are fun and cool.</p>
  <p>These don't really belong with any existing mods, and they are very much a matter of my personal taste, so I am not including them in any Unearthed Arcana project.</p>
  <p><b>Note:</b> most or all of these use EE 2.0 engine features. One or two may work on the pre-EE game (e.g. adding saving throws to level drain attacks), but most will not.</p>
</div>
<h2>Installation</h2>
<div class="section">
  <p><strong>Windows:</strong><br />
    The mod archive should be extracted into your game folder from the archive (or just unzipped and then copied there). If properly extracted, you should have a "d5_random_tweaks" folder and "setup-d5_random_tweaks.exe" in your game folder. To install, simply double-click "setup-d5_random_tweaks.exe" and then follow the instructions on screen.</p>
  <p><strong>MacOS:</strong><br />
    This mod is packaged and installed with the Mac Weidu Launcher (MWL). To install, simply extract the contents of the mod and then move them into your game folder. If properly extracted, you should now have a folder called "d5_random_tweaks" and the "Mac WeiDU Launcher" in your game directory. To install, simply double-click the MWL, choose "d5_random_tweaks" from the list, and then follow the instructions on the screen.</p>
</div>
<h2>Compatibility</h2>
<div class="section">
  <p>This mod should be installed after spell mods like Spell Revisions, IWDification, and SCS IWD Spells. It should probably be installed before kit mods, including Tome & Blood and Faiths & Powers.</p>
</div>
<h2>Contents</h2>
  <h4 class="subheader">Component 10: Revised Specialist Opposition Schools</h4>
  <div class="section">
    <p>This component allows changes to which spells are in an "opposition school" and thus unavailable to specialists. There are currently seven options, several of which will be available for install depending on which game is being played. (The BG2 options will not be displayed if you are playing BG; the IWD options will not be displayed if you are playing IWD.)
    <ul>
      <li>No Opposition Schools (all specialists can cast all spells)</li>
      <li>Baldur's Gate Opposition Schools (matches BG/BG2)</li>
      <li>Baldur's Gate Opposition Schools, low-level allowed (matches BG/BG2, but up to 3rd-level spells are universal)</li>
      <li>Icewind Dale Opposition Schools (matches IWD)</li>
      <li>Icewind Dale Opposition Schools, low-level allowed (matches IWD, but up to 3rd-level spells are universal)</li>
      <li>PnP Opposition Schools (matches the original 2E Player's Handbook)</li>
      <li>PnP Opposition Schools, low-level allowed (matches the original 2E PHB, but up to 3rd-level spells are universal)</li>
    </ul>
    <b>NOTE:</b> in the 3rd, 5th, and 7th options, you can changed the level limit for universally-available spells from 3 to another number by editing SubtleD_Spell_Tweaks/sdst_settings.ini before installing the mod.</p>
  </div>
  <h4 class="subheader">Component 15: Rebalanced Spell Schools</h4>
  <div class="section">
    <p>This component changes the school of various spells, to make sure there is at least one spell at each level in each school, and that specialists of different schools are better-balanced against one another.  Generally:
    <ul>
      <li>Sequencer spells are moved to the school of Enchantment</li>
      <li>Power Word spells are moved to the school of Enchantment</li>
      <li>Symbol spells are moved to the school of Divination</li>
      <li>A couple other small changes</li>
    </ul>
	These changes are determined by a list that resides in SubtleD_Spell_Tweaks/data/core/spell_list_base.tpa. That file is human readable and you can change it as you like, so you have complete control over the school of every spell, before installing the mod. (There is a version for Spell Revisions as well, if you have it installed.)</p>
  </div>
  <h4 class="subheader">Component 20: Revised Illusionary Clones</h4>
  <div class="section">
    <p>This component makes Mislead and Project Image work just as Simulacrum does, except the clones can use more magic as you go up in level, and the caster gets progressively better invisibility at the same time:
    <ul>
      <li>5th Level: Mislead - clone is a pure image, cannot attack or cast spells. Caster become normal invisible - NOT super-Mislead-invisible.</li>
      <li>6th Level: Shadow Clone - clone has 40% hit points and -7 to thac0 and caster level, can cast only 1st-level arcane spells, cannot cast divine spells.</li>
      <li>7th Level: Lesser Simulacrum - clone has 60% hit points and -5 to thac0 and caster level, can cast up to 4th-level arcane spells, cannot cast divine spells.</li>
      <li>8th Level: Simulacrum - clone has 75% hit points and -3 to thac0 and caster level, and can cast any spells.</li>
      <li>9th Level: Projected Simulacrum - cast Simulacrum on another creature. (Illusionists only)</li>
    </ul></p>
  </div>
  <h4 class="subheader">Component 25: Revised Invisibility</h4>
  <div class="section">
    <p>This component merges the effects of Invisibility and Sanctuary (you can now loot chests and open doors while invisible :) ). The upshot is, if you cast 2nd-level Detect Invisible, the caster will be able to see and target invisible enemies but other party members who cannot see invisible cannot.</p>
    <p>The Nondetection spell is renamed "Protection from Divination" and improved to actually block any DIVINATIONATTACK effects, like Invisibility Purge, Detect Illusion, and Oracle. A caster of Detect Invisible or True Sight <b>will</b> be able to spot and target enemies who are protected by Protection from Divination - Detect Invisible and True Sight affect the caster, not the target. But Protection from Divination will ensure that illusionary protections like Blur and Mirror Image are not dispelled.</p>
    <p>Additionally, the 5th-level Oracle spell is empowered to destroy nearby illusionary creatures, including Shadow Monsters if they are revised by this mod, and Projected Images and similar clones.</p>
  </div>
  <h4 class="subheader">Component 30: Pre-EE Behavior for Haste and Slow</h4>
  <div class="section">
    <p>Instead of only the last one cast being applied, Haste and Slow effects will now fully cancel each other out, resulting in a net neutral effect if you are affected by both, in any order.</p>
  </div>
  <h4 class="subheader">Component 35: Spells Reduce Target MR</h4>
  <div class="section">
    <p></p>
  </div>
  <h4 class="subheader">Component 40-43: Familiars</h4>
  <div class="section">
    <p></p>
  </div>
<div class="section">
  <h4 class="subheader">Component 1010: Cure Spells Bypass Deflection</h4>
  <div class="section">
    <p>Some friendly spells have their power level set to 0, so that they can bypass Spell Deflection. I always get frustrated when a battle is over and I try to heal a party member, but the Cure Wounds spell fails because their Spell Deflection is still in effect. This fixes that. The spells changed in this way include:
  	<ul>
  	  <li>All Cure/Regenerate Wounds spells and Heal</li>
  	  <li>Cure Disease</li>
  	  <li>Cure Blindness and Deafness</li>
  	  <li>Slow Poison and Neutralize Poison</li>
  	  <li>Remove Curse and Break Enchantment</li>
  	  <li>Remove Paralysis</li>
  	  <li>Exaltation and Spiritual Clarity</li>
  	  <li>Free Action</li>
  	  <li>Lesser and Greater Restoration</li>
  	  <li>Freedom</li>
    </ul>
  </div>
  <h4 class="subheader">Component 2105: Tweak Color Spray</h4>
  <div class="section">
    <p>This adds a chance for any target to be blinded for one round, regardless of their level. If you have SR installed, the Confusion effect is switched to the three-round duration.</p>
  </div>
  <h4 class="subheader">Component 2108: Tweak Protection from Petrification (EE-only)</h4>
  <div class="section">
    <p>This turns Pro Petrification into "Mirrored Eyes," giving protection from any effects using the GAZE projectile. AFAIK that includes vampire Charm, umber Hulk Confusion, and Aec'Letec's Death Gaze. This works like the IWD thieves' Evasion ability, giving you a saving throw to avoid the effect.</p>
  </div>
  <h4 class="subheader">Component 2110: Tweak Identify (EE-only)</h4>
  <div class="section">
    <p>Identify will now be cast like a normal spell in the main screen, rather than used from the inventory screen. Additionally, it will scale with level, such that at 13th level the caster can identify 4 items with a single casting of the spell. (<b>NOTE:</b> this component involves modifications to the UI. It *may* not work with some UI overhauls installed beforehand, and it likely won't work with any UI overhauls installed afterward.)</p>
  </div>
  <h4 class="subheader">Component 2116: Tweak Sleep</h4>
  <div class="section">
    <p>Individuals affected by the Sleep Spell will awaken when struck. If Spell Revisions is installed, this will fix the current (SRv4b19) bug that makes some creatures wake up without being struck.</p>
  </div>
  <h4 class="subheader">Component 2151: Replace Expeditious Retreat</h4>
  <div class="section">
    <p>Only available if Spell Revisions is installed. This will replace SR's Expeditious Retreat spell with "Chameleon," which gives weak invisibility (like improved invisibility, but after you attack a target) and improves thieves Sneak skill by 25%.</p>
  </div>
  <h4 class="subheader">Component 1151: Tweak Sunscorch</h4>
  <div class="section">
    <p>Only available if Spell Revisions is installed. Damage to non-undead is halved, from 1d6 per 2 levels to 1d3 per 2 levels, up to 5d3 max. Damage to undead is 1d6 per 2 levels on top of that, so up to 5d3+5d6. No saving throws are allowed relating to the damage. On a failed save vs. spells, the duration of blindness is increased from 1 round to 3 rounds.</p>
  </div>
  <h4 class="subheader">Component 2105: Tweak Faerie Fire</h4>
  <div class="section">
    <p>No saving throw is allowed to avoid either the AC penalty or the inability to turn invisible. A new animation is added. If Faerie Fire was added by Spell Revisions, the AoE radius will be doubled.</p>
  </div>
  <h4 class="subheader">Component 2201: Tweak Blur (EE-only)</h4>
  <div class="section">
    <p>Adds a missile avoidance effect to the Blur spell, which avoids the damage (of the "missile" damage type) from one projectile each round. Basically the same as the tweak to the Gloves of Missile Snaring, below.</p>
  </div>
  <h4 class="subheader">Component 2209: Tweak Luck</h4>
  <div class="section">
    <p>Makes Luck into an AoE spell that can affect the whole party, and extends the duration from 3 rounds to 10 rounds.</p>
  </div>
  <h4 class="subheader">Component 2212: Tweak Mirror Image</h4>
  <div class="section">
    <p>Moves Mirror Image to 3rd level. A straight nerf. But Illusion also has Blur at 2nd level, and having two illusionary protection spells there seems silly - and there are none at 3rd level. Mirror Image is incredibly useful, I think it works quite well one level below Stoneskin. (Pro tip: if you install the "Revised Invisibility" component of Tome & Blood, then Nondetection (renamed to "Protection from Divination") will protect your images from divination attacks like True Sight and Oracle, making them as effective as Stoneskins.)</p>
  </div>
  <h4 class="subheader">Component 2213: Tweak Stinking Cloud</h4>
  <div class="section">
    <p>Only available  if Spell Revisions is installed first. This buffs the SR version of Stinking Cloud a bit by making the effects of nausea remain for a short time after leaving the area with the noxious gas. Movement rate is slowed for two rounds, the inability to cast spells or attack is extended to two rounds, and residual 2-point penalties to thac0, AC, and casting speed remain for another two rounds after that.</p>
  </div>
  <h4 class="subheader">Component 2215: Tweak Web</h4>
  <div class="section">
    <p>Web no longer Holds targets who fail their save. Instead it Slows them and sets their APR to zero. Additionally, it cuts movement rate to 30% for anyone in the area of effect, regardless whether they make their save. This compounds with the Slow effect so on a failed save you will only be able to move at 15% your normal rate. And you won't be able to attack, and spellcasting will take twice as long, and you'll have a 4-point AC penalty. This is a nerf, to be sure... but man, vanilla Web is just too powerful. A non-party-friendly Slow spell one level below the party-friendly Slow spell makes a lot of sense to me.</p>
  </div>
  <h4 class="subheader">Component 2217: Tweak Agannazar's Scorcher</h4>
  <div class="section">
    <p>I find Agannazar's Scorcher to be too finicky for common use. This component changes it into a new spell, which is similar to Magic Missile but fires one extra missile, and can do 1d4 extra fire damage on a failed save.</p>
  </div>
  <h4 class="subheader">Component 2105: Tweak Glitterdust</h4>
  <div class="section">
    <p>No saving throw is allowed to avoid the inability to turn invisible. An AC penalty is added to match the thac0 penalty.</p>
  <h4 class="subheader">Component 2251: Tweak Decastave</h4>
  </div>
  <div class="section">
    <p>Adds a chance to Deafen anyone struck by the Decastave for three rounds if they fail a save.</p>
  </div>
  <h4 class="subheader">Component 1202: Tweak Barkskin (EE-only)</h4>
  <div class="section">
    <p>Instead of giving an AC bonus to avoid attacks, Barkskin acts like a slow version of Stoneskin, giving the caster one 'skin' of protection which regenerates each round. So the spell can block one attack per round for its duration. For balance reasons, this version can only target the caster, not an ally. This effect <b>does</b> stack with Stoneskin/Ironskin.</p>
    <p>For technical reasons, if installed in BG2EE, the ending of the Stoneskin effect triggered by the Juggernaut Golem in the Golem Manual will no longer cause the golem to die.</p>
  </div>
  <h4 class="subheader">Component 1207: Tweak Goodberry</h4>
  <div class="section">
    <p>Instead of creating consumable berries, that is abstracted away. Upon casting the spell, all nearby allies are assumed to have eaten berries; any intoxication and fatigue are removed, and they regenerate 2 hit points per round, for one round per level of the caster (to a maximum of 10 rounds). This spell cannot be cast in combat.</p>
  </div>
  <h4 class="subheader">Component 1212: Tweak Slow Poison</h4>
  <div class="section">
    <p>There's nothing more annoying than curing an ally of poison and then watching them immediately get poisoned again. This adds a very short immunity to poison damage - just three rounds - for convenience, to help you finish out a fight against those spiders or snakes or what have you.</p>
  </div>
  <h4 class="subheader">Component 1251: Tweak Alicorn Lance</h4>
  <div class="section">
    <p>The damage caused by this spell is increased from 3d6 to 4d6, and the damage type changed to 'magic.'</p>
  </div>
  <h4 class="subheader">Component 2324: Tweak Spell Thrust</h4>
  <div class="section">
    <p>This spell will be moved from 3rd level to 1st level, with all that implies. (E.g. if "Level 1 Cantrips" is installed, you cna cast Spell Thrust as a cantrip.) <b>NOTE:</b> you can edit SubtleD_Spell_Tweaks/sdst_settings.ini before installing the mod and change the spell's level from 1 to a different level.</p>
    <p>Additionally, if Spell Revisions is installed, this component will change Spell Thrust to target an individual instead of targeting the floor.</p>
  </div>
  <h4 class="subheader">Component 2324: Tweak Hold Undead and Control Undead</h4>
  <div class="section">
    <p>These spells will now bypass magic resistance, which is a fairly common defense for undead enemies.  (Tip of the hat to Bartimaeus for the idea!)</p>
  </div>
  <h4 class="subheader">Component 1323: Tweak Exaltation and Spiritual Clarity</h4>
  <div class="section">
    <p>Gives all the effects of Exaltation to Spiritual Clarity (curing more conditions, though the duration lasts only half as long) and improves the spells' casting times: to 4 for Exaltation and to 1 for Spiritual Clarity.</p>
  </div>
  <h4 class="subheader">Component 1351: Tweak Moonblade</h4>
  <div class="section">
    <p>Adds a chance to cast Faerie Fire on anyone struck by the Moonblade, and a chance to Slow if the target is undead.</p>
  </div>
  <h4 class="subheader">Component 2413: Tweak Otiluke's Sphere (EE-only)</h4>
  <div class="section">
    <p>This removes the Hold effect, and adds effects to prevent spellcasting and disable all UI buttons. The idea is, if you find yourself inside the sphere, you are still awake and aware. You cannot interact with the outside world, but you <b>can</b> go to the inventory screen and do things there, like drink potions!</p>
  </div>
  <h4 class="subheader">Component 2418: Tweak Fire Shields (SR-only)</h4>
  <div class="section">
    <p>This allows the Breach spell to work against Fire Shield and Acid Sheath spells.</p>
  </div>
  <h4 class="subheader">Component 2451: Tweak Shadow Monsters/Shades (EE-only)</h4>
  <div class="section">
    <p>This component alters the summoned creatures in the Shadow Monsters, Demi-Shadow Monsters, and Shades spells from IWDification or SCS IWD spells (or in IWDEE). There are several changes: 1) the summoned creatures do "non-lethal" damage; 2) most of the melee damage done by the summons can be resisted if the victim makes a saving throw vs. spells; 3) victims with intelligence of 17 or higher are immune to most of the damage done by the summons; and 4) the "gender" of the summoned creatures is changed from "SUMMONED" to "ILLUSIONARY," which means that they can bypass the normal summoning cap, and any spells that affect illusionary creatures will affect these ones (like Spell Revisions' version of True Sight). In general, these summons should be stronger than those in the equivalent-level Monster Summoning spells, but their power will be inconsistent and prone to being disbelieved.</p>
  </div>
  <h4 class="subheader">Component 1404: Tweak Neutralize Poison</h4>
  <div class="section">
    <p>This spell becomes "Remove Afflictions," a combination of Slow Poison, Cure Disease, Remove Paralysis, and IWD's Unfailing Endurance. It removes poison, disease, blindness, deafness, Hold, and fatigue. If Spell Revisions is installed first, this also extends immunity to disease for the same duration as the spell's immunity to poison.</p>
  </div>
  <h4 class="subheader">Component 1451: Tweak Smashing Wave</h4>
  <div class="section">
    <p>With a long casting time and finicky targeting, Smashing Wave is just too hard/annoying to use. This sets it to be party-friendly, so you don't have to worry about positioning and risk missing the enemies.</p>
  </div>
  <h4 class="subheader">Component 2508: Tweak Waves of Fatigue (SR-only)</h4>
  <div class="section">
    <p>Instead of applying actual fatigue (the effects of which can be frustratingly variable), this will apply a Luck penalty and remove Haste effects on the targets; and if they fail a save vs. polymorph/petrification, it will also penalize their saving throws,  APR, and spellcasting speed.</p>
  </div>
  <h4 class="subheader">Component 2518: Tweak Phantom Blade</h4>
  <div class="section">
    <p>Makes the Phantom Blade more of a phantasmal, psychic weapon. It now does 1d8 "stunning/nonlethal" damage, plus 1d8 magic damage. It removes the extra damage vs. undead (that's what Moonblade is for). There is a chance that anyone struck by the Phantom Blade will be confused for three rounds if they fail a save. If you use Spell Revisions it will also retain SR's casting-failure-on-hit. Finally, it moves the spell to the Illusion school.</p>
  </div>
  <h4 class="subheader">Component 2523: Tweak Sunfire</h4>
  <div class="section">
    <p>There are two options:
    <ul>
      <li>The spell becomes "Missile Storm." Put simply, it casts a maximum-strength Magic Missile at every enemy within 20' of the caster - twice.</li>
      <li>The spell become "Scorcher Storm." It casts Agannazar's Scorcher at every nearby enemy simultaneously.</li>
    </ul></p>
  </div>
  <h4 class="subheader">Component 2508: Tweak True Seeing (for SR or TnB)</h4>
  <div class="section">
    <p>This boosts the True Seeing spell from Spell revisions and/or Tome and Blood by granting the "see invisible" opcode to all party members, not just the caster.</p>
  </div>
  <h4 class="subheader">Component 1603: Tweak Blade Barrier (SR-only)</h4>
  <div class="section">
    <p>This allows the Breach spell to work against Blade Barrier spells.</p>
  </div>
  <h4 class="subheader">Component 1609: Tweak False Dawn</h4>
  <div class="section">
    <p>This allows the False Dawn spell to bypass magic resistance.</p>
  </div>
  <h4 class="subheader">Component 1611: Tweak Wondrous Recall</h4>
  <div class="section">
    <p>Instead of restoring two random spells you have no control over, this will now use a 6th-level slot to restore <b>ALL</b> 1st- and 2nd-level spells. If you have Item revisions installed, this will also affect Potions of Memory in the same way.</p>
  </div>
  <h4 class="subheader">Component 1613: Tweak Physical Mirror</h4>
  <div class="section">
    <p>This sets the Physical Mirror spell to acts as a super-strength "Reflected Image," blocking one physical attack every three seconds.</p>
  </div>
  <h4 class="subheader">Component 1614: Tweak Sol's Searing Orb</h4>
  <div class="section">
    <p>This will give the Searing Orb item a faster attack speed, and a slightly smaller radius of destruction, so that you can actually throw it before your target closes the distance and causes the thrower to be affected as well.</p>
  </div>
  <h4 class="subheader">Component 2708: Tweak Mantle (EE-only)</h4>
  <div class="section">
    <p>This changes Mantle into "Iron Skin" (and renames the druid Ironskins spell to "Stoneskin"). It applies the Stoneskin effect, identically to the 4th-level spell; but it also protects you from non-magical melee weapons and all missile weapons while the stoneskin effect is active, and also prevents elemental damage and other secondary effects of melee weapons while the stoneskin effect is active.</p>
  </div>
  <h4 class="subheader">Component 2711: Tweak Sphere of Chaos</h4>
  <div class="section">
    <p>Only available  if Spell Revisions is installed first. This sets all of the effects of Chaos to be mental - stun, sleep, fear, etc.</p>
  </div>
  <h4 class="subheader">Component 2714: Tweak Prismatic Spray</h4>
  <div class="section">
    <p>Only available  if Spell Revisions is installed first. This sets all of the effects of Prismatic Spray to be physical - poison, fire, petrification, etc.</p>
  </div>
  <h4 class="subheader">Component 1707: Tweak Sunray</h4>
  <div class="section">
    <p>This allows the Sunray spell to bypass magic resistance.</p>
  </div>
  <h4 class="subheader">Component 1710: Tweak Holy Word</h4>
  <div class="section">
    <p>Against enemies of the same level as the caster or above, Holy Word only applies deafness, which does nothing to hinder non-spellcasters. This Tweak adds a Slow effect that lasts for five rounds.</p>
  </div>
  <h4 class="subheader">Component 2808: Tweak Moment of Prescience (SR-only)</h4>
  <div class="section">
    <p>This makes the Breach spell unable to remove Moment of Prescience.</p>
  </div>
  <h4 class="subheader">Component 2811: Tweak Symbol: Fear</h4>
  <div class="section">
    <p>Moves Symbol: fear to 7th level. This is the weakest Symbol spell, I think, and this will diversify the Symbol spells a bit, instead of lumping them all at the same spell level.</p>
  </div>
  <h4 class="subheader">Component 2916: Tweak Shapechange</h4>
  <div class="section">
    <p>Moves Shapechange to 8th level. In the Alteration school at 9th level it competes with... Timestop?!? Shapechange is not quite at the same level. Seems more like 8th-level magic.</p>
  </div>
  <h4 class="subheader">Component 2915: Tweak Black Blade of Disaster</h4>
  <div class="section">
    <p>Moves BBoD to 8th level. Just because, again, it doens't quite seem like 9th level magic. (A 9th-level spell that requires you send your mage into melee?!? No.)</p>
  </div>
  <h4 class="subheader">Component 2914: Tweak Energy Drain</h4>
  <div class="section">
    <p>Adds a save-or-die effect to Energy Drain, and moves it to 8th level. (It's probably <i>still</i> underpowered... but at least it's better than competing with Wail of the Banshee at 9th level.)</p>
  </div>
  <h4 class="subheader">Component 2923: Tweak Planetars</h4>
  <div class="section">
    <p>This will change the Planetar HLA summon into a 'Noble Djinn,' and change the 'Fallen Planetar' into a 'Noble Efreet.' The name and animations will be changed as such, but the underlying creatures and abilities and scripting will not change very much. Elemental resistances will be tweaked (djinn immune to electrical damage, efreet immune to fire) and their weapons will be changed to something like Usuno's Blade and something like the Sword of Flame, respectively. But apart from that, they will behave and perform very similarly to the traditional planetars... they just won't stick out like a sore thumb anymore.</p>
  </div>
  <h4 class="subheader">Component 3000: 2 APR for Spell-Created Weapons</h4>
  <div class="section">
    <p>What it says on the tin. This affects Shillelagh, Flame Sword, Spiritual Hammer, Decastave, Moonblade, Starmetal Cudgel, Phantom Blade, and Black Blade of Disaster. If you spend a spell slot to make a magical melee weapon, you should gain a combat <i>benefit</i> for doing so!</p>
  </div>
  <h4 class="subheader">Component 3010: Tweak the Ring of Danger Sense</h4>
  <div class="section">
    <p>Adds a 1-point AC bonus and immunity to backstabs.</p>
  </div>
  <h4 class="subheader">Component 3020: Tweak the Gloves of Missile Snaring (EE-only)</h4>
  <div class="section">
    <p>The gloves now allow you to escape the missile damage (but not elemental damage) from the first missile weapon attack that hits you each round. Big props to OlvynChuru for showing how to do this!</p>
  </div>
  <h4 class="subheader">Component 3030: Tweak Detonating Weapons</h4>
  <div class="section">
    <p>Weapons like the Club of Detonation that can create Fireballs on-hit will now trigger the IWD priest spell "Produce Fire" instead.</p>
  </div>
  <h4 class="subheader">Component 3040: Tweak Skin of the Forest Armor (EE-only)</h4>
  <div class="section">
    <p>This leather armor will now act like a permanent version of the modified Barskin spell described above, absorbing one physical attack each round.</p>
  </div>
  <h4 class="subheader">Component 3050: Make IR's Rod of Absorption Truly Instantaneous (EE-only)</h4>
  <div class="section">
    <p>The Rod of Absorption in Item Revisions only lasts a single round, and can be triggered instantaneously to intercept an incoming spell. This component changes the item to use target mode 7 so that it can truly be used instantaneously, regardless of the other spells or attacks the wielder has performed in the preceding round.</p>
  </div>
  <h4 class="subheader">Component 3060: Tweak the Cloak of the Gargoyle (IR-only)</h4>
  <div class="section">
    <p>The Cloak of the Gargoyle will provide five Stoneskins, instead of the original AC bonus. This will be the same as Item Revisions' Gargoyle Boots and Potions of Stone Form.</p>
  </div>
  <h4 class="subheader">Component 3070: Tweak the Dwarven Thrower</h4>
  <div class="section">
    <p>Allows the Dwarven Thrower hammer to be used by any race, not just dwarves.</p>
  </div>
  <h4 class="subheader">Component 3080: Tweak Bard Harps</h4>
  <div class="section">
    <p>Azlaer's Harp will now cast Aid in addition to Resist Fear; Methild's Harp will cast Remove Curse in addition to Remove Paralysis.</p>
  </div>
  <h4 class="subheader">Component 3090: Tweak Edwin's Amulet</h4>
  <div class="section">
    <p>There are options to limit the amulet to providing +1 bonus slot per level, to limit the bonus slots to 7th level spells, or both.</p>
  </div>
  <h4 class="subheader">Component 4010: Tweak Vampires & Level Drain</h4>
  <div class="section">
    <p>Adds a saving throw vs. Death to all weapon-delivered level drain effects.</p>
  </div>
  <h4 class="subheader">Component 4020: Tweak Monster Stats</h4>
  <div class="section">
    <p>This changes the stats of certain creatures. As an example, yeti in IWDEE should be very strong, which means their minimum melee damage should be around 4. But some of them have 9 STR for some reason, which means they sometimes hit for only 1 damage. This component sates their STR scores to 18/99.</p>
    <p>If I or any players become aware of other creatures that require this kind of stat adjustment, I will add them to this component.</p>
  </div>
  <h4 class="subheader">Component 4030: Tweak Dragon Hit Points</h4>
  <div class="section">
    <p>Dragons are huge. Bigger than giants. For their sheer girth, they should arguably be a lot more durable, regardless of scales and magic and other protective characteristics. This component will let you increase their hit points by 50%, 100%, or 200%.</p>
  </div>
<h2>Contact Information</h2>
<div class="section">
  <p>This mod was created by SubtleDoctor. You can visit <a href="http://forums.gibberlings3.net/index.php">The
    Gibberlings Three</a> for information on this and many other fine mods.</p>
</div>
<h2>Thanks and Acknowledgements</h2>
<div class="section">
  <p>Thanks to the still active and vibrant Infinity Engine modding community. </p>
  <p><strong>Tools Used in Creation</strong><br />
    <a href="http://www.weidu.org/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a> by
    Wes Weimer, and then the bigg and then Wisp<br />
    <a href="http://www.idi.ntnu.no/~joh/ni/">Near Infinity</a> by Jon Olav Hauglid, and then Argent77 and Astrobryguy<br />
    <a href="http://iesdp.gibberlings3.net/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a> maintained by igi</p>
</div>
<h2>Credits and Copyright Information</h2>
<div class="section">
  <p>Copyright 2020. If you want to use or adapt any part of this mod in another mod or similar endeavor, please try to contact me at forums.gibberlings3.net to discuss it. As a general rule, I have no problem with that as long as you credit the source of the work. If you cannot get in touch with me, assume that you have my permission to use any of this code for any project that is non-commercial, offered for free, and intended for the greater enjoyment of players of Infinity Engine games. If you do so, please credit me, and mention how awesome I am in a comment in the code, or something like that. You may NOT use this code for any profit-making or commercial venture, without express permission from me.</p>
</div>
</body>
</html>
