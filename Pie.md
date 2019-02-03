# Active ROMs Manifest For Android Pie
 
You can replace <Potter> with your Device Codename 
# A
# ABC
https://github.com/ezio84/abc_manifest

Repo init & Sync command:

	repo init -u https://github.com/ezio84/abc_manifest -b p && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch abc_potter-userdebug && mka bacon -j24
	
# AospExtended
https://github.com/AospExtended/manifest

Repo init & Sync command:

	repo init -u git://github.com/AospExtended/manifest.git -b 9.x && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch aosp_potter-userdebug && mka aex -j48

# AICP
https://github.com/AICP/platform_manifest

Repo init & Sync command:

	repo init -u https://github.com/AICP/platform_manifest.git -b p9.0 && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# AOKP
https://github.com/AOKP/platform_manifest

Repo init & Sync command:

	repo init -u https://github.com/AOKP/platform_manifest.git -b pie && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch aokp_potter-userdebug && mka rainbowfarts

# AOSiP
https://github.com/AOSiP/platform_manifest

Repo init & Sync command:

	repo init -u git://github.com/AOSiP/platform_manifest.git -b pie && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	source build/envsetup.sh && lunch aosip_potter-userdebug && time mka kronic

# AOSPA
https://github.com/AOSPA/manifest

Repo init & Sync command:

	repo init -u https://github.com/AOSPA/manifest -b pie && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	./rom-build.sh potter

# AquariOS
https://github.com/AquariOS/manifest #Using a9-caf here(SSH key to be added)

Repo init & Sync command: 

	repo init -u https://github.com/aquarios/manifest -b a9-caf && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch aquarios_potter-userdebug && mka bacon -j48
	
# Arrow OS
https://github.com/ArrowOS/android_manifest

Repo init & Sync command:

	repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-9.x && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# B
# BenzoRom
https://github.com/BenzoRom/manifest

Repo init & Sync command: 

	repo init -u git://github.com/BenzoRom/manifest.git -b ninezero && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch benzo_potter-userdebug && mka bacon -j48

# BootleggersROM
https://github.com/BootleggersROM/manifest

Repo init & Sync command: 

	repo init -u https://github.com/BootleggersROM/manifest.git -b pasta && repo sync -f --force-sync --no-clone-bundle -j48

To build:

	source build/envsetup.sh && lunch bootleg_potter-userdebug && mka bacon -j48

# C
# Candy
https://github.com/CandyRoms/candy

Repo init & Sync command: 

	repo init -u https://github.com/CandyRoms/candy.git -b c9.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch candy_potter-userdebug && mka bacon -j48


# CarbonROM
https://github.com/CarbonROM/android

Repo init & Sync command: 

	repo init -u https://github.com/CarbonROM/android.git -b cr-7.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch carbon_potter-userdebug && make carbon -j48


# Citrus-CAF
https://github.com/Citrus-CAF/manifest

Repo init & Sync command: 

	repo init -u git://github.com/Citrus-CAF/manifest.git -b p9x -m citrus-caf.xml && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch citrus_potter-userdebug && mka lemonade -j48

# Cosmic-OS
https://github.com/Cosmic-OS/platform_manifest

Repo init & Sync command: 

	repo init -u https://github.com/Cosmic-OS/platform_manifest.git -b corona-release && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch cos_potter-userdebug && brunch potter
	
# COSP
https://github.com/cosp-project/manifest

Repo init & Sync command: 

	repo init -u https://github.com/cosp-project/manifest -b pie && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch aosp_potter-userdebug && mka bacon -j48

# crdroidandroid
https://github.com/crdroidandroid/android

Repo init & Sync command: 

	repo init -u git://github.com/crdroidandroid/android.git -b 9.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# D
# DotOS
https://github.com/DotOS/manifest

Repo init & Sync command: 

	repo init -u git://github.com/DotOS/manifest.git -b dot-p && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch dot_potter && brunch potter

# DirtyUnicorns
https://github.com/DirtyUnicorns/android_manifest

Repo init & Sync command: 

	repo init -u https://github.com/DirtyUnicorns/android_manifest.git -b p9x-caf && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && breakfast potter && mka bacon

# F

# G
# GZOSP
https://github.com/GZOSP/manifest

Repo init & Sync command: 

	repo init -u https://github.com/GZOSP/manifest.git -b 9.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# H
# Havoc-OS
https://github.com/Havoc-OS/android_manifest


Repo init & Sync command: 

	repo init -u https://github.com/Havoc-OS/android_manifest.git -b pie && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# I
# InvictrixRom
https://github.com/InvictrixRom/manifest


Repo init & Sync command: 

	repo init -u https://github.com/GZOSP/manifest.git -b inv-9.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch invictrix_potter-userdebug

# L

# LeanOS
https://github.com/LeanOS-Project/platform_manifest

Repo init & Sync command: 

	repo init -u https://github.com/LeanOS-Project/platform_manifest.git -b lean-9.x && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	source build/envsetup.sh && lunch lean_potter-userdebug && mka bacon lean

# LineageOS
https://github.com/LineageOS/android


Repo init & Sync command: 

	repo init -u git://github.com/LineageOS/android.git -b lineage-16.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	source build/envsetup.sh && lunch lineage_potter-userdebug && mka bacon -j48

# LiquidRemix
https://github.com/LiquidRemix/android_manifest


Repo init & Sync command: 

	repo init -u git://github.com/LiquidRemix/android_manifest.git -b pie && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && breakfast potter && time mka liquid

# LLuviaOS
https://github.com/LLuviaOS/platform_manifest

Repo init & Sync command:

	repo init -u https://github.com/LLuviaOS/platform_manifest -b 3.0 && repo sync --force-sync -j48 --no-tags --optimized-fetch --prune --no-clone-bundle
To build:

	. build/envsetup.sh && lunch lluvia_potter-userdebug && mka bacon -j48

# M

# N
# Nitrogen-project
https://github.com/nitrogen-project/android_manifest

Repo init & Sync command:

	repo init -u https://github.com/nitrogen-project/android_manifest.git -b p && repo sync -f -c -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch nitrogen_potter-userdebug && make -j48 otapackage

# NucleaRom

# O
# Omnirom
https://github.com/omnirom/android

Repo init & Sync command:

	repo init -u git://github.com/omnirom/android.git -b android-9.0 && repo sync -f -c -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# mTresk
https://github.com/mTresk/android #OMNI ROM MOD

Repo init & Sync command:

	repo init -u git://github.com/mtresk/android.git -b android-9.0 && repo sync -f -c --force-sync --no-clone-bundle -j48 --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && brunch potter

# P
# PixelExperience
https://github.com/PixelExperience/manifest

Repo init & Sync command:

	repo init -u https://github.com/PixelExperience/manifest -b pie && repo sync -f -c -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch aosp_potter-userdebug && mka bacon -j48

# PotatoProject
https://github.com/PotatoProject/manifest

Repo init & Sync command:

	repo init -u https://github.com/PotatoProject/manifest -b baked-release && repo sync -f -c -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	.source build/envsetup.sh && add_lunch_combo potato_potter-userdebug && brunch potter

# Project-Xtended
https://github.com/Project-Xtended/manifest

Repo init & Sync command:

	repo init -u https://github.com/Project-Xtended/manifest.git -b xtended && repo sync -f -c -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch xtended_potter-userdebug && mka bacon -j48

# R
# ResurrectionRemix
https://github.com/ResurrectionRemix/platform_manifest

Repo init & Sync command:

	repo init -u https://github.com/ResurrectionRemix/platform_manifest.git -b pie && repo sync -c -f -j48 --force-sync --no-clone-bundle

To build:

	. build/envsetup.sh && brunch potter

# S

# Syberia
https://github.com/syberia-project/manifest

Repo init & Sync command:

	repo init -u https://github.com/syberia-project/manifest.git -b 9.0 && repo sync -c -f -j48 --force-sync --no-clone-bundle 

To build:

	. build/envsetup.sh && brunch potter
	
# T
# TeamHorizon (XenonHD)
https://github.com/TeamHorizon/platform_manifest

Repo init & Sync command:

	repo init -u https://github.com/TeamHorizon/platform_manifest.git -b p && repo sync -c -f -j48 --force-sync --no-clone-bundle

To build:

	. build/envsetup.sh && brunch potter

# TipsyOs
https://github.com/TipsyOs/platform_manifest

Repo init & Sync command:

	repo init -u git://github.com/TipsyOs/platform_manifest.git -b 9.0 && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch tipsy_potter-userdebug && make tipsy -j48

# V
# Validus
https://github.com/ValidusOs/manifest


Repo init & Sync command:

	repo init -u https://github.com/ValidusOs/manifest.git -b 9.0 && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh &&  brunch potter
	
# ViperOS
https://github.com/Viper-Project/viper_manifest

Repo init & Sync command:

	repo init -u https://github.com/Viper-Project/viper_manifest.git -b pie && repo sync -c -f -j48 --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To build:

	. build/envsetup.sh && lunch viper_potter-userdebug && mka poison
